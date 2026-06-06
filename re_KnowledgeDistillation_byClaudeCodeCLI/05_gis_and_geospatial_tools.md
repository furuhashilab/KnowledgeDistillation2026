---
title: "GIS・地理空間ツール体系"
category: "gis_tools"
created_date: "2026-06-06"
language: "ja"
tags: ["GIS", "QGIS", "Mapbox", "MapLibre", "geospatial", "tools", "vector-tiles", "Re:Earth"]
sources:
  - "madebyStudents/OurBlogs_onMedium/05_gis_tools.md"
  - "madebyStudents/Paast_thesis_papers/04_tool_index(4).md"
  - "madebyStudents/YouTubeContents/furuhashilab.youtube4.md"
---

# GIS・地理空間ツール体系

## ツール利用頻度ランキング（研究室全体、1,164ファイル分析）

| 順位 | ツール | 出現回数 | 主な役割 |
|---|---|---|---|
| 1 | **GitHub** | 1,159 | 成果公開、データ共有、Issues管理、GitHub Pages |
| 2 | **JavaScript/HTML/CSS** | 227 | Webマッピング、可視化 |
| 3 | **Medium** | 199 | 週報、成果発信、活動記録 |
| 4 | **OpenStreetMap** | 119 | 参加型データ基盤 |
| 5 | **ドローン/UAV** | 92 | 空撮、点群取得、オルソモザイク |
| 6 | **QGIS** | 92 | 空間分析、ルート・勾配・カバレッジ評価 |
| 7 | **Python** | 84 | データ処理、APIスクリプト、バックエンド |
| 8 | **Google Sheets** | 74 | データ整理、調査集計、タグプロトタイプ |
| 9 | **Zoom** | 59 | 画面録画、リモート動画制作 |
| 10 | **PLATEAU** | 55 | 3D都市モデル、LOD建物、Minecraft/OSM変換 |
| 11 | **Mapbox** | 52 | Webマップスタイリング、3Dレンダリング |
| 12 | **Google Earth** | 51 | ストーリー可視化、歴史オーバーレイ |
| 13 | **Blender** | 30 | 3Dモデリング、点群処理 |
| 14 | **Google Maps** | 27 | 観光・アクセシビリティアプリ基盤 |
| 15 | **ChatGPT** | 25 | テキスト整形、コード支援、テクスチャ生成 |

---

## ツール別詳細解説

### QGIS（オープンソースGIS）
- **用途**: 空間分析、テーマ別地図作成、DID（人口集中地区）分析
- **ライセンス**: GNU GPL（無料・オープンソース）
- **特徴**: Shapefileや GeoJSON、PostGIS等、多様なデータ形式に対応
- **研究室での使用例**:
  - 通勤経路の勾配・効率分析
  - GeoTIFF → XYZ タイル変換（oam4kusatsu）
  - 避難経路の空間分析
  - 農地・森林カバー率の解析
  - tippecanoeとの連携でベクタータイル生成

### Mapbox / MapLibre GL JS
- **Mapbox GL JS**: 商用ベクタータイルライブラリ（アクセストークン必要）
- **MapLibre GL JS**: Mapboxのオープンソースフォーク（無料）
- **使用例**:
  - Mapbox Studio によるスタイル作成
  - ベクタータイルによる滑らかな3D表示
  - 建物の3D押し出し表示
  - カスタムスタイル・配色設計
  - 研究室ハッカソン（UNVT Hackathon Meetup 2022）でも活用

```javascript
// MapLibre GL JS 基本例
const map = new maplibregl.Map({
  container: 'map',
  style: 'https://demotiles.maplibre.org/style.json',
  center: [139.69, 35.69], // 東京
  zoom: 10
});
```

### Google Earth / Google Earth Studio
- **Google Earth**: ストーリー語り型の地理情報可視化
- **Google Earth Engine（GEE）**: 衛星データの大規模解析プラットフォーム
  - NDVI（植生指数）計算サンプルスクリプトが整備済み
  - JavaScriptベースのAPI
  - Inspector toolで任意地点のデータ確認
- **Google Earth Studio**: JPEGシーケンス出力 → FFmpeg で MP4変換
  ```bash
  # Google Earth Studio の動画変換
  ffmpeg -pattern_type none -r 30 -i frame_%04d.jpg -r 60 output.mp4
  ```

### Re:Earth
- **用途**: 3D空間ストーリーテリング、災害アーカイブ
- **ライセンス**: オープンソース
- **研究室での使用例**:
  - 令和2年7月豪雨のアーカイブ
  - Strava GPX → geojson.io → GeoJSON → Re:Earthインポート
  - カメラアングルと写真を連動させたストーリーテリング
- **ワークフロー例**:
  ```
  Strava GPXデータ → geojson.io → GeoJSON形式変換 → Re:Earth読み込み
  → カメラアングル設定 → 写真リンク付きストーリー公開
  ```

### PLATEAU（Project PLATEAU）
- **提供**: 国土交通省
- **内容**: 日本全国の3D都市モデル（CityGML形式）
- **LODレベル**:
  - LOD0: 建物フットプリント
  - LOD1: 押し出し3D（高さ情報あり）
  - LOD2: 詳細外観（屋根形状等）
  - LOD3: 内部構造含む詳細モデル
- **研究室での活用**:
  - OSMへのビルデータインポート
  - Blenderでの3D都市可視化
  - Minecraftへの変換（防災教育）
  - GitHub Pages での3D表示

---

## ツールエコシステム別分類

### GISエコシステム
```
QGIS ←→ JOSM ←→ iD Editor ←→ ArcGIS
  ↓          ↓
PDAL      CloudCompare
（点群処理）  （点群処理・可視化）
```

### 3Dパイプライン
```
PLATEAU（CityGML）→ Blender → Sketchfab/Minecraft/GitHub Pages
                  ↓
              3Dプリンター（STLエクスポート）
```

### Webマッピングスタック
```
データ: OpenStreetMap / PLATEAU / 独自調査データ
  ↓
処理: QGIS / Python / tippecanoe（ベクタータイル生成）
  ↓
配信: tileserver-gl-light / Mapbox / MapLibre
  ↓
表示: MapLibre GL JS / Leaflet / JavaScript
```

### 災害対応スタック
```
Raspberry Pi + UNVT Portable
→ オフラインベクタータイルサーバー
→ 通信途絶環境での地図配信
→ Re:Earth / MAPS.ME / OSM（支援活動向け）
```

### データフロー
```
Google Sheets → Python/QGIS → GitHub → Medium → 一般公開
```

---

## 新興ツール組み合わせ（2024〜2025年）

| 組み合わせ | 用途 |
|---|---|
| Spotify API + Next.js + Supabase + OpenWeatherMap | 音楽と場所を連動させたウォーキングマップ |
| PLATEAU + Minecraft + ChatGPT | 防災教育用3D都市体験 |
| NotebookLM + Wikipedia → GeoJSON | 歴史GIS再構築 |
| Figma + Canvas + モバイルアクセシビリティ | 反復的デザインプロセス |
| Strava GPX + Mapillary Uploader | 360°カメラのGPS紐付け |

---

## ベクタータイル技術

### 基本概念
- **ベクタータイル**: 小さな地理的グリッドに数値データを格納
- **メリット**: ズームインしても画像がぼけない、クライアント側でスタイル変更可能
- **対比**: ラスタータイル（画像ファイル）はズームでぼける

### 技術スタック
| ツール | 役割 |
|---|---|
| **tippecanoe** | GeoJSON → MVT（Mapbox Vector Tile）生成 |
| **tileserver-gl-light** | ベクタータイルの配信サーバー |
| **UNVT/Charites** | スタイル作成CLIツール |
| **MapLibre GL JS** | フロントエンドレンダリング |

### UNVT Portable（Raspberry Piサーバー）
- **目的**: 通信インフラのない環境でのオフライン地図配信
- **構成**: Raspberry Pi + 独自ビルドのUNVTソフトウェア
- **用途**: 災害時の現地オフライン地図配信
- **実績**: 能登半島地震対応、OpenDroneMap Global Meet-Up UR24で発表

---

## Mapillary活用

### 基本用途
- ストリートビュー画像の撮影・共有
- 360°カメラ（Insta360、Ricoh Theta等）での撮影
- OSMデータの補完（建物・道路・施設の確認）

### GPS付与ワークフロー（GPS非搭載カメラの場合）
```
Strava等でGPXログ記録
→ Mapillary Uploader でGPXファイルを選択してGPS埋め込み
→ Mapillaryに自動アップロード（OFF推奨、品質管理のため手動チェック）
```

### 活用事例
- Shibuya裏路地ストリートビュープロジェクト
- ミラノ・ドゥオーモの3D点群可視化
- Mapillary/OSMオンラインミートアップ #18 で発表

---

## ツール選択のガイドライン（研究テーマ別）

| 研究タイプ | 推奨ツール群 |
|---|---|
| OSM整備 | JOSM, iD Editor, Google Sheets, GitHub |
| GIS空間分析 | QGIS, GPX/Strava, Python, Google Sheets |
| 3D都市モデル | PLATEAU, Blender, CloudCompare, Sketchfab |
| Webマップ実装 | MapLibre GL JS, Mapbox, JavaScript, GitHub Pages |
| 災害対応 | Re:Earth, UNVT Portable, Raspberry Pi, PLATEAU, Minecraft |
| 教育・技術継承 | Zoom動画, iMovie, Medium, GitHub, Glide |
| AI支援研究 | ChatGPT, NotebookLM, Midjourney, Notion |
