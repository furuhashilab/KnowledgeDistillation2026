---
repo_name: "UNVT-Hackathon-Meetup-2022_YouthMappers_AGU"
repo_url: "https://github.com/furuhashilab/UNVT-Hackathon-Meetup-2022_YouthMappers_AGU"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-12-15"
repo_updated_at: "2022-01-25"
distilled_at: "2026-05-25"
language: "HTML"
homepage: null
tags:
  - "UNVT"
  - "YouthMappers"
  - "vector-tile"
confidence: "high"
---

# UNVT-Hackathon-Meetup-2022_YouthMappers_AGU

## 概要
古橋研究室（furuhashilab）が2021年12月に開催した、UN Vector Tile Toolkit（UNVT）をテーマとするハッカソン・ミートアップの成果管理リポジトリである。YouthMappersおよびAGU（American Geophysical Union）と連携した国際的な文脈のもとで実施され、学生チームがベクタータイルの生成・デザイン・配信の一連のワークフローを実践的に習得することを目的としている。発表用スライド、作業キャプチャ、マニュアル作成など、ハッカソン成果物の共同制作もIssueで管理された。

## 主な活動・成果
- ソースデータの取得（OpenAerialMap からの空撮 GeoTIFF ダウンロードを含む）
- QGIS を用いたラスタのベクタ化処理（TIF → GeoJSON）
- tippecanoe による GeoJSON → MBTiles 変換の実施・検証
- tileserver-gl-light を用いたベクタータイルの表示確認
- デザインプロパティの付与（Add design properties）の実践
- 発表用スライドおよびマニュアルの共同作成
- 作業画面キャプチャの収集・共有
- Windows 環境でのトラブル事例の記録（Issue #9）

## 使用技術・ツール
- HTML（リポジトリ主要言語）
- QGIS（ラスタのベクタ化）
- tippecanoe（GeoJSON → MBTiles 変換）
- tileserver-gl-light（ベクタータイル配信・表示）
- OpenAerialMap（空撮 GeoTIFF の取得元）
- UN Vector Tile Toolkit（UNVT）
- OSGeo JP ワークショップ資料（SpeakerDeck スライド参照）

## 得られた知見
- Windows 環境では tippecanoe 等の地理空間ツールが動作しないケースが多く、Linux（Ubuntu）環境の利用が実質的に必須となる。ハッカソンのような時間制約の大きい場面では、事前に参加者の OS 環境を確認し、非 Linux ユーザー向けの代替手段（WSL、VM、クラウドシェル等）を準備しておくことが重要である。
- OpenAerialMap から取得した空撮 TIF をベクタ化して MBTiles に変換するパイプラインは、UNVT ワークフローの典型的な応用例として他プロジェクトでも再利用できる。
- GitHub Issues をハッカソンのタスク管理・トラブルシューティング記録として活用することで、後続学習者への知識継承が容易になる。

## 未解決事項・課題
- 全9件の Issue がオープンのまま残っており、マニュアル作成・発表スライド・作業キャプチャなど複数のタスクが未クローズ。
- Windows 環境での作業課題（Issue #9）は「今後 Ubuntu 等で対策を試みる」とされたまま解決策が確定していない。
- TIF から MBTiles に変換した際の表示上の問題点（Issue #8）についてフィードバックが求められているが、解決の記録が残っていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/UNVT-Hackathon-Meetup-2022_YouthMappers_AGU
- Issues: https://github.com/furuhashilab/UNVT-Hackathon-Meetup-2022_YouthMappers_AGU/issues
