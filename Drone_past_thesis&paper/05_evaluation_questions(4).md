# 05_evaluation_questions.md

- 作成元ZIP：アーカイブ(4).zip
- 目的：古橋くんGPT / NotebookLM / カスタムGPT に、研究室Markdownを正しく読めているか確認するための評価質問集。
- 使い方：質問をそのまま投げ、返答が「期待される答え」に近いか確認する。
- 注意：これは個別研究の本文そのものではなく、**テスト用の質問と正答メモ**である。根拠確認には `01_all_research_summaries.md` と各個人Markdownを参照する。

---

## 0. 評価の見方

### 期待する回答レベル

古橋くんGPTが良い回答をしているかは、次の4点で見る。

1. **該当研究を正しく特定できるか**  
   研究名・年度・著者・リポジトリ名を取り違えない。

2. **目的・方法・成果・課題を分けて答えられるか**  
   ただ要約するだけでなく、何をした研究か、何が成果か、何が限界かを区別する。

3. **横断比較ができるか**  
   OSM系、PLATEAU系、防災系、教育系、観光系など、複数研究をつなげて説明できる。

4. **分からないものを分からないと言えるか**  
   README本文が薄い研究や、PDF本文未変換の研究について、無理に断定しない。

---

## 1. まず投げるならこれ：本命評価質問

### Q001：古橋研究室の卒論・ゼミ論に共通する研究スタイルを、具体例を3つ挙げて説明して。

**狙い**：個別研究ではなく、研究室全体の横断理解を確認する。  
**期待される答え**：

古橋研究室の研究は、地理空間情報やデジタル技術を使って、現場の情報を「使える形」に変換する実践研究が多い。共通する流れは、現場や対象を観察し、データ化し、地図・Webアプリ・3Dモデル・OSM・アーカイブなどに変換し、他者が再利用できる形で公開することである。

具体例として、

- `2018gsc_YunaWatanabe` は、ラーメン二郎40店舗の位置情報とタグ情報をOpenStreetMapに整理し、オープンデータ化した。
- `2021gsc_ShogoHirasawa` は、Raspberry PiとUNVTを使い、災害時にインターネットなしでも使えるオフラインWeb地図サーバーを開発した。
- `2022gsc_IbukiShibayama` は、相模原キャンパスの点群データから3D建物モデルを制作し、GitHubやSketchfabで公開した。

つまり、単なる分析ではなく、**作る・公開する・使えるようにする**ことが研究室の特徴である。

**判定ポイント**：
- 「地理空間情報を社会で使える形にする」という横断軸が出ているか。
- 個別研究を3件以上具体名付きで挙げているか。
- OSM、UNVT、3Dモデルなど異なる系統の例を混ぜられているか。

---

## 2. 個別研究を正しく引けるか：基本問題

### Q002：ラーメン二郎の全国店舗をOSMに整理した研究はどれ？何を成果にした？

**期待される答え**：
`2018gsc_YunaWatanabe`。タイトルは「日本全国のラーメン二郎店舗位置情報オープン化の実践」。2018年時点のラーメン二郎40店舗を対象に、OpenStreetMap上で未登録店舗の追加、位置情報修正、`amenity=fast_food`、`cuisine=ramen;jiro`、`opening_hours`、英語名称などのタグ整理を行い、二次利用可能な地理空間情報オープンデータとして整備した。

---

### Q003：神奈川県内の二郎系ラーメンをOSMに整理した研究は、2018年のラーメン二郎研究と何が違う？

**期待される答え**：
`2021gsc_SotaSuzuki`。2018年の渡邊結南氏の研究が「ラーメン二郎」直系全国40店舗を対象にしたのに対し、鈴木氏の研究は神奈川県内の「二郎系ラーメン」54店舗を対象にした。位置情報だけでなく、住所、営業時間、COVID-19対応営業時間、テイクアウト、デリバリー可否などのメタデータもOSMに整理した。

---

### Q004：JOSMのマッピング方法を初心者向けにマニュアル化した研究はどれ？

**期待される答え**：
`2019gsc_HinakoHori`。タイトルは「OpenStreetMapにおけるJOSMを用いたマッピング法のマニュアル化及び相模原市内の建物データ整備」。JOSMの導入・操作方法を初心者向けに整理し、グラフィックレコーディングを用いて分かりやすくマニュアル化した。相模原市内の建物データ整備も行った。

---

### Q005：オフライン環境で動くWeb地図サーバーを作った研究はどれ？使った主な技術は？

**期待される答え**：
`2021gsc_ShogoHirasawa`。タイトルは「オフライン環境下で動くオープンソース・ウェブ地図サーバー UNVT Portable の開発」。Raspberry Pi、UNVT、OpenStreetMap、OpenAerialMap、Tippecanoe、MapLibre GL JS、Apache2、hostapd、dnsmasqなどを用いて、Wi-Fiアクセスポイント化したオフラインWeb地図サーバーを構築した。

---

### Q006：住居表示住所デジタル化の進捗を調査した研究はどれ？

**期待される答え**：
`2021gsc_RanMatsuyama`。全国1917市町村を対象に、住居表示住所の実施状況、公開情報、フォーマット、公開レベル、国土地理院電子国土基本図への掲載状況を調査し、Googleスプレッドシートやカラム地図で可視化した研究。

---

### Q007：GIGAスクール端末向けに地理系Webサイトのホワイトリストを作った研究はどれ？

**期待される答え**：
`2021gsc_YunaHomma`。GIGAスクール端末で地理空間情報系Webサイトにアクセスできるように、ハザードマップ、自治体GIS、観光マップなどを整理し、47都道府県ごとのGitHub IssueやCSV形式のホワイトリストを作成した。

---

### Q008：レーザー加工機を使って地理空間情報を物体化した研究はどれ？

**期待される答え**：
`2021gsc_TatsumiBaba`。タイトルは「デジタルファブリケーションを用いた地理空間情報表現手法の検討 〜レーザー加工機を例に〜」。FABOOL Laser CO2を使い、渋谷〜原宿周辺や淵野辺〜青山学院大学周辺の地理空間情報をMDF板の栞にレーザー刻印した。

---

### Q009：相模原キャンパスの3D都市モデルを制作した研究はどれ？

**期待される答え**：
`2022gsc_IbukiShibayama`。PLATEAUの整備フローを参考に、ドローンLiDARやiPhone LiDAR、CloudCompare、Blenderを用いて青山学院大学相模原キャンパスの3D建物モデルを制作し、GitHubやSketchfabで公開した。

---

### Q010：ワークショップ用ジオガチャを開発した研究はどれ？

**期待される答え**：
`2022gsc_UraraNagashima`。地図記号を3Dプリントした「地図記号ガチャ」と、青山学院大学マスコットのイーゴくんを証明写真風に加工したガチャを制作した。Blender、FlashForge 3Dプリンター、PowerPointなどを使用した。

---

### Q011：グラレコ技能の継承アプリを改良した研究はどれ？

**期待される答え**：
`2022gsc_HarukaYasuda`。グラフィックレコーディング補助アプリ「おたすけグラレコ vol.2」を改良し、「おたすけグラレコ vol.3」としてアップデートした。Glideを用い、準備・確認・認識齟齬防止などのプロセスを整理した。

---

### Q012：Pokemon GOのGOスナップショットとPLATEAUを組み合わせた研究はどれ？

**期待される答え**：
`2022gsc_NatsumiHaga`。PLATEAU LOD2建物データを用い、渋谷PARCOの建物モデルをキャラクターカラーに変化させることで、Pokemon GOのGOスナップショットにおけるAR表現の拡張を提案した。

---

### Q013：OpenDroneMapの普及やグラレコ化を扱った研究はどれ？

**期待される答え**：
`2023gsc_Minaho_Ishii`。OpenDroneMapの概要と利用方法をグラレコにまとめ、日本での普及を図ること、Wikipediaページの日本語翻訳、課題と今後の展望を考察することを目的とした研究。

---

### Q014：古橋ゼミ公式LINE botを制作した研究はどれ？

**期待される答え**：
`2023gsc_NaoyaUematsu`。LINE Developers、Make、Google Apps Scriptを用いて、質問用古橋botとAI古橋botを制作した。匿名で質問でき、質問を共有できる仕組みを目指した。

---

### Q015：ジャズの地理的拡散をMapbox Storytellingで扱った研究はどれ？

**期待される答え**：
`2023gsc_ShioriUehara`。ニューオーリンズから始まるジャズの拡散や変容を文献調査し、Mapbox Storytellingを使って地理的に可視化した研究。

---

### Q016：PLATEAU LOD1建物データをOSMにインポートした研究はどれ？

**期待される答え**：
`2023gsc_WataruYoshida`。埼玉県新座市を対象に、PLATEAU LOD1建物データをOpenStreetMapにインポートする事前準備と実作業を行った。JOSM、Tasking Manager、citygml-osm、Java環境などを扱い、アカウントブロックなどの運用課題も記録した。

---

### Q017：韓国の道路名住所制度を扱った2024年の研究はどれ？

**期待される答え**：
`2024gsc_RikoSueki`。韓国における住所体系の変化、特に道路名住所制度の導入背景、住民の適応状況、文化的影響、地域間格差、日本への示唆を扱った研究。

---

### Q018：相模原キャンパスの環境音をMapbox上に展開しようとした研究はどれ？

**期待される答え**：
`2024gsc_ShioriUehara`。相模原キャンパスのカフェテリア前、チャペル前、ガーデン、スタジアム前でiPhoneボイスメモにより環境音を録音し、Mapbox GL JSでマーカーと音源リンクを地図に展開した研究。

---

### Q019：スノーボード滑走記録アプリを比較した研究はどれ？結論は？

**期待される答え**：
`2025gsc_MIKUHAYASHI`。Strava、Ski Buddy、Ski Tracks、Slopes、yukiyama、Snoway、YAMAP、ヤマレコなどを比較し、GPXをQGISで重ねて精度を検証した。Ski BuddyとStravaが比較的高精度で、ただし一部ラグも確認された。

---

### Q020：Minecraftで相模原キャンパスB棟を防災教育向けに再現した研究はどれ？

**期待される答え**：
`2025gsc_Kentaro-Takai`。青山学院大学相模原キャンパスB棟をMinecraft上に再現し、非常階段、避難経路、消火器などを視覚的に強調した。体験型ゲームの前後で防災理解度テストを行い、理解度向上を確認した。

---

### Q021：知覧飛行場跡をGoogle NotebookLMとGoogle Earth Proで再可視化した研究はどれ？

**期待される答え**：
`2025gsc_MayuKanazawa`。Wikipedia上の特攻隊員出身地データをGoogle NotebookLMで整理し、Google Earth Proで出身地分布や知覧飛行場跡を再可視化した。米軍航空写真や現地調査も組み合わせた。

---

### Q022：CKANベースのオープンデータポータルを国際比較した研究はどれ？

**期待される答え**：
`2025gsc_FukaOkamura`。CKAN上の地理空間データ形式に着目し、日本の都道府県と海外の国単位で、GeoJSON、SHP、KML、GeoPackage、CSV、PDFなどの提供状況を比較した。

---

### Q023：CLUB BAYSTARS加盟店を地図化した研究はどれ？

**期待される答え**：
`2025gsc_MiaKozaki`。横浜DeNAベイスターズのCLUB BAYSTARS加盟店362件をデジタルデータ化し、Google My Mapsで業種別に可視化した。スポーツと都市回遊性・地域経済の関係を分析した。

---

### Q024：Wheelmapを使って町田駅周辺のアクセシビリティ情報を整備した研究はどれ？

**期待される答え**：
`2025gsc_RenseiInoue`。町田駅周辺の公共トイレ、飲食店、出入り口、駅設備などをWheelmap/OSM上で評価し、評価件数を4件から60件へ増やした。線情報としてのエレベータ表現や当事者検証の必要性も課題として整理した。

---

### Q025：渋谷の歩道Wi-Fiカバー率をQGISで分析した研究はどれ？

**期待される答え**：
`2025gsc_RitoYamasaki`。WiGLEで取得したWi-Fi AP点群、OSM道路、25mグリッドを用い、Potential Street Coverage手法をQGISで再現した。APバッファ半径の感度分析を行い、r=25mを採用した。

---

### Q026：音楽視聴履歴と移動ログを組み合わせたアプリ研究はどれ？

**期待される答え**：
`2025gsc_YudaiKato`。Spotify API、Geolocation、OpenWeatherMap、Supabase、MapLibre、Next.jsを用いて、再生履歴に位置情報・天気・moodを付与し、地図上で振り返る「音楽散歩地図」アプリを作成した。

---

### Q027：横浜駅の高低差表現を含む地図デザインを試作した研究はどれ？

**期待される答え**：
`2025gsc-ChihanaUsui`。横浜駅の複雑な階層構造を対象に、Figmaを使って階層切り替えや透過表示、階段・エスカレーターのグラデーション表現を用いた地図デザインを試作した。

---

### Q028：新百合ヶ丘の歩ける中心軸をSpace Syntaxと勾配で分析した研究はどれ？

**期待される答え**：
`2025GSC-Hinako-Terado`。新百合ヶ丘駅周辺の15分徒歩圏を対象に、Space Syntaxのintegrationと地形勾配を重ね、平均勾配8%以下かつ高integrationの「歩ける中心軸」を延長ベースで評価した。

---

### Q029：GeoGuessr攻略からGEOINTナレッジを整理した研究はどれ？

**期待される答え**：
`2025gsc-KounaFukuda`。GeoGuessrのプレイ記録や上級者動画をもとに、標識、道路、電柱、植生、Google carなどの判断材料をExcelやNotionに整理し、攻略集としてオープン化しようとした研究。

---

## 3. 横断比較問題

### Q030：OSMを使った研究を3つ挙げ、それぞれ何をOSMに入れたか比較して。

**期待される答え**：
例として、

- `2018gsc_YunaWatanabe`：ラーメン二郎40店舗の位置情報・営業時間・料理ジャンルなど。
- `2021gsc_SotaSuzuki`：神奈川県内二郎系ラーメン54店舗の住所、営業時間、COVID-19営業時間、テイクアウト・デリバリー可否など。
- `2023gsc_WataruYoshida`：PLATEAU LOD1建物データを新座市のOSM建物データとしてインポート。
- `2025gsc_RenseiInoue`：町田駅周辺のアクセシビリティ情報をWheelmap/OSMで整備。
- `2025gsc_YukariHayashi`：駅構内多機能トイレ情報とOSMタグ提案。

答えでは、OSMが「研究成果の公開先」かつ「再利用可能な地理空間データ基盤」として使われている点を説明できるとよい。

---

### Q031：PLATEAUを使った研究を複数挙げて、使い方の違いを説明して。

**期待される答え**：

- `2022gsc_IbukiShibayama`：相模原キャンパスの3D建物モデル制作の文脈でPLATEAU整備フローを参考にした。
- `2022gsc_NatsumiHaga`：PLATEAU LOD2建物データをPokemon GO風AR表現に応用した。
- `2023gsc_WataruYoshida`：PLATEAU LOD1建物データをOSMにインポートした。
- `2024gsc_Kentaro-Takai` / `2025gsc_Kentaro-Takai`：Minecraft再現の初期方針としてPLATEAU利用を検討したが、最終的には手作業再現に転換した。

PLATEAUは、3D都市モデル制作、AR表現、OSMインポート、ゲーム空間再現の試行など、用途が多様である。

---

### Q032：防災・災害対応に関係する研究を4つ挙げて、それぞれのアプローチを比較して。

**期待される答え**：

- `2021gsc_ShogoHirasawa`：災害時にインターネットなしで使えるオフラインWeb地図サーバーUNVT Portableを開発。
- `2025gsc_Kentaro-Takai`：Minecraftで相模原キャンパスB棟を再現し、防災設備の位置理解を促進。
- `2025gsc_ChisatoFuruuchi`：Re:Earthで楢葉町の震災記録を空間的に可視化する災害アーカイブを構築。
- `2025gsc_InadaYuka`：横浜駅周辺の混雑・危険エリアをBlenderや衛星データ、ハザードマップで立体的に把握。
- `2025gsc-AkiraMotoyoshi`：通学ルートにおける信号待ち・安全性を含めた実測歩行ルート最適化。

防災研究でも、地図サーバー、ゲーム教材、災害アーカイブ、3D可視化、ルート分析などアプローチが異なる。

---

### Q033：教育・教材化に関係する研究を3つ挙げて、何を教材化したか説明して。

**期待される答え**：

- `2018gsc_NairuNomura`：ZoomとiMovieを用いた映像教育教材作成手法。
- `2019gsc_HinakoHori`：JOSMを使ったOSMマッピング方法を初心者向けマニュアル化。
- `2022gsc_HarukaYasuda`：グラフィックレコーディング技能を継承する「おたすけグラレコ」アプリ。
- `2025gsc_Kentaro-Takai`：Minecraftを用いた防災教育教材。

共通点は、専門的・経験的な知識を他者が学べる形式に変換していること。

---

### Q034：観光・地域回遊に関係する研究を3つ挙げて、どのように地図化しているか比較して。

**期待される答え**：

- `2025gsc_ShotaArakawa`：行田市の観光スポットをMapLibre GL JSで動画連携型Webマップ化。
- `2025gsc_MiaKozaki`：横浜DeNAベイスターズのCLUB BAYSTARS加盟店をGoogle My Mapsで可視化。
- `2025gsc_MoeAnjo`：隅田川・隅田公園周辺を対象に、Mapbox Studioで春夏秋冬の地図デザインを作成。
- `2025gsc_MayuKanazawa`：知覧飛行場跡をGoogle Earth Proで歴史的ストーリーテリング化。

観光・地域回遊研究では、単なる位置表示だけでなく、動画、季節感、スポーツファンの回遊、歴史記憶などを地図に重ねている。

---

### Q035：3D・点群・Minecraft・Blender系の研究をまとめて。

**期待される答え**：

- `2022gsc_IbukiShibayama`：点群データとBlenderで相模原キャンパス3Dモデルを制作。
- `2024GSC_SatoAki`：標高データから3Dボクセルを生成し、FastAPIで検索APIを作成。
- `2024gsc_takizawamihiro-zemireport`：Scaniverse、CloudCompare、Blenderで水族館の3Dデータ処理を試行。
- `2025gsc_InadaYuka`：Blenderで横浜駅周辺の混雑・危険エリアを立体的に把握。
- `2025gsc_Kentaro-Takai`：MinecraftでB棟内部空間を再現し、防災教育に活用。

共通点は、2D地図では分かりにくい高さ・内部空間・立体構造を可視化すること。

---

### Q036：住所・場所の伝え方に関係する研究を比較して。

**期待される答え**：

- `2021gsc_RanMatsuyama`：日本の住居表示住所デジタル化の進捗を全国自治体で調査。
- `2024gsc_RikoSueki`：韓国の道路名住所制度の導入背景と課題を整理。
- `2025gsc_RikoSueki`：若年層の日韓比較から、住所が「覚える情報」ではなく「検索・共有するデータ」になっていることを調査。

住所研究は、制度・データ整備・若者の実利用という3段階で展開している。

---

### Q037：移動ログ・行動記録を扱う研究を3つ挙げて。

**期待される答え**：

- `2025gsc_MIKUHAYASHI`：スノーボード滑走ログをGPXとして取得し、QGISで比較。
- `2025gsc-AkiraMotoyoshi`：通学ルートをStravaで実測し、セクション別に分析。
- `2025gsc_YudaiKato`：Spotify再生履歴に位置情報・天気・moodを付与し、音楽散歩地図を作成。
- `2025gsc_RitoYamasaki`：WiGLE歩行ログ由来のWi-Fi APデータを歩道カバー率分析に利用。

移動ログ系は、実測データをもとに、地図上で行動を振り返る・比較する点が共通する。

---

### Q038：AI・生成AIを使った研究をいくつか挙げて。

**期待される答え**：

- `2023gsc_TaiyuOzawa-`：MidjourneyとChatGPTを用いたゼミワードリスト構築。
- `2025gsc_MayuKanazawa`：Google NotebookLMでWikipedia起点のデータ整理。
- `2025gsc_YudaiKato`：GPT-5.1/5.2 Codexを用いたバイブコーディングでアプリ実装。
- `2025gsc_Kentaro-Takai`：ChatGPTで防災設備テクスチャを生成。
- `2025gsc-KounaFukuda`：GeoGuessr攻略情報をNotion・Excelに整理し、GEOINT知識化。

AIは、画像生成、データ整理、コード生成、教材・表現素材制作などに使われている。

---

### Q039：研究室の「オープン化」のパターンを説明して。

**期待される答え**：
古橋研究室では、成果物を閉じたレポートで終わらせず、GitHub、OpenStreetMap、LocalWiki、Sketchfab、Google Sheets、Re:Earth、Webアプリなどで公開・再利用可能にする研究が多い。例として、ラーメン二郎OSM、二郎系OSM、相模原キャンパス3Dモデル、LocalWikiによる質的データアーカイブ、CKANポータル比較、災害アーカイブなどがある。

---

### Q040：研究室の中で「失敗や制約」を成果として残している研究を挙げて。

**期待される答え**：

- `2023gsc_WataruYoshida`：PLATEAUインポート時のJavaバージョン、OSMアカウントブロック、アップロード制限などの問題を記録。
- `2024gsc_takizawamihiro-zemireport`：ScaniverseのPLYがCloudCompareで読めない、転送で壊れる、Blenderが重いなどの課題を整理。
- `2024gsc_ShioriUehara`：Mapbox Standardの3D表現が想定通り反映されず、2D的表示になった課題を記録。
- `2025gsc_Kentaro-Takai`：PLATEAUからMinecraftへの直接変換が難しく、手作業再現へ転換した。
- `2025gsc_MIKUHAYASHI`：アプリごとのGPX出力可否やラグ発生を記録。

失敗を隠さず、次の研究の判断材料として残している点が特徴。

---

## 4. ツール逆引き問題

### Q041：QGISが出てくる研究を3つ挙げて、それぞれ何に使われた？

**期待される答え**：

- `2025gsc_MIKUHAYASHI`：滑走記録アプリのGPX軌跡を比較。
- `2025gsc_RitoYamasaki`：Wi-Fi APバッファとOSM道路の交差長、25mグリッドのcoverage ratio、ECDF計算。
- `2025GSC-Hinako-Terado`：Space Syntax指標と勾配データを重ね、歩ける中心軸を分析。
- `2025gsc-AkiraMotoyoshi`：通学ルートの距離計測、街灯密度分析、地図作成。

---

### Q042：Blenderが出てくる研究を3つ挙げて。

**期待される答え**：

- `2022gsc_IbukiShibayama`：相模原キャンパス3D建物モデルの手動調整。
- `2022gsc_NatsumiHaga`：PLATEAU建物モデルにキャラクターカラーを着色。
- `2024gsc_takizawamihiro-zemireport`：Scaniverseデータの取り込み・処理の代替手段。
- `2025gsc_InadaYuka`：横浜駅周辺の混雑・危険エリアを3D地図と重ねて考察。

---

### Q043：MapboxまたはMapLibreを使った研究を挙げて。

**期待される答え**：

- `2023gsc_ShioriUehara`：Mapbox Storytellingでジャズの地理的拡散を可視化。
- `2024gsc_ShioriUehara`：Mapbox GL JSで相模原キャンパスのサウンドマップを作成。
- `2025gsc_MoeAnjo`：Mapbox Studioで四季を感じる地図デザインを作成。
- `2025gsc_ShotaArakawa`：MapLibre GL JSで行田市の動画連携型観光Webマップを構築。
- `2025gsc_YudaiKato`：MapLibreで音楽視聴ログを地図上に可視化。

---

### Q044：Google Earth Proが使われた研究を挙げて。

**期待される答え**：

- `2024AGU-KounaFukuda`：平野龍磨脱獄事件の逃走経路をGoogle Earth上にマッピング。
- `2025gsc_MayuKanazawa`：知覧飛行場跡や特攻隊員出身地をGoogle Earth Proで再可視化。
- `2025gsc-ChihanaUsui`：横浜駅の現状分析や高低差確認でGoogle Earthや既存地図を参照。

---

### Q045：Glideを使った研究は？

**期待される答え**：

- `2022gsc_HarukaYasuda`：グラレコ補助アプリ「おたすけグラレコ vol.3」を制作。
- `2024gsc_Tomoki-Fukamizu`：就活管理アプリをGlideで作成。

---

### Q046：Stravaを使った研究は？

**期待される答え**：

- `2025gsc-AkiraMotoyoshi`：淵野辺駅北口から青学相模原キャンパスまでの通学歩行ログを取得。
- `2025gsc_ChisatoFuruuchi`：楢葉町現地調査で地形・移動経路データを取得し、GeoJSON化してRe:Earthに反映。
- `2025gsc_MIKUHAYASHI`：滑走記録比較の基準アプリとして使用。

---

### Q047：Re:Earthを使った研究は？

**期待される答え**：
`2025gsc_ChisatoFuruuchi`。福島県楢葉町を対象に、東日本大震災と福島第一原発事故の記録をRe:Earth Visualizerで空間的に可視化する災害アーカイブを構築した。

---

### Q048：NotebookLMを使った研究は？

**期待される答え**：
`2025gsc_MayuKanazawa`。Wikipedia上の特攻隊員出身地データをGoogle NotebookLMで整理し、CSV化してGoogle Earth Proに取り込んだ。

---

### Q049：FastAPIが使われた研究は？

**期待される答え**：
`2024GSC_SatoAki`。標高データから生成した3DボクセルにハッシュIDを付与し、FastAPIでボクセル検索APIを構築した。

---

### Q050：Supabaseが使われた研究は？

**期待される答え**：
`2025gsc_YudaiKato`。Spotify再生履歴、位置情報、mood、天気情報を保存するDBとしてSupabaseを使った。

---

## 5. 回答不能・注意確認問題

### Q051：`sotsuron2022` の研究目的と結果を詳しく説明して。

**期待される答え**：
`sotsuron2022` は個別研究ではなく、2022年度の卒論・ゼミ論をまとめる年度別管理リポジトリである。READMEには個別研究のAbstract、Methods、Resultsなどは含まれていないため、研究目的や結果を詳しく説明することはできない。個別研究の詳細は各学生のリポジトリを参照する必要がある。

**判定ポイント**：無理に架空の研究内容を作らないこと。

---

### Q052：`2022gsc_TaiyuOzawa` の具体的な研究方法を詳しく説明して。

**期待される答え**：
README上では「別次元におけるコミュニケーション変化について」というテーマ名は確認できるが、Abstract、Methods、Resultsなどの詳細本文は不足している。そのため、具体的な研究方法はGitHub上のREADMEだけでは断定できない。

---

### Q053：`1999_GraduationThesis_TaichiFuruhashi` の詳細な分析手法を説明して。

**期待される答え**：
リポジトリは古橋大地氏の1999年卒業論文「衛星・標高・気象データを用いた，富士山における植物・積雪分布の季節変化について」を扱うが、Markdown本文は十分に整備されておらず、詳細はPDF本文を確認する必要がある。Markdownだけから詳細な分析手法を断定するのは避けるべき。

---

### Q054：`2024gsc_MayuKanazawa` の研究内容を詳しく教えて。

**期待される答え**：
READMEにはリポジトリ名と簡単な説明程度しかなく、研究本文がほぼ確認できないため、詳細な研究内容は断定できない。2025年度の`2025gsc_MayuKanazawa`とは別物として扱う必要がある。

---

### Q055：同姓同名・似たリポジトリがあるとき、どう注意すべき？

**期待される答え**：
同じ著者・似たテーマで年度違いの研究があるため、年度とリポジトリ名を確認する必要がある。例として、Riko Suekiは2024年に韓国の道路名住所制度、2025年に若年層の日韓住所利用比較を扱っている。Yukari Hayashiは2024年に駅トイレ調査のゼミ論、2025年に多機能トイレ設置状況の卒論を扱っている。Kentaro Takaiは2024年に相模原キャンパスMinecraft再現の初期案、2025年にB棟防災活用の卒論を扱っている。

---

## 6. 古橋くんGPTに効く実践質問

### Q056：古橋研究室で「地図を作る」研究と「地図を使って分析する」研究を分けて説明して。

**期待される答え**：

「地図を作る」研究：
- `2018gsc_YunaWatanabe`：ラーメン二郎OSMデータ整備。
- `2025gsc_ShotaArakawa`：行田市観光Webマップ作成。
- `2025gsc_MoeAnjo`：四季を感じる地図デザイン作成。
- `2025gsc_YudaiKato`：音楽散歩地図アプリ作成。

「地図を使って分析する」研究：
- `2025gsc_RitoYamasaki`：Wi-Fiカバー率を道路・グリッドで分析。
- `2025GSC-Hinako-Terado`：Space Syntaxと勾配で歩ける中心軸を分析。
- `2025gsc_MIKUHAYASHI`：滑走ログをQGISで比較分析。
- `2025gsc-AkiraMotoyoshi`：通学ルートを実測データで分析。

---

### Q057：研究室内で「体験をデータ化する」研究を挙げて。

**期待される答え**：

- `2020gsc_TomokaHayasaki`：タイでのフィールドノートをLocalWikiとMapillaryでアーカイブ化。
- `2024gsc_ShioriUehara`：相模原キャンパスの環境音を録音し地図化。
- `2025gsc_YudaiKato`：音楽視聴体験に位置情報・天気・気分を付与。
- `2025gsc_MIKUHAYASHI`：スノーボード滑走体験をGPXログとして比較。
- `2025gsc-KounaFukuda`：GeoGuessrのプレイ体験と思考プロセスをNotion・Excelに整理。

---

### Q058：研究室内で「現地調査」と「デジタルデータ」を組み合わせた研究を挙げて。

**期待される答え**：

- `2025gsc_MayuKanazawa`：Google Earth Proでの知覧再可視化と現地調査の照合。
- `2025gsc_RenseiInoue`：Wheelmap/OSM整備と町田駅周辺の現地評価。
- `2025gsc_YukariHayashi`：駅構内トイレの実地調査とOSMタグ提案。
- `2025gsc-AkiraMotoyoshi`：Strava実測歩行ログとQGIS分析。
- `2022gsc_IbukiShibayama`：ドローンLiDAR・iPhone LiDARと3Dモデル制作。

---

### Q059：古橋研究室の研究で「マニュアル化」が重要なものを挙げて。

**期待される答え**：

- `2018gsc_NairuNomura`：ZoomとiMovieを使った映像教材作成手法。
- `2019gsc_HinakoHori`：JOSMによるマッピング手法。
- `2022gsc_HarukaYasuda`：グラレコの準備・確認・実践プロセス。
- `2023gsc_Minaho_Ishii`：OpenDroneMapの概要・利用方法をグラレコ化。
- `2025gsc-KounaFukuda`：GeoGuessr判断基準を攻略集化。

---

### Q060：古橋研究室の研究で「UI/UX改善」が中心になっているものを挙げて。

**期待される答え**：

- `2024gsc_Tomoki-Fukamizu`：就活管理アプリのUIをGlideで作成。
- `2025gsc_MiaKozaki`：CLUB BAYSTARS加盟店情報をリストから地図へ変換し、ファンの回遊を促す。
- `2025gsc-ChihanaUsui`：横浜駅の高低差を直感的に理解できる地図デザイン。
- `2025gsc_YudaiKato`：音楽視聴履歴を時系列ではなく地図上で振り返るUI。
- `2025gsc_ShotaArakawa`：動画と地図を統合した観光WebマップUI。

---

## 7. 評価用の短問セット

以下は、NotebookLMやカスタムGPTが基礎知識を拾えているかを軽く確認するための短問。

| ID | 質問 | 期待される短答 |
|---|---|---|
| S001 | `cuisine=ramen;jiro` を使った代表的研究は？ | `2018gsc_YunaWatanabe`、`2021gsc_SotaSuzuki` |
| S002 | UNVT Portableを作ったのは？ | `2021gsc_ShogoHirasawa` |
| S003 | 住居表示住所デジタル化を調べたのは？ | `2021gsc_RanMatsuyama` |
| S004 | GIGAスクール端末のホワイトリスト研究は？ | `2021gsc_YunaHomma` |
| S005 | 相模原キャンパス3Dモデル制作は？ | `2022gsc_IbukiShibayama` |
| S006 | ジオガチャ開発は？ | `2022gsc_UraraNagashima` |
| S007 | おたすけグラレコ vol.3 は？ | `2022gsc_HarukaYasuda` |
| S008 | GOスナップショット×PLATEAUは？ | `2022gsc_NatsumiHaga` |
| S009 | 古橋bot制作は？ | `2023gsc_NaoyaUematsu` |
| S010 | ジャズ拡散×Mapbox Storytellingは？ | `2023gsc_ShioriUehara` |
| S011 | PLATEAU LOD1をOSMにインポートしたのは？ | `2023gsc_WataruYoshida` |
| S012 | 韓国道路名住所の2024研究は？ | `2024gsc_RikoSueki` |
| S013 | 相模原キャンパスの音地図は？ | `2024gsc_ShioriUehara` |
| S014 | 3Dボクセル検索APIは？ | `2024GSC_SatoAki` |
| S015 | 楢葉町災害アーカイブは？ | `2025gsc_ChisatoFuruuchi` |
| S016 | CKAN国際比較は？ | `2025gsc_FukaOkamura` |
| S017 | CLUB BAYSTARS加盟店マップは？ | `2025gsc_MiaKozaki` |
| S018 | 滑走記録アプリ比較は？ | `2025gsc_MIKUHAYASHI` |
| S019 | 町田Wheelmap研究は？ | `2025gsc_RenseiInoue` |
| S020 | 渋谷Wi-Fiカバー率は？ | `2025gsc_RitoYamasaki` |
| S021 | 音楽散歩地図は？ | `2025gsc_YudaiKato` |
| S022 | 横浜駅高低差地図デザインは？ | `2025gsc-ChihanaUsui` |
| S023 | Space Syntax×勾配は？ | `2025GSC-Hinako-Terado` |
| S024 | GeoGuessr攻略GEOINTは？ | `2025gsc-KounaFukuda` |

---

## 8. 古橋くんGPTに投げる最終チェック質問候補

### 候補A：一番おすすめ

**質問**：
古橋研究室の卒論・ゼミ論を横断して、「オープンデータ化」「体験の可視化」「教育・技能継承」の3系統に分け、それぞれ代表研究を3件ずつ挙げて説明して。

**この質問が強い理由**：
- 個別研究検索だけでは答えられない。
- 03_cross_theme_analysis、04_tool_index、01_all_research_summariesの全部を使う必要がある。
- 研究室全体の理解を試せる。

---

### 候補B：ツール理解重視

**質問**：
古橋研究室でQGIS、OpenStreetMap、PLATEAU、Mapbox/MapLibre、Blenderがそれぞれどんな目的で使われているか、代表研究と一緒に整理して。

**この質問が強い理由**：
- 04_tool_indexが効く。
- ツール名だけでなく、研究目的との対応を見られる。

---

### 候補C：失敗・限界重視

**質問**：
古橋研究室の研究で、技術的にうまくいかなかったことや限界を、後続研究に役立つ知見として残している例を5つ挙げて。

**この質問が強い理由**：
- きれいな成果だけでなく、DiscussionやConclusionを読めているか確認できる。
- 実践研究らしさを評価できる。

---

### 候補D：個別研究特定重視

**質問**：
「相模原キャンパス」「防災」「3D・Minecraft・PLATEAU」に関係する研究を、年度順に整理して、研究の発展の流れを説明して。

**この質問が強い理由**：
- 2022の3Dモデル、2024/2025のMinecraft、2025の防災教育などをつなげられる。
- 年度違い・同一人物・類似テーマの混同を見抜ける。

---

## 9. 使うときの注意

- ここにある「期待される答え」は採点用メモであり、古橋くんGPTの返答が一字一句同じである必要はない。
- ただし、リポジトリ名・年度・著者・ツール・成果物を取り違えた場合は減点。
- README本文が薄い研究について断定した場合も減点。
- 横断質問では、1つの研究だけでなく、複数研究をつないで説明できるかを見る。
- NotebookLMでは、`01_all_research_summaries.md`、`02_index_keywords.md`、`03_cross_theme_analysis.md`、`04_tool_index.md`、この `05_evaluation_questions.md` を一緒に入れると評価しやすい。
