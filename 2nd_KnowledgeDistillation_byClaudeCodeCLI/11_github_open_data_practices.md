---
title: "GitHub運用・オープンデータ実践"
category: "github_open_data"
created_date: "2026-06-06"
language: "ja"
tags: ["GitHub", "open-data", "practices", "repositories", "Issues", "Pages", "license"]
sources:
  - "madebyStudents/GitHub_Knowledge/design.md"
  - "madebyStudents/GitHub_Knowledge/drone.md"
  - "madebyStudents/GitHub_Knowledge/hackathon.md"
  - "madebyStudents/GitHub_Knowledge/vf.md"
  - "madebyStudents/GitHub_Knowledge/other.md"
  - "madebyStudents/Paast_thesis_papers/04_tool_index(4).md"
---

# GitHub運用・オープンデータ実践

## 研究室のGitHub方針

### 基本原則
> 「全ての成果物をGitHubでパブリック公開する」

- 卒業論文リポジトリ: パブリック公開が原則
- 研究データ: オープンライセンス付与
- Medium記事との連携: コードとブログ記事をセットで公開
- 失敗記録も含めた透明性の確保

### GitHub Organization
- **URL**: https://github.com/furuhashilab
- **主要Organization**: 古橋研究室公式
- **個人リポジトリ**: 学生個人のGitHubアカウントでも管理

---

## リポジトリ命名規則

### GSCゼミ論・卒論
```
{year}gsc_{FirstName}-{LastName}
例: 2025gsc_Kentaro-Takai
```

### 卒論コレクション
```
sotsuron{year}
例: sotsuron2022
```

### プロジェクト別
```
Hackathon_{month}         # ハッカソン
drone_{specialization}    # ドローン特化
oam4{location}            # OpenAerialMap + 地名
fc_{ProjectName}          # 研究室（furuhashi lab）
{project}_{year}          # その他
```

---

## GitHub Issues の活用方法

### ハッカソン・プロジェクト管理
Issues はタスク管理・作業記録の中心的な場。

#### 標準的なIssueパターン
```
#1 Application（応募書類・申請）
#2 Slides（プレゼン資料制作）
#3 Medium（ブログ記事）
#4 Graphic Recording（グラレコ）
#5 Illustration（イラスト・図）
```

#### Issues の特徴的運用
- **全オープン状態が多い**: 完了しても閉じないことが多い（記録として残す）
- **スクリーンショット多用**: 作業進捗をスクリーンショットでコメント
- **複数人でのクローズドループ**: 担当者が直接コメントして記録

### Issues × GitHub Projects
- 2020年のハッカソンからGitHub Projectsでのカンバン管理を開始
- PDCAサイクルへの準拠を意識（2020年6月ハッカソン）

---

## GitHub Pages の活用

### 主な用途
- 研究成果のウェブ公開（HTMLマップ等）
- ハッカソン成果物の公開
- ドキュメントサイト（Jekyll/Gatsby.js）

### 活用例
| リポジトリ | 内容 |
|---|---|
| shikuchoson-hazardmap-template | 自治体向けハザードマップ（Leaflet）|
| style-template4unvtcharites | ベクタータイルスタイルテンプレート |
| hakone-ekiden | 3Dリアルタイムスポーツ可視化 |
| logos4gsc2024 | GSC学部ブランドアイデンティティ |
| UNVT_Hackathon_Meetup2022_Drone | ドローンハッカソン成果 |

---

## ライセンス運用

### 主要ライセンス一覧

| ライセンス | 用途 | 特徴 |
|---|---|---|
| **MIT License** | コード | 最も自由度が高い、商用利用可 |
| **CC BY 4.0** | コンテンツ・データ | 氏名表示が必要 |
| **CC BY-NC-SA 4.0** | 一部コンテンツ | 非商用・継承が条件 |
| **ODbL** | OSMデータ | OpenStreetMap公式ライセンス |

### ライセンス適用事例
- 研究室プロモーション動画: **CC BY 4.0**
- logos4gsc2024リポジトリ: **CC BY-NC-SA 4.0**
- OSMを含む成果: **ODbL**表記必須

---

## 主要リポジトリカタログ

### デザイン・地図可視化カテゴリ

| リポジトリ | 概要 | ツール |
|---|---|---|
| fc_SpatialDesign | デザイン基礎、色彩理論 | Markdown, Medium |
| shikuchoson-hazardmap-template | 自治体ハザードマップ | Leaflet, TypeScript, GitHub Pages |
| style-template4unvtcharites | ベクタータイルスタイル | UNVT/Charites CLI, Geolonia Map |
| hakone-ekiden | 箱根駅伝3D可視化 | JavaScript, 3Dマッピング |
| maplibre_tutorial_usucase | MapLibre GL JS 学習 | MapLibre, ラスターオーバーレイ |
| city-roads | OSM道路ネットワーク可視化 | フォーク（anvaka/city-roads）|
| areamap | 都道府県コロプレスマップ | 表形式地図 |
| tokyo-vector-tile | 東京オープンデータVT | 550MB, 東京都と共同 |
| JampMap | ハイキュー！！キャラ位置マップ | Mapbox Studio, インターンシップ |
| logos4gsc2024 | GSCロゴ・ブランドアイデンティティ | CC BY-NC-SA 4.0 |

### ドローンカテゴリ

| リポジトリ | 概要 | ツール |
|---|---|---|
| drone | ドローンカタログ、航空法 | GitHub Issues, PDF |
| drone_gacha | ガチャ用3Dドローンモデル | Blender, STL |
| dronegacha | 3Dドローンモデル（複数機種）| Blender, STL |
| oam4kusatsu | 草津市空撮 → OAM登録 | GeoTIFF, XYZ タイル |
| yokozeriver2022 | 横瀬川UAV測量 | UAV, SfM, オルソ |
| drone_UN-EC_OSS4SDG_hachathon2022 | UNVT PortableへのDrone統合 | Raspberry Pi, UNVT |
| drone1_3dprinting_project | 3Dプリントドローン | Blender, 3Dプリンター |
| UNVT_Hackathon_Meetup2022_Drone | UNVT点群処理 | PDAL, Ruby, Mapbox Studio |

### Video & Film (V&F) カテゴリ

| リポジトリ | 概要 | ツール |
|---|---|---|
| fc_creativeVideo | 映像編集知識ベース | Adobe Premiere Pro, After Effects |
| Hackathon_07 | 7ヶ月ハッカソン記録 | 映像制作全工程 |
| ShibuyaUrarojiStreetView | 渋谷裏路地ストリートビュー | Mapillary, 360°カメラ |
| googleearthstudio | GEStudio → MP4変換 | FFmpeg |
| 2020_TEDxdesign | TEDx AGU 2020 バーチャル | OBS, Gatsby.js, STYLY |
| makingmovie4furuhashilab2025 | 2025年プロモーション動画 | Premiere Pro |
| furuhashilab_movie_2024 | 2024年プロモーション動画 | CC BY 4.0 |

### ハッカソンカテゴリ

| リポジトリ | 概要 |
|---|---|
| UNVT-Hackathon-Meetup-2022_YouthMappers_AGU | OAM GeoTIFF → ベクタータイル |
| hackathon_yokozemap | 横瀬町マップ制作ハッカソン |
| hachathon_3dmodel | ガチャ3Dモデルハッカソン |
| fc_game | ゲームハッカソン（タコヤキウインナー）|
| gsi_airportmap | 国土地理院ハッカソン、飛行制限可視化 |
| ingress-mission- | 位置情報ゲーム × GSI マップ |
| OSM-GSI | Wheelmap + GSI マップ統合 |
| GeoGachaHackathon_Drone_202211 | ジオガチャハッカソン |

---

## Medium との連携

### 基本方針
- 研究室の**全メンバーが週報をMediumに投稿**（必須）
- ハッカソン成果: 必ずMedium記事を作成
- コードリポジトリとMedium記事をセットで管理

### Mediumの位置づけ
```
GitHub（技術的詳細）+ Medium（解説・考察・ストーリー）= 完全なドキュメント
```

### 記事URL例
- 研究室Medium: https://medium.com/furuhashilab
- タグ: furuhashilab, openstreetmap, crisis-mapping 等

---

## オープンデータの重要性

### 研究室が重視するオープン性の理由
1. **再現性の確保**: 手法・データを公開することで他者が検証可能
2. **技術継承**: 次世代学生が先輩の成果を引き継げる
3. **社会貢献**: 研究成果が広く社会で活用される
4. **OSMコミュニティへの貢献**: データが世界中で再利用される

### 失敗記録の公開（重要文化）
- 「失敗したこと・うまくいかなかったこと」も記録してGitHubに公開
- 次世代学生が同じ失敗を繰り返さないための知識資産

---

## 技術的ベストプラクティス

### README の必須要素
```markdown
## プロジェクト名
## 概要
## 使い方
## データソース・ライセンス
## 著者
## 関連リンク（Medium記事・発表資料等）
```

### Issueテンプレート
- ハッカソン: Application / Slides / Medium / グラレコ の4点セット
- 研究: 課題定義 / 手法 / 進捗記録 / 成果 の4ステップ

### ブランチ戦略
- `main/master`: 最終成果物
- `gh-pages`: GitHub Pages 公開用
- `feature/xxx`: 作業ブランチ（一部プロジェクト）
