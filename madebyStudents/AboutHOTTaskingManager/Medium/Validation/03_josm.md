---
title: HOT Tasking ManagerのValidation におけるJOSMの使い⽅
date: 2026-05-22
original_article_date: 2025-11-03
category: Validation
project: Youth① Weekly Report
keywords:
  - HOT Tasking Manager
  - Validation
  - JOSM
  - リモート制御
source: 古橋研究室 Medium
url: https://medium.com/furuhashilab/hot-tasking-managerのvalidationにおけるjosmの使い方-youth①週報-b637c242f2a5
related_tools:
  - HOT Tasking Manager
  - JOSM
related_work:
  - Validation
  - JOSM初期設定
  - 建物直角化
---

# HOT Tasking Manager初心者向け JOSM基本操作手順書

## 記事の概要

この記事は、HOT Tasking Managerで中級マッパーへ昇格した人が、Validation（検証）へ挑戦する際に必要となるJOSMの準備方法をまとめた初心者向け解説記事です。

Validation作業に必要な、

- JOSMのダウンロード
- インストール
- 初期設定
- リモート制御の有効化

に重点を置いて説明されています。

---

# 操作手順

# Step 1. JOSMをダウンロードしてインストールする

## Windows環境の場合

1. ブラウザ（例：Microsoft Edge）で `JOSM` と検索します。
2. JOSM公式ダウンロードページへアクセスします。
3. `Windows installer (MSI, EXE)` を選択してダウンロードします。
4. インストーラーを実行し、JOSMをインストールします。

---

## 画像から確認できるポイント

### JOSMダウンロードページ

- `Windows installer (MSI, EXE)` のリンクが黄色で強調表示されている。
- 赤枠で囲まれており、ダウンロード対象として示されている。

---

# Step 2. JOSMを起動する

1. インストール完了後、JOSMを起動します。
2. 起動後、初期画面が表示されます。

---

## 画像から確認できるポイント

### JOSM起動画面

- 「JOSM - Java OpenStreetMap エディタ」という見出しが表示される。
- 画面上部に以下のメニューが表示される。

### 主なメニュー

- ファイル
- 編集
- 表示
- ツール

---

# Step 3. 「設定」画面を開く

1. 画面上部メニューの `編集` をクリックします。
2. メニュー一覧の一番下にある `設定` を選択します。

---

## ショートカットキー

| 操作 | キー |
|---|---|
| 設定を開く | `F12` |

---

## 画像から確認できるポイント

- 「設定」は `編集` メニュー最下部に配置されている。
- `F12` ショートカットが割り当てられている。

---

# Step 4. 「リモート制御」を有効にする

1. 設定ウィンドウを開きます。
2. 左側メニューからアンテナ型アイコンを選択します。
3. `リモート制御を有効` にチェックを入れます。
4. 「許可するアクション」にも必要なチェックを入れます。

---

## 画像から確認できるポイント

### リモート制御設定

- 左メニュー下から2番目にアンテナ型アイコンが存在する。
- `リモート制御を有効` のチェックボックスへチェックを入れる必要がある。
- その下の「許可するアクション」に複数チェックが入っている。

---

# Validation準備完了後

上記設定完了後、

- HOT Tasking Manager
- JOSM

を連携させ、Validation作業を実施できるようになります。

---

# 初心者が迷いやすい点

## 設定画面の開き方

- 「設定」ボタンは目立つ位置に存在しません。
- `編集` メニュー最下部から開く必要があります。

---

## リモート制御の重要性

記事内でも特に強調されている重要設定です。

### 注意点

- リモート制御を有効化し忘れると、HOT Tasking ManagerとJOSMが連携できません。

---

# 重要な用語

## HOT Tasking Manager

マッピングプロジェクト管理やValidationを行うプラットフォーム。

---

## Validation（検証）

マッピング済みデータが正しいか確認する作業。  
主に中級マッパー以上が担当します。

---

## JOSM

Java OpenStreetMap Editor の略称。  
Validation作業に使用される高度なOSM編集ソフト。

---

## リモート制御

JOSMの設定機能。  
外部アプリケーション（HOT Tasking Manager等）と連携可能にする。

---

# 画像から確認できる操作ポイント

| 画像番号 | 関連手順 | 内容 | 確認ポイント |
|---|---|---|---|
| 画像1 | Step 1 | JOSMダウンロードページ | `Windows installer (MSI, EXE)` をクリック |
| 画像2 | Step 2 | JOSM起動画面 | 正常起動を確認 |
| 画像3 | Step 3 | 編集メニュー | 「設定」を選択 |
| 画像4 | Step 4 | 設定ウィンドウ | 「リモート制御を有効」にチェック |
| 画像5 | 本文外 | グラレコ | 「図形の直角化」「タスクの検証」確認 |

---

# NotebookLMに覚えさせたいポイント

- HOT Tasking ManagerでValidationを行うにはJOSMが必要である。
- Windows環境では `Windows installer (MSI, EXE)` からインストールする。
- 初期設定では「リモート制御の有効化」が最重要である。
- Validation時は「建物の直角化」「地物同士の重なり解消」が重要なルールとなる。
- JOSMの「ツール」メニューには「図形の直角化」機能が存在する。

---

# この記事から得られる重要ポイント

- Validation作業にはJOSMを利用する。
- 事前にJOSMのインストールと初期設定が必要。
- 「リモート制御を有効化すること」が特に重要。
- Validation時には建物直角化や地物重複の解消を意識する必要がある。

---

# 出典

- 記事タイトル：HOT Tasking ManagerのValidation におけるJOSMの使い⽅【Youth①週報】
- 公開日：2025-11-03
- URL：https://medium.com/furuhashilab/hot-tasking-managerのvalidationにおけるjosmの使い方-youth①週報-b637c242f2a5
