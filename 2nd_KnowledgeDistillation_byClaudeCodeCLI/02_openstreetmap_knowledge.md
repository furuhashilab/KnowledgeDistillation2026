---
title: "OpenStreetMap 知識体系"
category: "osm_knowledge"
created_date: "2026-06-06"
language: "ja"
tags: ["OpenStreetMap", "OSM", "mapping", "JOSM", "iD-editor", "tools", "tagging"]
sources:
  - "madebyStudents/OurBlogs_onMedium/02_openstreetmap.md"
  - "madebyStudents/AboutHOTTaskingManager/"
  - "madebyStudents/OSM_beginners_validation.md"
---

# OpenStreetMap（OSM）知識体系

## OpenStreetMapとは

OpenStreetMap（OSM）は「地図のWikipedia」とも呼ばれる、自由に編集可能なオープン地図データベース。

| 項目 | 内容 |
|---|---|
| **設立** | 2004年 |
| **アカウント数** | 約1,000万アカウント（2025年時点） |
| **日次アクティブマッパー** | 約6,000人 |
| **ライセンス** | Open Database License (ODbL) |
| **URL** | https://www.openstreetmap.org |

### ビジネス・社会での活用例
- Pokémon GO（Niantic）
- Instagram、Facebook
- Apple Maps（一部データ）
- Grab（東南アジアの配車アプリ）
- MAPS.ME（オフライン地図）
- 国連・NGOの人道支援活動

---

## OSM編集エディタ

### iD Editor（ブラウザ版）
- **対象**: 初心者〜中級者
- **アクセス**: https://www.openstreetmap.org → Editボタン
- **特徴**: ブラウザ上で動作、直感的な操作

| ショートカット | 機能 |
|---|---|
| `3` | エリア（ポリゴン）ツール選択 |
| `S` | 直角化（Straighten） |
| `Q` | 直角化（Orthogonalize） |
| `Ctrl+Z` | アンドゥ |

**効率**: 建物1棟あたり約5クリック

### JOSM（Java OpenStreetMap Editor）
- **対象**: 中級〜上級者
- **ダウンロード**: https://josm.openstreetmap.de/
- **特徴**: デスクトップアプリ、プラグイン対応、検証機能が強力

#### JOSMのセットアップ手順
1. 公式サイトからインストール（MSI/EXE形式）
2. 起動後、設定を開く（`F12`キー or Edit → Settings）
3. **Remote Control を有効化**（必須）
   - 設定画面でアンテナアイコンを選択
   - 「Enable Remote Control」にチェック
   - 「Allowed Actions」を設定
   - ※これがないとHOT Tasking ManagerとJOSMが連携できない
4. buildings_pluginをインストール（建物マッピング効率化）

**効率**: buildings_plugin使用時、建物1棟あたり約2クリック

#### 主要JOSMプラグイン
| プラグイン名 | 用途 |
|---|---|
| buildings_plugin | 建物描画の高速化（2クリック）|
| HOT-OSM-Validation スタイル | バリデーション時の誤り可視化（赤三角表示）|
| mapathonerplug-in | マパソン向け機能追加 |

### その他のOSMツール
| ツール | 用途 |
|---|---|
| **Go Map!!** | iOSアプリ、モバイルOSM編集 |
| **Mapswipe** | 衛星画像スワイプで人道支援エリア特定 |
| **Field Papers** | 紙地図を使ったフィールド調査→OSM入力 |
| **Wheelmap** | 車椅子アクセシビリティマッピング |
| **Mapillary** | ストリートビュー画像共有・360度写真 |
| **MAPS.ME** | オフライン利用可能なOSMビューア |

---

## OSMタギング（属性付与）の基礎

タグとは、地物に属性を付与するキー＝バリューのペア。

### 主要タグカテゴリ
| カテゴリ | タグ例 |
|---|---|
| 建物 | `building=yes`, `building=house`, `building=residential` |
| 道路 | `highway=primary`, `highway=residential`, `highway=path` |
| 農地 | `landuse=farmland`, `landuse=forest` |
| 施設 | `amenity=hospital`, `amenity=school`, `amenity=restaurant` |
| アクセシビリティ | `wheelchair=yes/no/limited` |

### タギングの注意事項
- 道路と農地をノードで接続しない（トポロジー分離を維持）
- 建物は屋根ではなく**建物基礎（フットプリント）**をトレース
- コミュニティのタグ慣習に従う（OSM WikiやTagInfo参照）

---

## 建物マッピングの手順（標準手順）

### iD Editorでの建物マッピング
1. プロジェクトを開く（HOT Tasking Manager経由）
2. 担当タスク（白いグリッド）を選択
3. 「Area（エリア）」ツールを選択
4. 建物の角を順にクリックして輪郭をトレース
5. ダブルクリックまたはEnterで確定
6. 左メニューで「Buildings（General）」タグを付与
7. 右クリック → 「Straighten」（または`Q`）で直角化
8. 「Save」→「Upload」でOSMにアップロード

### 直角化（Orthogonalization）の重要性
- 実際の建物は直角コーナーを持つため、マッピングでも直角化が必須
- 直角化なしのデータはデータ品質が低いとみなされる
- 検証者（バリデーター）が直角化を確認・修正する

---

## OSM × 古橋研究室の主要プロジェクト

### ラーメン二郎マッピング（継続プロジェクト）
- **開始**: 2018年（渡辺氏の卒論）
- **内容**: チェーン店舗のOSM登録（40店舗）
- **継続**: 2020年（余田氏）、2021年（鈴木氏）と受け継がれた研究系譜

### PLATEAUデータのOSMインポート
- 国土交通省PLATEAUの3D都市モデルデータをOSMに取り込む
- 建物フットプリントの大量追加が可能

### Wheelmap拡張（車椅子アクセシビリティ）
- 多機能トイレ・車椅子スロープのOSMマッピング
- 駅周辺エリア（まち・駅エリア）での調査実施

### YouthMappers AGUの活動
- 国際的なYouthMappersネットワーク（30校以上）に所属
- 毎年複数のマパソンを主催・参加
- 2025年度：ヨロン島マパソン（2025年1月）、タイ洪水支援（2024年12月）

---

## OSMデータ活用の注意事項

1. **クレジット表記**: 「© OpenStreetMap contributors」の明示が必須
2. **ODbLライセンス**: 派生物の共有義務（シェアアライク）
3. **データ鮮度**: 衛星画像と地物の時差（10年以上ずれることもある）
4. **公式データとの差異**: トイレ情報、番地情報など公式データとのズレに注意
5. **継続更新の課題**: 一度マッピングしても継続更新が必要

---

## UN Maps Learning Hub（日本語化プロジェクト）

- 国連のマッピング学習リソースを日本語に翻訳
- 古橋研究室が翻訳・普及活動に参加
