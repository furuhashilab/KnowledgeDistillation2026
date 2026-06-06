---
title: "HOT Tasking Manager 完全操作ガイド"
category: "hot_tasking_manager"
created_date: "2026-06-06"
language: "ja"
tags: ["HOT", "Tasking-Manager", "HOT-TM", "mapping-guide", "validation", "JOSM", "iD-editor"]
sources:
  - "madebyStudents/AboutHOTTaskingManager/Youtube/Mapping/"
  - "madebyStudents/AboutHOTTaskingManager/External/"
  - "madebyStudents/AboutHOTTaskingManager/Medium/Validation/"
  - "madebyStudents/OSM_beginners_validation.md"
---

# HOT Tasking Manager 完全操作ガイド

## HOT Tasking Managerとは

HOT Tasking Manager（HTM）は、Humanitarian OpenStreetMap Team（HOT）が提供する
ボランティアマッピングを効率的に組織化するためのウェブプラットフォーム。

- **URL**: https://tasks.hotosm.org
- **目的**: 大規模な地域をグリッド（タスク）に分割し、複数人が重複なく作業できるようにする
- **利用者**: 世界中のボランティアマッパー、NGO、人道支援組織

### カラーコードの意味
| 色 | 意味 |
|---|---|
| 白（未着手） | 誰も作業していないタスク（選択可能）|
| 青（作業中） | 現在誰かが作業中（ロック中）|
| 黄（マッピング完了） | マッピング完了、バリデーション待ち |
| 緑（バリデーション済み） | 全作業完了 |
| 赤（無効化） | 問題あり、再マッピングが必要 |

---

## マッピング手順（2025年版）

### ステップ1: アカウント作成

#### OSMアカウント（必須）
1. https://www.openstreetmap.org にアクセス
2. 右上の「Sign Up」をクリック
3. メールアドレス、ユーザー名、パスワードを設定
4. 確認メールのリンクをクリックして認証完了

#### HOT Tasking Managerへのログイン
1. https://tasks.hotosm.org にアクセス
2. OSMアカウントでログイン（右上のログインボタン）
3. オープンデータ条項への同意が必要

### ステップ2: プロジェクト選択

1. Tasking Managerのトップページでプロジェクト一覧を確認
2. 検索フィールドで地名やプロジェクト番号を検索
3. 難易度（BEGINNER / INTERMEDIATE / ADVANCED）を確認
4. プロジェクトの「Instructions（指示書）」を必ず読む

### ステップ3: タスク選択

1. 地図上の白い（未着手）グリッドを選択
2. 小さなエリアから始める（初心者は特に重要）
3. 「Map Selected Task」（または「このタスクをマッピング」）をクリック
4. エディタが起動する

### ステップ4: マッピング作業（iD Editor使用）

1. 「Area（エリア）」ツールを選択（キー: `3`）
2. 建物の角を順にクリックして輪郭をトレース
   - **注意**: 建物の屋根ではなく基礎（フットプリント）をトレース
3. ダブルクリックまたはEnterで形状を確定
4. 左メニューから「Buildings（General）」を選択してタグ付け
5. 右クリック → 「Straighten」（または`Q`キー）で直角化
6. 担当エリア内の全建物をマッピング
7. 「Save」→「Upload」でOSMに保存

### ステップ5: タスク完了報告

1. HOT Tasking Managerに戻る（OSMではなくHTMで完了報告）
2. 「Is this area completely mapped?（このエリアは完全にマッピングされましたか？）」に回答
   - **Yes**: 確実に完了している場合のみ
   - **No**: 未完了部分がある場合（正直に報告することが重要）
3. 「Post Task」をクリックして提出

---

## バリデーション（検証）手順

バリデーションとは、他のマッパーの作業を確認・品質検査するプロセス。
通常「中級マッパー（250回以上の保存実績）」以上が担当。

### バリデーション前準備

#### 推奨エディタ: JOSM
- バリデーション機能が充実しているためJOSMが推奨
- JOSMのRemote Controlを有効化する（必須）

#### JOSMのRemote Control有効化手順
1. JOSMを起動
2. Edit → Settings（`F12`）を開く
3. 左メニューのアンテナアイコンを選択
4. 「Enable Remote Control」にチェック
5. 「Allowed Actions」で許可する操作を設定
6. OKをクリック

### バリデーションプロセス

#### ステップ1: 作業指示書の再確認
- プロジェクトの指示書を熟読
- 必要なマッピング対象・タグを確認

#### ステップ2: JOSMでのデータ読み込み
1. HTMでバリデーション対象タスクを選択
2. 「Edit with JOSM」をクリック
3. Remote Control経由でJOSMにデータが読み込まれる

#### ステップ3: 初期スキャン
- タスクエリア全体を素早く確認
- ほぼ未マッピングで「完了」マークされている → 即座に無効化（Invalidate）

#### ステップ4: 検証ツールの実行
JOSMの「Validation」機能を使用:
- 建物の重複・交差を検出
- 道路の接続エラーを検出
- 自動修正可能な問題をリスト表示

#### ステップ5: 建物の確認・修正
- 未マッピングの建物を追加
- 建物の直角化（Orthogonalize Shape）を確認
- 特殊な建物形状（円形建物など）の適切な処理

#### ステップ6: 道路（Highway）の確認
- 適切なタグ付けの確認
- 道路が適切に接続しているか（ルーティングに影響）
- 孤立した道路セグメントがないか確認

#### ステップ7: バリデーション完了
- 小さな問題 → 修正してValidate（承認）
- 重大な問題 → Invalidate（無効化）+ コメントで問題点を具体的に記述

### バリデーション判断基準

| 状況 | 対応 |
|---|---|
| ほぼ完璧、軽微な修正で済む | 自分で修正してValidate |
| 建物の直角化が必要 | 直角化してValidate |
| 大量の未マッピング建物 | Invalidate（コメント必須）|
| タスクがほぼ空 | Invalidate（コメント必須）|
| 重複・交差が多数 | Invalidate（コメント必須）|

### バリデーションの注意事項
1. **自分でマッピングしたタスクを自分でバリデーションしない**（利益相反）
2. **古い編集にコメントしない**（最近の編集だけにフィードバック）
3. 判断に迷う場合は「軽微 → 直して承認」「重大 → 無効化」を基本とする
4. バリデーターは品質管理者であると同時に新人マッパーの教師でもある

---

## よくある初心者ミスとその対処

### 選択ミス
| ミス | 対処 |
|---|---|
| 大きすぎるエリアを選択 | 小さなグリッドから始める |
| 完了済み（青/緑）エリアを選択 | 白いエリアのみ選択 |
| 他人が作業中（ロック中）のタスク | 別の白いタスクを選択 |

### マッピングミス
| ミス | 対処 |
|---|---|
| 直角化を忘れる | `Q`キーを常に使う習慣をつける |
| タグを付けない | 形状確定後、必ずタグを付与 |
| 道路に建物ノードを接続 | 建物は道路と分離してトレース |
| フィーチャー同士が重複 | 重複を確認・削除してからアップロード |
| 農地と森林を混同 | 衛星画像の色調・テクスチャで判断 |

### 技術的ミス
| ミス | 対処 |
|---|---|
| アップロードを忘れる | 定期的に`Ctrl+S`でセーブ、最後にUpload |
| JOSM Remote Controlが無効 | 設定でEnable Remote Controlにチェック |
| iDとJOSMの混同 | バリデーションはJOSM推奨 |
| 完了質問に不正確な回答 | 完全に終わったときだけYes |

---

## 編集ツール比較表

| 項目 | iD Editor | JOSM |
|---|---|---|
| 動作環境 | ブラウザ | デスクトップ（Java必要）|
| 難易度 | 初心者向け | 中〜上級者向け |
| 建物マッピング | 約5クリック/棟 | 約2クリック/棟（プラグイン使用）|
| オフライン | 不可 | 可能（データ事前読み込み）|
| 検証機能 | 基本的な検証のみ | 強力な検証ツール |
| バリデーション | 限定的 | 主要エディタ |
| 直角化ショートカット | `Q` または `S` | Tools → Orthogonalize Shape |

---

## バージョン履歴・更新記録

| バージョン | 時期 | 主な変更点 |
|---|---|---|
| HTM v.4 | 2020年頃 | インターフェース改善 |
| HTM 2021年版 | 2021年11月 | 現行UIに近い形 |
| HTM 2025年版 | 2025年1月 | 最新機能追加 |

---

## 学習リソース

| リソース | 内容 | URL/参照 |
|---|---|---|
| HOT Tasking Manager 4 使い方（2021） | 古橋研究室制作動画 | https://youtu.be/hI8Mwxpyon4 |
| Tasking Manager 2019年版 | 古橋研究室 真部氏制作 | https://youtu.be/d8CPTLUkLIw |
| YouthMappers Mapathon 2025 | ヨロン島マパソン向け | https://youtu.be/6taiWYx0B54 |
| OSM Wiki バリデーションガイド | 公式英語解説 | https://wiki.openstreetmap.org/wiki/Tasking_Manager/Validating_data |
| JOSM バリデーション動画（2017） | 英語チュートリアル | https://www.youtube.com/watch?v=k-tVk_7IePM |
