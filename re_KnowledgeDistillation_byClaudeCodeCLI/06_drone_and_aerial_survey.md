---
title: "ドローン活動・空撮測量"
category: "drone_operations"
created_date: "2026-06-06"
language: "ja"
tags: ["drone", "UAV", "aerial-survey", "OpenDroneMap", "ODM", "orthomosaic", "3D-printing", "DJI"]
sources:
  - "madebyStudents/OurBlogs_onMedium/05_gis_tools.md"
  - "madebyStudents/GitHub_Knowledge/drone.md"
  - "madebyStudents/YouTubeContents/furuhashilab.youtube4.md"
---

# ドローン活動・空撮測量

## 研究室ドローン部門の概要

古橋研究室のドローン部門は、災害対応研究・空撮測量・3Dモデリング・ガチャ商品制作など多岐にわたる活動を展開。

- **資格取得**: ドローン国家資格（2022年制度化）取得を推進
- **主要活動**: 空撮、点群処理、オルソモザイク生成、3Dプリント用モデリング
- **社会貢献**: DRONEBIRD構想（災害時の緊急ドローン展開）

---

## 使用ドローン機体

### 主要保有・活用機体

| メーカー | 機種名 | 用途 |
|---|---|---|
| DJI | Phantom 4 | 空撮、測量（主力機）|
| DJI | Mavic Air | 軽量携帯用空撮 |
| DJI | Phantom 2 | 旧型機 |
| DJI | Tello | 室内練習・入門 |
| Parrot | Disco FPV | FPV飛行 |
| Parrot | Anafi | コンパクト空撮 |
| Skydio | 2 | 自律飛行・追従 |
| SenseFly | eBee X | 固定翼型測量機 |
| Aerosense | Aerobo | 業務用 |
| Sony | Airpeak | 業務用高性能 |

### DJI Phantom 4 仕様（主力機）
- **最大飛行時間**: 約28分
- **最大飛行速度**: 72km/h
- **カメラ**: 1インチCMOSセンサー、4K動画
- **GPS**: マルチGNSS対応
- **重量**: 約1.38kg

---

## 空撮規制と手続き

### DID（人口集中地区）規制
- 住宅が密集した地区での飛行には事前許可が必要
- **航空法上の規制**:
  - 高度150m以上: 許可申請が必要
  - DIDエリア: 国土交通省への許可申請が必要
  - 夜間飛行、目視外飛行: 追加許可が必要
- **DID地区の判定**: QGISで国勢調査データと重ねて確認可能

### 飛行前チェックリスト
1. 天候確認（Windy アプリ推奨）
2. 飛行エリアの規制確認
3. バッテリー充電確認
4. 機体プリフライトチェック
5. 許可証の持参（必要な場合）

### 風の影響
- 風速5m/s以上での飛行は避ける
- ホバリング練習から始める（特にトイドローン）
- GSD（地上サンプル距離）計算: 高度と焦点距離から解像度を決定

---

## 空撮データ処理

### OpenDroneMap（ODM）
- **URL**: https://www.opendronemap.org/
- **用途**: ドローン空撮写真からオルソモザイク・点群・3Dメッシュを生成
- **ライセンス**: オープンソース
- **入力**: 複数の重複する空撮写真
- **出力**: オルソモザイク（GeoTIFF）、点群（LAS/LAZ）、DSM/DTM

#### ODM処理ワークフロー
```
ドローン空撮（70%以上の重複率）
→ 写真の整理・GCPポイント設定（高精度化）
→ OpenDroneMap処理（SfM: Structure from Motion）
→ オルソモザイク生成（GeoTIFF形式）
→ OpenAerialMap（OAM）にアップロード
→ HOT Tasking Manager経由で世界に公開
```

### OpenAerialMap（OAM）
- **URL**: https://openaerialmap.org/
- **用途**: ドローン航空写真のオープン共有・アーカイブ
- **研究室プロジェクト**: oam4kusatsu（滋賀県草津市・大津市エリアのGeoTIFF/XYZタイル）
- **ワークフロー**: Google Drive/Slack/GitHub で10名以上が協力

### 点群処理ツール
| ツール | 用途 |
|---|---|
| PDAL | 点群データパイプライン処理 |
| CloudCompare | 点群の可視化・比較・フィルタリング |
| Potree | Webブラウザ上での点群3D表示 |
| Blender | 点群のシーン合成・可視化 |

---

## NIST STM（ドローンパイロット技能評価）

### NIST Standard Test Methods for Small Unmanned Aerial Systems
- **目的**: 無人機パイロットのスキルを標準化された方法で評価
- **適用**: 古橋研究室ではSTMに基づくドローン訓練を実施
- **主な評価項目**:
  - ホバリング精度
  - 狭路飛行
  - 障害物回避
  - 指定エリア内飛行

---

## DRONEBIRDコンセプト

### 概要
DRONEBIRD（ドローンバード）は古橋研究室が提唱する災害対応ドローン展開の枠組み。

- **理念**: 鳥のように迅速・柔軟にドローンを災害現場に展開
- **目的**: 衛星画像が取得できない状況でもオルソ画像を緊急生成
- **実績**: 能登半島地震（2024年）では200,000棟・1,900km道路データを迅速更新
- **発表**: OpenDroneMap Global Meet-Up UR24（2024年6月）

### Raspberry Pi + UNVT Portable との連携
```
ドローン空撮
→ ODMでオルソモザイク生成
→ Raspberry Pi上のUNVT Portableサーバーに格納
→ 現地WiFiでオフライン配信（通信インフラ不要）
→ 支援隊員がスマートフォンで利用
```

---

## 3Dプリントプロジェクト（ドローンガチャ）

### ドローン3Dモデリング → ガチャ商品制作
研究室の「ジオ展」でガチャ（カプセルトイ）として販売するドローンモデルの制作。

#### 制作フロー
```
実機ドローンの資料収集・計測
→ Blenderで3Dモデリング
  ├── Mirror Modifier（左右対称）
  ├── Subdivision Surface（滑らか化）
  └── プロペラデザイン
→ STLエクスポート
→ 3Dプリンター出力（48mmカプセル内に収まるサイズ調整）
→ 塗装・仕上げ
→ ジオ展で販売（50円〜100円/個）
```

#### 制作機体実績（drone_gacha / dronegacha リポジトリ）
- Aerosense Aerobo
- SenseFly eBeeX
- Parrot Anafi
- Skydio 2
- Sony Airpeak
- DJI 各モデル
- カスタムトイドローン

---

## 横瀬川河川調査（2022年）

- **プロジェクト名**: yokozeriver2022
- **場所**: 埼玉県横瀬町
- **目的**: UAVによるSfM点群とオルソ画像を使った河川測量
- **成果**: 河川地形の3Dデータ化、GIS分析への活用

---

## 伊豆大島での廃林・ドローン調査

- **目的**: 廃棄された森林地帯の現状把握
- **手法**: ドローン空撮 → ODM処理 → 時系列変化分析
- **OSMとの連携**: 調査結果をOSMデータ更新に反映

---

## 主要GitHubリポジトリ（ドローン関連）

| リポジトリ | 内容 |
|---|---|
| drone | ドローンメーカーカタログ、航空法チートシートPDF |
| drone_gacha | Blender製3Dドローンモデル（ガチャ用）|
| dronegacha | 3Dドローンモデル（STL形式、複数機種）|
| oam4kusatsu | 草津市空撮 → OAM登録 |
| yokozeriver2022 | 横瀬川UAV測量 |
| drone_UN-EC_OSS4SDG_hachathon2022 | UNVT Portableへのドローン写真統合マニュアル |
| drone1_3dprinting_project | ドローン3Dプリントプロジェクト |
