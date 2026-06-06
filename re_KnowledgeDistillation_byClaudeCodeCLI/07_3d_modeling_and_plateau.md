---
title: "3Dモデリング・PLATEAU活用・デジタルツイン"
category: "3d_modeling"
created_date: "2026-06-06"
language: "ja"
tags: ["3D", "PLATEAU", "Blender", "CityGML", "Minecraft", "digital-twin", "3D-printing", "Cesium"]
sources:
  - "madebyStudents/OurBlogs_onMedium/05_gis_tools.md"
  - "madebyStudents/Paast_thesis_papers/02_index_keywords(4).md"
  - "madebyStudents/Paast_thesis_papers/03_cross_theme_analysis(4).md"
  - "madebyStudents/GitHub_Knowledge/design.md"
---

# 3Dモデリング・PLATEAU活用・デジタルツイン

## 3D技術の研究室における位置づけ

古橋研究室では「地理空間情報の3次元表現」が重要な研究軸の一つ。
2D地図では表現できない高度情報・内部構造・体験的視点を3D技術で実現している。

---

## PLATEAU（国土交通省3D都市モデル）

### PLATEAUとは
- **提供元**: 国土交通省
- **内容**: 日本全国の都市を3Dモデル化したオープンデータ
- **形式**: CityGML（国際標準）
- **URL**: https://www.mlit.go.jp/plateau/

### LODレベル（Level of Detail）
| LOD | 内容 | 用途 |
|---|---|---|
| LOD0 | 建物フットプリント（2D） | OSMインポート基礎 |
| LOD1 | 押し出し3D（高さ情報あり） | 都市スカイライン表示 |
| LOD2 | 詳細外観（屋根形状あり） | 詳細可視化 |
| LOD3 | 内部構造含む詳細モデル | VR・建築シミュレーション |

### 研究室でのPLATEAU活用事例

#### 1. OSMへのデータインポート
- PLATEAUの建物フットプリント（LOD0）をOSMに一括インポート
- 大量建物データの効率的なOSM整備を実現

#### 2. Blenderでの3D都市可視化
- CityGMLデータをBlenderにインポート
- マテリアル設定・レンダリングで高品質3D都市画像を生成

#### 3. Minecraftへの変換（防災教育）
- PLATEAUデータ → Minecraftワールド変換
- 防災教育用のゲーム空間として活用
- FOSS4G SHINSHU 2025でデモ発表
- ChatGPTとの組み合わせで学習効果を向上

#### 4. 青山学院大学キャンパスの3Dモデル
- **2021年**: 柴山氏がPLATEAU + Blenderでキャンパスモデル制作
- **2022年**: 継続研究（柴山氏）
- **2024〜2025年**: 高井氏がMinecraftへの変換で継承

---

## Blender活用

### Blenderとは
- 無料・オープンソースの3DCGソフトウェア
- モデリング、アニメーション、レンダリングに対応

### 研究室での主要活用

#### ドローン3Dモデリング（ガチャ制作）
```
実機ドローン → Blenderモデリング → STLエクスポート → 3Dプリント
```
**主要技術**:
- Mirror Modifier（左右対称モデリング）
- Subdivision Surface（表面滑らか化）
- UV展開・テクスチャマッピング

#### 地形可視化
- 等高線データ → 3D地形モデル
- ヒートマップの3D表現

#### 点群データ処理
- ドローン空撮で得た点群データの可視化
- シーンへの組み合わせ

#### Hakone Ekiden 3D可視化
- リポジトリ: hakone-ekiden
- JavaScriptを使ったリアルタイム3Dスポーツ可視化（nagixからフォーク）

---

## 3Dプリント活用

### 研究室でのガチャ商品制作
**ジオ展（Geo Exhibition）**でのガチャマシン設置が恒例行事。

#### 制作プロセス
1. テーマ選定（ドローン、地形、キャラクター等）
2. Blenderでの3Dモデリング
3. STL形式でエクスポート
4. スライシングソフトで印刷設定
5. 3Dプリンター出力
6. 後処理（サポート除去、塗装）
7. 48mmカプセルに格納

#### 主要制作事例
- **ドローンシリーズ**: DJI、Skydio、Sensefly等の機体モデル
- **地形モデル**: 武甲山（横瀬町ハッカソン）のプロトタイプ
- **カメラシリーズ**: GoPro、OSMO等

---

## Cesium（3D地球ビューア）

- **用途**: 大規模3Dジオデータのストーリーテリング
- **特徴**: WebGL使用のブラウザ内3D地球表示
- **研究室での用途**: 地理的ストーリーテリングプロジェクト

---

## デジタルツインの概念

### 研究室が考えるデジタルツイン
> "「現実世界の双子（デジタルコピー）」として都市・地域・施設をデジタル空間に再現し、
> シミュレーション・計画・教育に活用する"

### 主要応用分野
1. **防災教育**: Minecraft上での災害体験シミュレーション
2. **都市計画**: PLATEAU + 可視化ツールでの政策立案支援
3. **キャンパス管理**: 青山学院大学キャンパスの3Dモデル
4. **歴史保存**: 失われた建物・文化遺産の3Dアーカイブ

---

## スキャニング技術

### Scaniverse（スマートフォン3Dスキャン）
- iPhoneのLiDARセンサーを使った3Dスキャンアプリ
- 活用例: 給水タンクの3Dスキャン → デジタルアーカイブ

### LiDAR活用
- 航空機搭載LiDARによる高精度地形データ取得
- 点群データ（LAS/LAZ形式）の処理
- CloudCompare / PDELでのフィルタリング・解析

---

## 主要GitHubリポジトリ（3D・デザイン関連）

| リポジトリ | 内容 |
|---|---|
| fc_SpatialDesign | デザイン基礎（近接・整列・反復・コントラスト）|
| hakone-ekiden | 3Dリアルタイムスポーツ可視化（JS）|
| tokyo-vector-tile | 東京オープンデータベクタータイル（550MB）|
| shikuchoson-hazardmap-template | Leaflet/TypeScriptハザードマップテンプレート |
| logos4gsc2024 | GSC学部ロゴ・ブランドアイデンティティ |
| drone1_3dprinting_project | ドローン3Dプリントプロジェクト |
| drone_gacha | ガチャ用3Dドローンモデル |
| hachathon_3dmodel | ハッカソン3Dモデルガチャ |

---

## 関連学術発表

- FOSS4G SHINSHU 2025（2025年11月29〜30日）: PLATEAU × Minecraft 防災教育デモ
- OpenDroneMap Global Meet-Up UR24（2024年6月）: ODMエコシステムと DRONEBIRD概念発表
- State of the Map 各年: 3D都市情報に関連した発表
