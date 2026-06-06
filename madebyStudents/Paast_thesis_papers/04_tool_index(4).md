# 04_tool_index.md

- 作成元ZIP：アーカイブ(4).zip
- 対象Markdownファイル数：1164
- 目的：古橋研究室の卒論・ゼミ論で登場するツール、データ基盤、プラットフォームを横断的に検索できるようにする。

このファイルは、個別研究の内容をまとめる `01_all_research_summaries.md` ではなく、**ツール・データ・プラットフォーム起点で研究を探すための索引**である。

---

## 使い方

- 「QGISを使った研究は？」のように、ツール名から関連研究を探す。
- 「防災×Minecraft×PLATEAU」のように、複数ツールの組み合わせから研究を比較する。
- 古橋くんGPTには、ツールの正式名称だけでなく、略称・関連語も含めて質問するとよい。

---

## ツール出現数ランキング

|順位|ツール / データ基盤|出現ファイル数|
|---:|---|---:|
|1|GitHub|1159|
|2|JavaScript / HTML / CSS|227|
|3|Medium|199|
|4|OpenStreetMap / OSM|119|
|5|ドローン / UAV|92|
|6|QGIS|92|
|7|Python|84|
|8|Google Sheets / Spreadsheet|74|
|9|Zoom|59|
|10|PLATEAU / CityGML|55|
|11|Mapbox|52|
|12|Google Earth / Google Earth Pro|51|
|13|Blender|30|
|14|Google Maps / My Maps|27|
|15|ChatGPT|25|
|16|JOSM|20|
|17|Strava|19|
|18|3Dプリンター / デジタルファブリケーション|19|
|19|Glide|17|
|20|GPX|15|
|21|LocalWiki|14|
|22|PowerPoint|13|
|23|MapLibre GL JS|13|
|24|Notion|13|
|25|ArcGIS|13|
|26|LiDAR|12|
|27|Mapillary|11|
|28|Canva|10|
|29|iMovie|9|
|30|UNVT|9|
|31|Raspberry Pi|9|
|32|Microsoft Excel|9|
|33|Docker|9|
|34|iD Editor|8|
|35|CloudCompare|8|
|36|Sketchfab|8|
|37|Google Forms|8|
|38|Scaniverse|6|
|39|Re:Earth|6|
|40|Midjourney / 画像生成AI|5|

---

## カテゴリ別ツール索引

## GIS・地図編集

### OpenStreetMap / OSM

- 出現ファイル数：119
- 役割：参加型地図データベース。店舗・建物・トイレ・道路・アクセシビリティなどを地理空間オープンデータとして整備する基盤。
- 代表的な使われ方：
  - 店舗・施設・建物・トイレ・道路などのオープンデータ整備
  - JOSMやiD Editor、Wheelmapなど周辺ツールとの連携
  - 研究成果を再利用可能な地図データとして公開
- 関連リポジトリ例：
  - `2018gsc_YunaWatanabe.md`：2018gsc_YunaWatanabe
  - `2019gsc_Atsuko-Nakanishi.md`：2019gsc_Atsuko-Nakanishi
  - `2019gsc_HinakoHori.md`：2019gsc_HinakoHori
  - `2020gsc_AtsukoWakamatsu.md`：2020gsc_AtsukoWakamatsu
  - `2020gsc_shunsuke-yoda.md`：2020gsc_shunsuke-yoda
  - `2021gsc_AtsukoWakamatsu.md`：2021gsc_AtsukoWakamatsu
  - `2021gsc_ShogoHirasawa.md`：2021gsc_ShogoHirasawa
  - `2022gsc_MOTOYA-KAWANO.md`：2022gsc_MOTOYA-KAWANO
  - `2022gsc_SotaSuzuki.md`：2022gsc_SotaSuzuki
  - `2023gsc_WataruYoshida.md`：2023gsc_WataruYoshida
  - `2024gsc_YukariHayashi.md`：2024gsc_YukariHayashi
  - `2025gsc_InadaYuka.md`：2025gsc_InadaYuka
  - `2025gsc_MIKUHAYASHI.md`：2025gsc_MIKUHAYASHI
  - `README.md`：Source
  - `NEWS.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### QGIS

- 出現ファイル数：92
- 役割：デスクトップGIS。GPX、道路、勾配、Wi-Fiカバー率、滑走ログなどの空間分析・可視化に使用。
- 代表的な使われ方：
  - GPXや道路ネットワークの空間分析
  - 地図・図表作成、バッファ・クリップ・集計
  - 研究結果の可視化と比較
- 関連リポジトリ例：
  - `2019gsc_RyuichiAnbo.md`：2019gsc_RyuichiAnbo
  - `2024GSC_SatoAki.md`：2024GSC_SatoAki
  - `2025gsc_MIKUHAYASHI.md`：2025gsc_MIKUHAYASHI
  - `2025gsc_MIKUHAYASHI2.md`：2025gsc_MIKUHAYASHI
  - `NEWS.md`：Source
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### JOSM

- 出現ファイル数：20
- 役割：OSM編集用の高機能エディタ。大量の建物入力や妥当性検証、PLATEAUインポート準備で重要。
- 代表的な使われ方：
  - 研究内での道具・データ基盤として登場
  - 他ツールと組み合わせて成果物作成に利用
  - 関連研究の検索キーとして有効
- 関連リポジトリ例：
  - `2019gsc_HinakoHori.md`：2019gsc_HinakoHori
  - `2022gsc_WataruYoshida.md`：2022gsc_WataruYoshida
  - `2023gsc_WataruYoshida.md`：2023gsc_WataruYoshida
  - `README.md`：Source
  - `JOSM__styles__README.md`：Source
  - `JOSM__sessions__README.md`：Source
  - `JOSM__README.md`：Source
  - `JOSM__scripts__combine-highways__README.md`：Source
  - `materials__license.md`：Source
  - `materials__26__26.md`：Source
  - `app__assets__sources__MissingMaps_validation_josm_en.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### iD Editor

- 出現ファイル数：8
- 役割：ブラウザ上で使えるOSM編集ツール。初心者向け編集やJOSMとの比較対象として登場。
- 代表的な使われ方：
  - 初心者向けOSM編集
  - JOSMとの操作比較
  - ブラウザだけでの地図編集
- 関連リポジトリ例：
  - `2019gsc_HinakoHori.md`：2019gsc_HinakoHori
  - `HowToUseThisData.md`：Source
  - `README.md`：Source
  - `CONTRIBUTING.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### ArcGIS

- 出現ファイル数：13
- 役割：GISプラットフォーム。QGISやMapboxとの比較、既存GIS環境の参照として出現。
- 代表的な使われ方：
  - 既存GISとの比較・参照
  - GIS学習や分析環境の候補
  - QGIS/Mapboxとの使い分け検討
- 関連リポジトリ例：
  - `2021gsc_TatsumiBaba.md`：2021gsc_TatsumiBaba
  - `2025gsc_FukaOkamura.md`：2025gsc_FukaOkamura
  - `README.md`：Source
  - `NEWS.md`：Source
  - `materials__high_school__webmap.md`：Source
  - `materials__web_gis__README.md`：Source
  - `SUMMARY.md`：Source
  - `materials__high_school__README.md`：Source
  - `materials__web_gis__arcgisapi4js__arcgisapi4js.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Wheelmap

- 出現ファイル数：4
- 役割：OSMを基盤とした車椅子アクセシビリティ可視化サービス。バリアフリーマッピング研究で使用。
- 代表的な使われ方：
  - 施設の車椅子可否評価
  - OSM上のアクセシビリティ情報の可視化
  - 点情報中心の限界を検討
- 関連リポジトリ例：
  - `2025gsc_RenseiInoue.md`：2025gsc_RenseiInoue
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

## Web地図・可視化

### Mapbox

- 出現ファイル数：52
- 役割：Web地図・3D地図・スタイル設計に使われる地図サービス。キャンパス地図、サウンドマップ、季節地図などで登場。
- 代表的な使われ方：
  - 3D地図・キャンパスマップ・サウンドマップなどのWeb地図表示
  - 地図スタイルのデザイン
  - Mapbox GL JSを使ったインタラクティブ表現
- 関連リポジトリ例：
  - `2019gsc_KotaHamada.md`：2019gsc_KotaHamada
  - `2020gsc_YukaSaito.md`：2020gsc_YukaSaito
  - `2021gsc_Kohki_Kikuchi.md`：2021gsc_Kohki_Kikuchi
  - `2021gsc_KuniharuHigano.md`：2021gsc_KuniharuHigano
  - `2022gsc_Kohki_Kikuchi.md`：2022gsc_Kohki_Kikuchi
  - `2023gsc_ShioriUehara.md`：2023gsc_ShioriUehara
  - `2024gsc_ShioriUehara.md`：2024gsc_ShioriUehara
  - `2025gsc_MoeAnjo.md`：2025gsc_MoeAnjo
  - `README.md`：Source
  - `NEWS.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### MapLibre GL JS

- 出現ファイル数：13
- 役割：オープンソースのWeb地図描画ライブラリ。Mapbox GL JS系の実装や観光マップで利用。
- 代表的な使われ方：
  - MapLibreを使ったWebマップ実装
  - OSMタイルやGeoJSONの表示
  - 動画・観光・地域情報との組み合わせ
- 関連リポジトリ例：
  - `2021gsc_Kohki_Kikuchi.md`：2021gsc_Kohki_Kikuchi
  - `2021gsc_ShogoHirasawa.md`：2021gsc_ShogoHirasawa
  - `2021gsc_ShogoHirasawa2.md`：2021gsc_ShogoHirasawa
  - `2022gsc_Kohki_Kikuchi.md`：2022gsc_Kohki_Kikuchi
  - `2025gsc_ShotaArakawa.md`：2025gsc_ShotaArakawa
  - `README.md`：Source
  - `docs__chronologicaltable.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Google Maps / My Maps

- 出現ファイル数：27
- 役割：一般利用者向けの地図・マイマップ作成・ルート案内。店舗分布や観光マップ、行動導線に使用。
- 代表的な使われ方：
  - 一般ユーザー向けの地図公開
  - 店舗分布・観光・ルート案内
  - Google Mapsへの導線連携
- 関連リポジトリ例：
  - `2019gsc_KotaHamada.md`：2019gsc_KotaHamada
  - `2021gsc_YunaHomma.md`：2021gsc_YunaHomma
  - `2025gsc_InadaYuka.md`：2025gsc_InadaYuka
  - `2025gsc_MiaKozaki.md`：2025gsc_MiaKozaki
  - `demos__interactive-classifier__README.md`：Source
  - `demos__cloud-functions__README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Google Earth / Google Earth Pro

- 出現ファイル数：51
- 役割：3D地球儀型の可視化ツール。歴史資料、逃走経路、知覧飛行場、現地調査ストーリーの可視化に使用。
- 代表的な使われ方：
  - ストーリーテリング型の空間可視化
  - 歴史航空写真や経路の重ね合わせ
  - 現地調査とデジタル地図の照合
- 関連リポジトリ例：
  - `2019gsc_ShuntaNakanishi.md`：2019gsc_ShuntaNakanishi
  - `2020gsc_ShuntaNakanishi.md`：2020gsc_ShuntaNakanishi
  - `2020gsc_SuzukaYoshida.md`：2020gsc_SuzukaYoshida
  - `2021gsc_Suzuka-Yoshida.md`：2021gsc_Suzuka-Yoshida
  - `2024AGU-KounaFukuda.md`：2024AGU-KounaFukuda
  - `2025gsc_MayuKanazawa.md`：2025gsc_MayuKanazawa
  - `2025gsc_MayuKanazawa2.md`：2025gsc_MayuKanazawa
  - `README.md`：Source
  - `demos__server-auth-python__README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Re:Earth

- 出現ファイル数：6
- 役割：地理情報のWeb可視化プラットフォーム。災害アーカイブなどのストーリー型可視化に利用。
- 代表的な使われ方：
  - 災害アーカイブや地域記録の可視化
  - GeoJSONやCSVのインポート
  - ストーリー性のある地理情報公開
- 関連リポジトリ例：
  - `2025gsc_ChisatoFuruuchi.md`：2025gsc_ChisatoFuruuchi
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### UNVT

- 出現ファイル数：9
- 役割：国連ベクトルタイルツールキット。オフライン地図サーバーや災害対応GISで利用。
- 代表的な使われ方：
  - オフラインWeb地図サーバー構築
  - ベクトルタイルの生成・配信
  - 災害時の地図利用バックアップ
- 関連リポジトリ例：
  - `2021gsc_ShogoHirasawa.md`：2021gsc_ShogoHirasawa
  - `2021gsc_ShogoHirasawa2.md`：2021gsc_ShogoHirasawa
  - `README.md`：Source
  - `docs__chronologicaltable.md`：Source
  - `README_02.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Tippecanoe

- 出現ファイル数：4
- 役割：ベクトルタイル生成ツール。UNVT Portableなどのオフライン地図生成で登場。
- 代表的な使われ方：
  - ベクトルタイル生成
  - オフラインWeb地図のデータ作成
  - UNVT周辺ツール
- 関連リポジトリ例：
  - `2021gsc_ShogoHirasawa.md`：2021gsc_ShogoHirasawa
  - `README.md`：Source
  - `docs__chronologicaltable.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

## 3D・点群・都市モデル

### PLATEAU / CityGML

- 出現ファイル数：55
- 役割：国土交通省の3D都市モデル・CityGMLデータ。3D建物、OSMインポート、Minecraft、防災、AR表現などの基盤。
- 代表的な使われ方：
  - 3D都市モデルの取得・変換・活用
  - OSMインポート、Minecraft、Blender、AR表現への展開
  - 都市・建物・防災・教育研究の基盤データ
- 関連リポジトリ例：
  - `2020gsc_YosukeKanda.md`：2020gsc_YosukeKanda
  - `2021gsc_IbukiShibayama.md`：2021gsc_IbukiShibayama
  - `kentoukai03__20211129_τ¼¼3σ¢₧µñ£Φ¿ÄΣ╝ÜΦ¡░Σ║ïΘî▓.md`：Source
  - `2022gsc_IbukiShibayama.md`：2022gsc_IbukiShibayama
  - `2022gsc_NatsumiHaga.md`：2022gsc_NatsumiHaga
  - `2023gsc_WataruYoshida.md`：2023gsc_WataruYoshida
  - `2024gsc_Kentaro-Takai.md`：2024gsc_Kentaro-Takai
  - `2024GSC_SatoAki.md`：2024GSC_SatoAki
  - `2025gsc_Kentaro-Takai.md`：2025gsc_Kentaro-Takai
  - `2025gsc_Kentaro-Takai2.md`：2025gsc_Kentaro-Takai
  - `README.md`：Source
  - `NEWS.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Blender

- 出現ファイル数：30
- 役割：3Dモデリングツール。PLATEAU/点群/Scaniverse/Minecraft/AR表現/水族館モデルなどで使用。
- 代表的な使われ方：
  - 点群・CityGML・Scaniverseデータの3Dモデリング
  - 3Dモデルの整形・可視化・レンダリング
  - MinecraftやAR、観光・防災表現への変換
- 関連リポジトリ例：
  - `2020gsc_YosukeKanda.md`：2020gsc_YosukeKanda
  - `2021gsc_IbukiShibayama.md`：2021gsc_IbukiShibayama
  - `2021gsc_UraraNagashima.md`：2021gsc_UraraNagashima
  - `2022gsc_IbukiShibayama.md`：2022gsc_IbukiShibayama
  - `2022gsc_NatsumiHaga.md`：2022gsc_NatsumiHaga
  - `2022gsc_NatsumiHaga2.md`：2022gsc_NatsumiHaga
  - `2022gsc_UraraNagashima.md`：2022gsc_UraraNagashima
  - `2022gsc_UraraNagashima2.md`：2022gsc_UraraNagashima
  - `2024gsc_takizawamihiro-zemireport.md`：2024gsc_takizawamihiro-zemireport
  - `2025gsc_InadaYuka.md`：2025gsc_InadaYuka
  - `README.md`：Source
  - `3Ddata__README.md`：Source
  - `graduationthesis.md`：Source
  - `data__MihiroTakizawa__README.md`：Source
  - `data__TaichiFuruhashi__README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### CloudCompare

- 出現ファイル数：8
- 役割：点群処理ツール。LiDARやScaniverseデータのトリミング・マージ・前処理で登場。
- 代表的な使われ方：
  - 点群の読み込み・マージ・前処理
  - ScaniverseやLiDARデータの検証
  - 3Dモデル化前のデータ整理
- 関連リポジトリ例：
  - `2021gsc_IbukiShibayama.md`：2021gsc_IbukiShibayama
  - `2022gsc_IbukiShibayama.md`：2022gsc_IbukiShibayama
  - `2024gsc_takizawamihiro-zemireport.md`：2024gsc_takizawamihiro-zemireport
  - `README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Scaniverse

- 出現ファイル数：6
- 役割：iPhone LiDAR等を用いた3Dスキャンアプリ。建物内部・水族館などの空間取得に使用。
- 代表的な使われ方：
  - iPhoneによる3Dスキャン
  - 水族館・建物内部の点群取得
  - Blender/CloudCompareへの受け渡し
- 関連リポジトリ例：
  - `2022gsc_IbukiShibayama.md`：2022gsc_IbukiShibayama
  - `2024gsc_takizawamihiro-zemireport.md`：2024gsc_takizawamihiro-zemireport
  - `README.md`：Source
  - `data__TaichiFuruhashi__README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Sketchfab

- 出現ファイル数：8
- 役割：3Dモデル公開プラットフォーム。3D都市モデルの共有・閲覧に使用。
- 代表的な使われ方：
  - 3Dモデルのオンライン公開
  - OBJ等の閲覧・共有
  - 3D成果物のオープン化
- 関連リポジトリ例：
  - `2021gsc_IbukiShibayama.md`：2021gsc_IbukiShibayama
  - `2022gsc_IbukiShibayama.md`：2022gsc_IbukiShibayama
  - `README.md`：Source
  - `graduationthesis.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### LiDAR

- 出現ファイル数：12
- 役割：点群取得技術。ドローンLiDAR、iPhone LiDAR、建物・キャンパス・内部空間の取得に使用。
- 代表的な使われ方：
  - 点群取得
  - 建物や室内空間の3D化
  - ドローン・iPhoneによる測量
- 関連リポジトリ例：
  - `2021gsc_YosukeKanda.md`：2021gsc_YosukeKanda
  - `2021gsc_YosukeKanda2.md`：2021gsc_YosukeKanda
  - `2022gsc_IbukiShibayama.md`：2022gsc_IbukiShibayama
  - `README.md`：Source
  - `graduationthesis.md`：Source
  - `NEWS.md`：Source
  - `kentoukai03__20211129_τ¼¼3σ¢₧µñ£Φ¿ÄΣ╝ÜΦ¡░Σ║ïΘî▓.md`：Source
  - `UserGuide__jp__UserGuide.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### ドローン / UAV

- 出現ファイル数：92
- 役割：空撮・点群取得・オルソ画像生成などに使用。ODMやQGISと組み合わされることが多い。
- 代表的な使われ方：
  - 空撮・測量・点群取得
  - ODM/QGISへの流れ
  - 災害・都市・キャンパス観測
- 関連リポジトリ例：
  - `2019gsc_ReikoMori.md`：2019gsc_ReikoMori
  - `2019gsc_ShuntaNakanishi.md`：2019gsc_ShuntaNakanishi
  - `2020gsc_HironoriMorita.md`：2020gsc_HironoriMorita
  - `2020gsc_KokiSano.md`：2020gsc_KokiSano
  - `2021gsc_IbukiShibayama.md`：2021gsc_IbukiShibayama
  - `2021gsc_ShogoHirasawa.md`：2021gsc_ShogoHirasawa
  - `2022gsc_IbukiShibayama.md`：2022gsc_IbukiShibayama
  - `2022gsc_UraraNagashima.md`：2022gsc_UraraNagashima
  - `2023gsc_Minaho_Ishii.md`：2023gsc_Minaho_Ishii
  - `2023gsc_TaiyuOzawa-.md`：2023gsc_TaiyuOzawa-
  - `README.md`：Source
  - `pressrelease__README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### 3Dプリンター / デジタルファブリケーション

- 出現ファイル数：19
- 役割：地図記号ガチャ、建物模型、地理空間情報の物理化などで使用。
- 代表的な使われ方：
  - 地図・建物・記号を物理化
  - ワークショップ用グッズ制作
  - 空間情報を触れる教材に変換
- 関連リポジトリ例：
  - `2021gsc_TatsumiBaba.md`：2021gsc_TatsumiBaba
  - `2021gsc_TatsumiBaba2.md`：2021gsc_TatsumiBaba
  - `2021gsc_UraraNagashima.md`：2021gsc_UraraNagashima
  - `2022gsc_UraraNagashima.md`：2022gsc_UraraNagashima
  - `2022gsc_UraraNagashima2.md`：2022gsc_UraraNagashima
  - `README.md`：Source
  - `materials__equipment__uav__uav.md`：Source
  - `SUMMARY.md`：Source
  - `materials__equipment__3dprinter__3dprinter.md`：Source
  - `materials__equipment__README.md`：Source
  - `materials__web_gis__gsimap__gsimap.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### OpenDroneMap / ODM

- 出現ファイル数：3
- 役割：ドローン画像からオルソ画像・点群・DSM/DTM等を生成するオープンソース処理環境。
- 代表的な使われ方：
  - ドローン画像から地理空間成果物を生成
  - オルソ画像・点群・DSM/DTM生成
  - QGIS確認やマニュアル化
- 関連リポジトリ例：
  - `2023gsc_Minaho_Ishii.md`：2023gsc_Minaho_Ishii
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

## データ整理・分析

### Google Sheets / Spreadsheet

- 出現ファイル数：74
- 役割：参考文献、データ整理、アンケート集計、タグ一覧、CSV前処理などで多用される表計算基盤。
- 代表的な使われ方：
  - 参考文献リスト管理
  - 調査データ・タグ案・アンケート・集計表の整理
  - CSVや外部ツールへの中間データ作成
- 関連リポジトリ例：
  - `2019gsc_Atsuko-Nakanishi.md`：2019gsc_Atsuko-Nakanishi
  - `2019gsc_HironoriMorita.md`：2019gsc_HironoriMorita
  - `2020gsc_AtsukoWakamatsu.md`：2020gsc_AtsukoWakamatsu
  - `2020gsc_AyakaKawashima.md`：2020gsc_AyakaKawashima
  - `2021gsc_AtsukoWakamatsu.md`：2021gsc_AtsukoWakamatsu
  - `2021gsc_Kahoru-Sato.md`：2021gsc_Kahoru-Sato
  - `2022gsc_HarukaYasuda.md`：2022gsc_HarukaYasuda
  - `2022gsc_HarukaYasuda2.md`：2022gsc_HarukaYasuda
  - `2023gsc_NaoyaUematsu.md`：2023gsc_NaoyaUematsu
  - `2023gsc_ShioriUehara.md`：2023gsc_ShioriUehara
  - `2025gsc_Kentaro-Takai.md`：2025gsc_Kentaro-Takai
  - `2025gsc_MayuKanazawa.md`：2025gsc_MayuKanazawa
  - `README.md`：Source
  - `whitelists__tokorozawacity.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Microsoft Excel

- 出現ファイル数：9
- 役割：データ整理・表作成・手作業での分類や集計に使用。
- 代表的な使われ方：
  - 表形式データの整理
  - 手動分類・集計・比較
  - 研究途中のデータベース作成
- 関連リポジトリ例：
  - `2025gsc_FukaOkamura.md`：2025gsc_FukaOkamura
  - `2025gsc-AkiraMotoyoshi.md`：2025gsc-AkiraMotoyoshi
  - `2025gsc-KounaFukuda.md`：2025gsc-KounaFukuda
  - `README.md`：Source
  - `NEWS.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Google Forms

- 出現ファイル数：8
- 役割：アンケート・理解度テスト・利用者評価の収集に使用。
- 代表的な使われ方：
  - アンケート調査
  - 理解度テストや利用者評価
  - Google Sheetsとの連携集計
- 関連リポジトリ例：
  - `2021gsc_Kahoru-Sato.md`：2021gsc_Kahoru-Sato
  - `2025gsc_Kentaro-Takai.md`：2025gsc_Kentaro-Takai
  - `2025gsc_RikoSueki.md`：2025gsc_RikoSueki
  - `σ╖Ñτ¿ïΦí¿.md`：Source
  - `README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Google Colab

- 出現ファイル数：4
- 役割：Python実行環境。ボクセル生成、地理データ処理、試作コード実行などで使用。
- 代表的な使われ方：
  - Pythonコード実行・共有
  - 地理データ処理の試作
  - Google Drive連携
- 関連リポジトリ例：
  - `2024GSC_SatoAki.md`：2024GSC_SatoAki
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Python

- 出現ファイル数：84
- 役割：空間データ処理、API、分析、QGISスクリプト、ボクセル生成、可視化などで幅広く使用。
- 代表的な使われ方：
  - 地理データ処理・API・分析コードの作成
  - QGISやColab、FastAPIとの連携
  - 自動化・再現性確保
- 関連リポジトリ例：
  - `2024GSC_SatoAki.md`：2024GSC_SatoAki
  - `2024GSC_SatoAki2.md`：2024GSC_SatoAki2
  - `2025gsc_RitoYamasaki.md`：2025gsc_RitoYamasaki
  - `demos__server-auth-python__README.md`：Source
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### FastAPI

- 出現ファイル数：3
- 役割：PythonのWeb APIフレームワーク。ボクセル検索APIなどで使用。
- 代表的な使われ方：
  - ローカル検索APIの構築
  - 3Dボクセルや辞書データの問い合わせ
  - Pythonデータ処理とWeb APIの橋渡し
- 関連リポジトリ例：
  - `2024GSC_SatoAki.md`：2024GSC_SatoAki
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Raspberry Pi

- 出現ファイル数：9
- 役割：小型コンピュータ。オフライン地図サーバーや災害対応システムで使用。
- 代表的な使われ方：
  - 小型オフラインサーバー
  - Wi-Fiアクセスポイント化
  - 災害対応GISの実装基盤
- 関連リポジトリ例：
  - `2021gsc_ShogoHirasawa.md`：2021gsc_ShogoHirasawa
  - `2021gsc_ShogoHirasawa2.md`：2021gsc_ShogoHirasawa
  - `2024GSC_SatoAki.md`：2024GSC_SatoAki
  - `README.md`：Source
  - `docker__README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### GPX

- 出現ファイル数：15
- 役割：GPS軌跡データ形式。Strava、滑走ログ、通学ルート、移動経路分析に使用。
- 代表的な使われ方：
  - GPSログ交換形式としての使用
  - QGISでの軌跡比較・距離計算
  - 滑走・通学・移動ログ研究の中間データ
- 関連リポジトリ例：
  - `2021gsc_KuniharuHigano.md`：2021gsc_KuniharuHigano
  - `2025gsc_MIKUHAYASHI.md`：2025gsc_MIKUHAYASHI
  - `2025gsc_MIKUHAYASHI2.md`：2025gsc_MIKUHAYASHI
  - `2025gsc-AkiraMotoyoshi.md`：2025gsc-AkiraMotoyoshi
  - `graduationthesis.md`：Source
  - `NEWS.md`：Source
  - `README.md`：Source
  - `materials__26__26.md`：Source
  - `materials__web_gis__CZML__CZML.md`：Source
  - `materials__equipment__mobile__mobile.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Strava

- 出現ファイル数：19
- 役割：GPSログ取得アプリ。滑走記録、現地移動、地形データ取得に使用。
- 代表的な使われ方：
  - 歩行・滑走・現地移動ログの取得
  - GPX形式での出力とQGIS連携
  - 実測データに基づくルート・行動分析
- 関連リポジトリ例：
  - `2019gsc_MinoriIizuka.md`：2019gsc_MinoriIizuka
  - `2020gsc-MizutaniHaru.md`：2020gsc-MizutaniHaru
  - `2021gsc_KuniharuHigano.md`：2021gsc_KuniharuHigano
  - `2025gsc_ChisatoFuruuchi.md`：2025gsc_ChisatoFuruuchi
  - `2025gsc_MIKUHAYASHI.md`：2025gsc_MIKUHAYASHI
  - `2025gsc_MIKUHAYASHI2.md`：2025gsc_MIKUHAYASHI
  - `2025gsc-AkiraMotoyoshi.md`：2025gsc-AkiraMotoyoshi
  - `README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### WiGLE

- 出現ファイル数：3
- 役割：Wi-Fiアクセスポイント観測データ。渋谷の歩道Wi-Fiカバー率分析に使用。
- 代表的な使われ方：
  - Wi-Fi APデータ取得
  - 道路カバー率分析
  - PSC手法の再現
- 関連リポジトリ例：
  - `2025gsc_RitoYamasaki.md`：2025gsc_RitoYamasaki
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

## Webアプリ・開発

### JavaScript / HTML / CSS

- 出現ファイル数：227
- 役割：Webマップ、GitHub Pages、インタラクティブ可視化、アプリUIの実装に使用。
- 代表的な使われ方：
  - Webマップ・GitHub Pages・UI実装
  - MapLibre/Mapbox/Next.jsなどのフロント実装
  - 研究成果のWeb公開
- 関連リポジトリ例：
  - `2019gsc_RyuichiAnbo.md`：2019gsc_RyuichiAnbo
  - `2019gsc_ShuntaNakanishi.md`：2019gsc_ShuntaNakanishi
  - `2020gsc_MamiYahiro.md`：2020gsc_MamiYahiro
  - `2020gsc_Rantsuyama.md`：2020gsc_Rantsuyama
  - `2021gsc_Kohki_Kikuchi.md`：2021gsc_Kohki_Kikuchi
  - `2021gsc_ShioriOno.md`：2021gsc_ShioriOno
  - `2023gsc_ShioriUehara.md`：2023gsc_ShioriUehara
  - `2023gsc_WataruYoshida.md`：2023gsc_WataruYoshida
  - `2024GSC_SatoAki2.md`：2024GSC_SatoAki2
  - `2024gsc_ShioriUehara.md`：2024gsc_ShioriUehara
  - `2025gsc_ShotaArakawa.md`：2025gsc_ShotaArakawa
  - `2025__italy__README.md`：Source
  - `README.md`：Source
  - `pressrelease__README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Next.js

- 出現ファイル数：2
- 役割：ReactベースのWebアプリフレームワーク。Spotify連携の音楽散歩地図などで使用。
- 代表的な使われ方：
  - Webアプリのフロント・API統合
  - SpotifyログやSupabaseとの連携
  - プロトタイプから実運用への発展
- 関連リポジトリ例：
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Supabase

- 出現ファイル数：2
- 役割：PostgreSQLベースのBaaS。再生ログや位置情報の保存に使用。
- 代表的な使われ方：
  - 位置ログや再生履歴のDB保存
  - Webアプリのバックエンド
  - 集計APIのデータ基盤
- 関連リポジトリ例：
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Spotify API

- 出現ファイル数：2
- 役割：音楽再生履歴や再生中トラックの取得に使用。
- 代表的な使われ方：
  - 音楽再生履歴の取得
  - 位置情報・気分・天気と組み合わせたログ化
  - 音楽体験の地図化
- 関連リポジトリ例：
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### OpenWeatherMap

- 出現ファイル数：2
- 役割：天気情報API。音楽ログに天気情報を付与するために使用。
- 代表的な使われ方：
  - 地点・時刻ごとの天気情報付与
  - 音楽ログや行動ログへの外部環境データ追加
  - API連携の実例
- 関連リポジトリ例：
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Docker

- 出現ファイル数：9
- 役割：開発環境・処理環境のコンテナ化。ODMや開発環境の説明で登場。
- 代表的な使われ方：
  - 処理環境の再現性確保
  - ODMなどの実行環境
  - コマンドライン作業の基盤
- 関連リポジトリ例：
  - `README.md`：Source
  - `NEWS.md`：Source
  - `docker__README.md`：Source
  - `CHANGES.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

## 発信・記録・教材化

### GitHub

- 出現ファイル数：1159
- 役割：研究成果公開・Markdown本文管理・データ配布・Issue管理・GitHub Pages公開の基盤。
- 代表的な使われ方：
  - 研究本文のMarkdown公開
  - データ・コード・成果物の共有
  - IssueやPagesを使った進捗管理・Web公開
- 関連リポジトリ例：
  - `1999_GraduationThesis_TaichiFuruhashi.md`：1999_GraduationThesis_TaichiFuruhashi
  - `2015__README.md`：Source
  - `2016__README.md`：Source
  - `2016__study-abroad-guideline-01.md`：Source
  - `data__2017__README.md`：Source
  - `2018gsc_NairuNomura.md`：2018gsc_NairuNomura
  - `2018gsc_YunaWatanabe.md`：2018gsc_YunaWatanabe
  - `2019_gsc_yoda.md`：2019-gsc-yoda
  - `2019gsc_Atsuko-Nakanishi.md`：2019gsc_Atsuko-Nakanishi
  - `2020_gurareco.md`：2020_gurareco
  - `2020gsc_AtsukoWakamatsu.md`：2020gsc_AtsukoWakamatsu
  - `2021gsc_AtsukoWakamatsu.md`：2021gsc_AtsukoWakamatsu
  - `2021gsc_IbukiShibayama.md`：2021gsc_IbukiShibayama
  - `2022gsc_HarukaYasuda.md`：2022gsc_HarukaYasuda
  - `2022gsc_HarukaYasuda2.md`：2022gsc_HarukaYasuda
  - `2023gsc_Minaho_Ishii.md`：2023gsc_Minaho_Ishii
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Medium

- 出現ファイル数：199
- 役割：週報・研究発信・最終成果公開・作業記録の投稿先。
- 代表的な使われ方：
  - 研究内での道具・データ基盤として登場
  - 他ツールと組み合わせて成果物作成に利用
  - 関連研究の検索キーとして有効
- 関連リポジトリ例：
  - `2019gsc_HironoriMorita.md`：2019gsc_HironoriMorita
  - `2019gsc_RyuichiAnbo.md`：2019gsc_RyuichiAnbo
  - `2020gsc_HironoriMorita.md`：2020gsc_HironoriMorita
  - `2020gsc_KokiSano.md`：2020gsc_KokiSano
  - `2021gsc_IbukiShibayama.md`：2021gsc_IbukiShibayama
  - `2021gsc_Kohki_Kikuchi.md`：2021gsc_Kohki_Kikuchi
  - `2022gsc_IbukiShibayama.md`：2022gsc_IbukiShibayama
  - `2022gsc_NatsumiHaga.md`：2022gsc_NatsumiHaga
  - `2023gsc_NaoyaUematsu.md`：2023gsc_NaoyaUematsu
  - `2023gsc_TaiyuOzawa-.md`：2023gsc_TaiyuOzawa-
  - `2025GSC-Hinako-Terado.md`：2025GSC-Hinako-Terado
  - `2025gsc-KounaFukuda.md`：2025gsc-KounaFukuda
  - `LICENSE.md`：Source
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Notion

- 出現ファイル数：13
- 役割：知識整理、攻略集、研究メモ、思考プロセスの可視化に使用。
- 代表的な使われ方：
  - 思考プロセスや攻略集の整理
  - 研究メモやデータベース化
  - 公開可能な知識ベース作成
- 関連リポジトリ例：
  - `2021gsc_ShogoHiraswa.md`：2021gsc_ShogoHiraswa
  - `2021gsc_ShogoHiraswa2.md`：2021gsc_ShogoHiraswa
  - `2024AGU-KounaFukuda.md`：2024AGU-KounaFukuda
  - `2025gsc-KounaFukuda.md`：2025gsc-KounaFukuda
  - `README.md`：Source
  - `docs__en__week13__13-1.md`：Source
  - `docs__en__week10__10-1.md`：Source
  - `docs__en__week13__13-2.md`：Source
  - `docs__ar__week13__13-1.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Canva

- 出現ファイル数：10
- 役割：発表スライドや視覚資料作成に使用。
- 代表的な使われ方：
  - 発表資料作成
  - 視覚的に分かりやすいスライド整理
  - 共有しやすいプレゼン資料化
- 関連リポジトリ例：
  - `2021gsc_Kohki_Kikuchi.md`：2021gsc_Kohki_Kikuchi
  - `2024gsc_Tomoki-Fukamizu.md`：2024gsc_Tomoki-Fukamizu
  - `2025gsc_InadaYuka.md`：2025gsc_InadaYuka
  - `2025gsc_MIKUHAYASHI.md`：2025gsc_MIKUHAYASHI
  - `2025gsc_MIKUHAYASHI2.md`：2025gsc_MIKUHAYASHI
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Figma

- 出現ファイル数：2
- 役割：UIデザイン、地図デザイン試作、ロゴ・付箋・階層マップ設計に使用。
- 代表的な使われ方：
  - UI・地図デザイン・ロゴ・印刷物の試作
  - 階層構造や視覚表現の検討
  - Web公開前のデザインモック
- 関連リポジトリ例：
  - `2025gsc-ChihanaUsui.md`：2025gsc-ChihanaUsui
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### PowerPoint

- 出現ファイル数：13
- 役割：発表資料・ポップ・スライド制作に使用。
- 代表的な使われ方：
  - ポップや資料の制作
  - 発表資料作成
  - 手軽な図版・レイアウト制作
- 関連リポジトリ例：
  - `2019gsc_RyuichiAnbo.md`：2019gsc_RyuichiAnbo
  - `2020_gurareco.md`：2020_gurareco
  - `2022gsc_UraraNagashima.md`：2022gsc_UraraNagashima
  - `2022gsc_UraraNagashima2.md`：2022gsc_UraraNagashima
  - `README.md`：Source
  - `materials__web_gis__CZML__CZML.md`：Source
  - `about.md`：Source
  - `command__README.md`：Source
  - `practice_advanced__README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Glide

- 出現ファイル数：17
- 役割：Googleスプレッドシート等を元にノーコードアプリを作成するツール。グラレコ・就活管理などで使用。
- 代表的な使われ方：
  - ノーコードアプリ作成
  - スプレッドシートを元にした教材・管理アプリ
  - 利用者が触れるプロトタイプ作成
- 関連リポジトリ例：
  - `2019gsc_KotaHamada.md`：2019gsc_KotaHamada
  - `2019gsc_RyuichiAnbo.md`：2019gsc_RyuichiAnbo
  - `2020gsc_AyakaKawashima.md`：2020gsc_AyakaKawashima
  - `2021gsc_Kahoru-Sato.md`：2021gsc_Kahoru-Sato
  - `2022gsc_HarukaYasuda.md`：2022gsc_HarukaYasuda
  - `2022gsc_HarukaYasuda2.md`：2022gsc_HarukaYasuda
  - `2024gsc_Tomoki-Fukamizu.md`：2024gsc_Tomoki-Fukamizu
  - `README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### LocalWiki

- 出現ファイル数：14
- 役割：地域情報・質的データのアーカイブ化に使用。
- 代表的な使われ方：
  - 地域情報や質的データのアーカイブ化
  - フィールドノートと位置情報の接続
  - 市民参加型の記録共有
- 関連リポジトリ例：
  - `2020gsc_SuzukaYoshida.md`：2020gsc_SuzukaYoshida
  - `2020gsc_TomokaHayasaki.md`：2020gsc_TomokaHayasaki
  - `2021gsc_MamiYahiro.md`：2021gsc_MamiYahiro
  - `2021gsc_Suzuka-Yoshida.md`：2021gsc_Suzuka-Yoshida
  - `graduate.md`：Source
  - `README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Mapillary

- 出現ファイル数：11
- 役割：ストリートレベル画像共有サービス。フィールドノートやOSM情報補強に使用。
- 代表的な使われ方：
  - 現地写真と地図情報の連携
  - OSM編集の補助資料
  - フィールドワーク記録の公開
- 関連リポジトリ例：
  - `2019gsc_MinoriIizuka.md`：2019gsc_MinoriIizuka
  - `2020gsc_TomokaHayasaki.md`：2020gsc_TomokaHayasaki
  - `2021gsc_YutaKita.md`：2021gsc_YutaKita
  - `graduationthesis.md`：Source
  - `README.md`：Source
  - `kentoukai03__20211129_τ¼¼3σ¢₧µñ£Φ¿ÄΣ╝ÜΦ¡░Σ║ïΘî▓.md`：Source
  - `profile__README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Zoom

- 出現ファイル数：59
- 役割：動画教材制作・遠隔録画・オンライン活動に使用。
- 代表的な使われ方：
  - 遠隔録画・動画教材制作
  - オンライン活動の記録
  - iMovieなどの編集工程と連携
- 関連リポジトリ例：
  - `2018gsc_NairuNomura.md`：2018gsc_NairuNomura
  - `2020gsc_TatsumiBaba.md`：2020gsc_TatsumiBaba
  - `README.md`：Source
  - `NEWS.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### iMovie

- 出現ファイル数：9
- 役割：Zoom録画などの動画編集に使用。
- 代表的な使われ方：
  - 録画動画の編集
  - 教材動画のオープニング・エンディング挿入
  - 低コストな映像制作
- 関連リポジトリ例：
  - `2018gsc_NairuNomura.md`：2018gsc_NairuNomura
  - `2019gsc_NaoYoshida.md`：2019gsc_NaoYoshida
  - `2020gsc_RenAoki-.md`：2020gsc_RenAoki-
  - `2021gsc_Kahoru-Sato.md`：2021gsc_Kahoru-Sato
  - `README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

## AI・生成AI

### ChatGPT

- 出現ファイル数：25
- 役割：文章整理、プロンプト生成、コード補助、テクスチャ生成、研究設計補助として登場。
- 代表的な使われ方：
  - 文章整形・要約・翻訳・コード補助
  - 画像生成プロンプトやテクスチャ作成補助
  - 研究設計や発表資料作成の補助
- 関連リポジトリ例：
  - `2022gsc_Kohki_Kikuchi.md`：2022gsc_Kohki_Kikuchi
  - `2023gsc_TaiyuOzawa-.md`：2023gsc_TaiyuOzawa-
  - `2024gsc_takizawamihiro-zemireport.md`：2024gsc_takizawamihiro-zemireport
  - `2025gsc_Kentaro-Takai.md`：2025gsc_Kentaro-Takai
  - `2025gsc_Kentaro-Takai2.md`：2025gsc_Kentaro-Takai
  - `2025gsc_RitoYamasaki.md`：2025gsc_RitoYamasaki
  - `2025gsc-AkiraMotoyoshi.md`：2025gsc-AkiraMotoyoshi
  - `README.md`：Source
  - `.github__ISSUE_TEMPLATE__chatgpt-code-interpreter-πâòπéÜπâ¡πâ│πâòπéÜπâêπâ¼πé╖πâÆπéÜπâåπâ│πâòπéÜπâ¼πâ╝πâê.md`：Source
  - `sampledata__README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### NotebookLM

- 出現ファイル数：4
- 役割：資料整理・歴史資料やWikipedia起点データの要約・構造化に使用。
- 代表的な使われ方：
  - 大量資料の整理・要約
  - Wikipediaや文献から表形式データを作る補助
  - デジタル再可視化の準備
- 関連リポジトリ例：
  - `2025gsc_MayuKanazawa.md`：2025gsc_MayuKanazawa
  - `2025gsc_MayuKanazawa2.md`：2025gsc_MayuKanazawa
  - `README.md`：Source
  - `01_all_research_summaries.md`：01_all_research_summaries.md
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### Midjourney / 画像生成AI

- 出現ファイル数：5
- 役割：画像生成・ゼミワードリスト・ビジュアル制作に関する研究で使用。
- 代表的な使われ方：
  - 画像生成AIのプロンプト・ワードリスト研究
  - ゼミ活動のビジュアル素材生成
  - 生成結果の安定化・再利用可能な語彙整理
- 関連リポジトリ例：
  - `2023gsc_TaiyuOzawa-.md`：2023gsc_TaiyuOzawa-
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

### GeoGuessr

- 出現ファイル数：2
- 役割：GEOINT的観察力・空間推論の学習対象として扱われるゲーム。
- 代表的な使われ方：
  - 空間推論・GEOINT的観察学習
  - 道路標識・電柱・植生などの判断基準整理
  - 攻略集・知識ベース化
- 関連リポジトリ例：
  - `2025gsc-KounaFukuda.md`：2025gsc-KounaFukuda
  - `README.md`：Source
- 古橋くんGPTでの使い方：このツール名を含む質問では、個別研究だけでなく「どの研究群で、どんな目的で使われたか」を横断的に答える。

---

## 研究タイプ別に見たツールの組み合わせ

### OSMデータ整備型

- 概要：店舗、トイレ、建物、アクセシビリティなどをOSMに登録・修正し、オープンデータ化する研究。
- よく使うツール：OpenStreetMap / OSM, JOSM, iD Editor, Google Sheets / Spreadsheet, GitHub
- 古橋くんGPTへの質問例：
  - 「OSMデータ整備型の研究を、使っているツールと成果物の違いで比較して」

### GIS分析型

- 概要：実測ログや道路データをGISで分析し、ルート・軌跡・カバー率・勾配などを評価する研究。
- よく使うツール：QGIS, GPX, Strava, Python, Google Sheets / Spreadsheet
- 古橋くんGPTへの質問例：
  - 「GIS分析型の研究を、使っているツールと成果物の違いで比較して」

### 3D都市モデル型

- 概要：3D都市モデル・点群・スキャンデータを加工し、建物・都市・室内空間を再現する研究。
- よく使うツール：PLATEAU / CityGML, Blender, CloudCompare, Scaniverse, Sketchfab
- 古橋くんGPTへの質問例：
  - 「3D都市モデル型の研究を、使っているツールと成果物の違いで比較して」

### Web地図アプリ型

- 概要：Web上で地図、動画、音、位置情報、観光情報などを統合して見せる研究。
- よく使うツール：MapLibre GL JS, Mapbox, JavaScript / HTML / CSS, GitHub, Google Maps / My Maps
- 古橋くんGPTへの質問例：
  - 「Web地図アプリ型の研究を、使っているツールと成果物の違いで比較して」

### 防災・災害対応型

- 概要：災害記録、防災教育、避難、オフライン地図などに地理空間技術を応用する研究。
- よく使うツール：Re:Earth, UNVT, Raspberry Pi, PLATEAU / CityGML, Minecraft
- 古橋くんGPTへの質問例：
  - 「防災・災害対応型の研究を、使っているツールと成果物の違いで比較して」

### 教育・技能継承型

- 概要：教材化、マニュアル化、動画化、アプリ化によって技能や知識を継承する研究。
- よく使うツール：Glide, Zoom, iMovie, Medium, GitHub
- 古橋くんGPTへの質問例：
  - 「教育・技能継承型の研究を、使っているツールと成果物の違いで比較して」

### AI活用・知識整理型

- 概要：生成AIや知識整理ツールを使い、プロンプト、画像、歴史資料、攻略知識などを構造化する研究。
- よく使うツール：ChatGPT, NotebookLM, Midjourney / 画像生成AI, Notion, Microsoft Excel
- 古橋くんGPTへの質問例：
  - 「AI活用・知識整理型の研究を、使っているツールと成果物の違いで比較して」

---

## 古橋くんGPTに効く質問例

- QGISを使っている研究を、分析対象・入力データ・出力成果物で分類して。
- PLATEAUを使った研究を、OSMインポート、Minecraft、防災、AR表現の系統に分けて説明して。
- OSMを使った研究の中で、タグ設計やデータ整備に関わるものを一覧化して。
- BlenderやScaniverseなど3D系ツールを使った研究の失敗パターンをまとめて。
- Google EarthやRe:Earthなど、ストーリーテリング型可視化に近い研究を比較して。
- GitHubが単なる提出場所ではなく、研究成果公開・データ公開として機能している例を挙げて。
- ChatGPTやNotebookLMなどAIツールを使った研究を、補助的利用と研究対象としての利用に分けて。
- 防災教育・災害アーカイブ・避難支援に使われているツールを横断的に整理して。

---

## 注意点

- 出現ファイル数はMarkdown本文内でツール名が検出された数であり、実際に主要ツールとして使われた数とは一致しない場合がある。
- `GitHub` や `JavaScript / HTML / CSS` は汎用語として多く出るため、個別研究の中心ツールかどうかは `01_all_research_summaries.md` と合わせて確認する。
- ツール名の表記ゆれにより、完全には拾えていない可能性がある。
- このファイルは、NotebookLMや古橋くんGPTで「ツールから研究を探す」用途に向いている。