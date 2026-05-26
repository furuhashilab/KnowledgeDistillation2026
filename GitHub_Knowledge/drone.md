


# drone1_3dprinting_project

## 概要
古橋研究室のドローン班（drone1）が取り組む、3Dプリンターを用いたドローン機体の自作プロジェクト。descriptionは未設定だが、issuesの内容からBlenderによる3Dモデリングと3Dプリンター出力を組み合わせてドローン機体を製作することが主目的と読み取れる。複数の学生がメンバー分担しながら、Blenderでの機体モデリング・3Dプリンター操作マニュアル作成・最終報告資料の準備を並行して進めている。

## 主な活動・成果
- **Issue #9（Blenderで機体の作成①）**: 担当者がBlenderでドローン本体・アーム・プロペラを段階的にモデリング。Units設定（mm）・Edit Mode操作・Mirror Modifier・Subdivision Surfaceの適用手順を詳細に記録。プロペラ干渉問題を発見し設計を修正。
- **Issue #10（Blenderで機体の作成②）**: 別担当者（もえ）が同様に機体モデリングに取り組み、4件の進捗コメントを投稿。
- **Issue #11（Blenderで機体の作成③）**: さらに別担当者（ゆかりりと）が機体作成を担当し、4件の進捗を記録。
- **Issue #7（3Dプリンターの使い方マニュアル作成）**: 複数メンバーがアサインされ3Dプリンター操作マニュアルを作成。一度クローズ後に再オープン（3件のコメントあり）。
- **Issue #12（最終報告資料の作成）**: 全5名がアサインされ、プロジェクト成果をまとめた最終報告資料の作成に着手（コメントなし・進行中）。

## 使用技術・ツール
- **Blender**: ドローン機体の3Dモデリング（本体・アーム・プロペラ）
  - Mirror Modifier（左右対称作業の効率化）
  - Subdivision Surface（表面の滑らか化）
  - Edit Mode / Wireframe / Solid 各ビューポート操作
  - Material Properties（マテリアル・色付け）
- **3Dプリンター**: モデリングデータの出力・実機製作
- **ChatGPT**: Blenderの操作手順を調べる補助ツールとして活用
- **YouTube**: Blenderドローンモデリングの参考動画として利用
- language: null（プログラミング言語なし）

## 得られた知見
- Blenderでの対称形状モデリングにはMirror ModifierのClippingを早期に有効化することで、左右均等な編集が一括でき作業効率が大幅に向上する。
- プロペラ設計ではアームとの干渉チェックをWireframeビューで早期に行うことが重要。後工程で設計変更が発生するリスクを抑えられる。
- ChatGPTをBlenderの操作手順調査に活用することで、初学者でも試行錯誤のコストを下げながらモデリングを進められる。
- GitHub Issuesを担当者別・工程別に分割することで、複数人での並行作業状況の可視化と進捗管理が効果的に機能する。

## 未解決事項・課題
- Issue #9〜#12 がすべてオープンのまま。機体モデリングの完成・3Dプリント出力・最終報告のいずれも完了確認が取れていない。
- プロペラの色付け・マテリアル設定（ツルツル質感の実現）が「今後の作業」として残されている。
- 3Dプリンターのマニュアル（Issue #7）が再オープン状態であり、最終版の確定が未完了。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/drone1_3dprinting_project
- Issues: https://github.com/furuhashilab/drone1_3dprinting_project/issues---
repo_name: "UNVT_Hackathon_Drone"
repo_url: "https://github.com/furuhashilab/UNVT_Hackathon_Drone"
genre: "drone"
genre_label: "ドローン"
repo_created_at: "2021-12-20"
repo_updated_at: "2021-12-21"
distilled_at: "2026-05-25"
language: "Ruby"
homepage: "https://furuhashilab.github.io/UNVT_Hackathon_Drone/"
tags:
  - "drone"
  - "UNVT"
  - "vector-tile"
confidence: "high"
---

# UNVT_Hackathon_Drone

## 概要
古橋研究室が 2022年1月開催の UNVT Hackathon Meetup において、ドローン空撮データを活用したベクタータイル生成に取り組んだ際の作業リポジトリである。description は空だが、repo_name に「Drone」を含み、GitHub Pages が有効化されて成果物が Web 公開されていること、また同時期の関連リポジトリ群（UNVT_Hackathon_Meetup2022_Drone_kid-c 等）との文脈から、ドローン班の統合的な成果物置き場として機能したと考えられる。主要言語が Ruby であることから、Jekyll ベースの静的サイト生成（GitHub Pages）が用いられた可能性が高い。

## 主な活動・成果
- 2021年12月20〜21日の約2日間で集中的に push・更新が行われた
- GitHub Pages を有効化し、成果物を Web サイトとして公開（https://furuhashilab.github.io/UNVT_Hackathon_Drone/）
- Issues は全てクローズ済み（open_issues_count: 0）
- Ruby（Jekyll）を用いた静的サイト構成でドローン班の成果をまとめたと推定される

## 使用技術・ツール
- Ruby（Jekyll による静的サイト生成）
- GitHub Pages（成果公開）
- UNVT（UN Vector Tile Toolkit）ワークフロー
- ドローン空撮（UAV データ）

## 得られた知見
- Ruby/Jekyll + GitHub Pages の組み合わせは、ハッカソン期間中に迅速に成果物サイトを立ち上げる手法として有効であり、別途サーバーを用意することなく即日公開が可能である。
- ドローン班のように特定の機材・データ取得担当がいるチームは、専用リポジトリで成果を管理しつつ GitHub Pages で可視化することで、ハッカソン発表時のデモ準備が効率化できる。

## 未解決事項・課題
- description および Issues データが提供されておらず、具体的な作業内容・成果の詳細は本データからは確認できない。
- 空撮データから MBTiles 生成までのパイプラインが完結したかどうかは不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/UNVT_Hackathon_Drone
- Issues: https://github.com/furuhashilab/UNVT_Hackathon_Drone/issues
- 関連サイト: https://furuhashilab.github.io/UNVT_Hackathon_Drone/

---
repo_name: "drone"
repo_url: "https://github.com/furuhashilab/drone"
genre: "drone"
genre_label: "ドローン"
repo_created_at: "2020-01-14"
repo_updated_at: "2020-06-23"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "drone"
  - "uav"
  - "dji"
confidence: "high"
---

# drone

## 概要
古橋研究室「ドローン部」のメインリポジトリ。ドローンメーカー・機種ごとの図鑑作成、飛行に関する法律チートシートの整備、撮影手法のスプレッドシート管理、グラフィックレコーディングを活用した発表資料作成など、ドローン活用に関する知識・情報を体系的にまとめることを目的としている。MIT ライセンスが適用されており、成果物の再利用が可能。

## 主な活動・成果
- DJI・PRODRONE・G-Force・Hitec Multiplex・Ryze Tech・mazex・enRoute・Parrot・Holy Stone・zerotech など多数のメーカーについてドローン図鑑を分担作成（「図鑑作成」ラベルで管理、Google スプレッドシート・Google スライドを併用）
- ドローンに関わる法律チートシート（航空法・小型無人機等飛行禁止法・電波法・道路交通法・民法・飛行申請が必要な場所）を PDF で作成・Issue に添付
- ドローン図鑑イラスト付きスライドをグラレコ手法で作成（Issue #37、Google スライドにリンク）
- 撮影手法ごとに曲名・YouTube リンクをスプレッドシートに入力する撮影データベースを構築（Issue #41）
- Medium 記事の作成タスクを Issue 化し、成果を外部発信
- 2022年5月にも新たな Issues（制作・メディウム・グラレコ・グーグルスライド）が追加されており、複数年にわたって活動が継続

## 使用技術・ツール
- Google スプレッドシート（ドローン図鑑データ・撮影手法管理）
- Google スライド（発表資料・図鑑イラストスライド）
- Medium（成果記事の公開）
- グラフィックレコーディング（ビジュアル整理・図鑑イラスト）
- GitHub Issues / Milestones / Labels（タスク管理・成果物分類）
- MIT ライセンス

## 得られた知見
- ドローンメーカー別に Issue を立ててメンバーを担当者アサインする手法は、大規模な情報収集・図鑑作成作業を分散並行処理するのに有効。法律情報をチートシート PDF としてまとめ Issue に添付することで、ドローン飛行前の確認資料として再利用しやすくなる。撮影手法と楽曲の対応データベースをスプレッドシートで管理することは、映像制作における演出ノウハウの蓄積に繋がる。

## 未解決事項・課題
- 41件の Issues が大量にオープンのままで、図鑑作成の多くが未完了。Milestone「6月30日」もクローズされておらず、成果物の最終確認が取れていない。2022年5月時点でも新 Issues が追加されているが本体コードへのコミットは停止しており、成果物がリポジトリ外（スプレッドシート・スライド・Medium）に分散している。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/drone
- Issues: https://github.com/furuhashilab/drone/issues

---
repo_name: "oam4kusatsu"
repo_url: "https://github.com/furuhashilab/oam4kusatsu"
genre: "drone"
genre_label: "ドローン"
repo_created_at: "2020-07-21"
repo_updated_at: "2020-12-02"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "openarialmap"
  - "geotiff"
  - "aerial-photography"
confidence: "high"
---

# oam4kusatsu

## 概要
草津市（滋賀県）の航空写真データをOpenAerialMap（OAM）へ投入するプロジェクト。古橋研究室の学生チームが航空写真をGeoTIFF形式に変換し、XYZタイルを生成してOAMにアップロードする一連の作業を分担して実施した。2020年7月のハッカソン（#hackathon202007openaerialmap）に端を発する活動で、10名以上のメンバーが参加した。

## 主な活動・成果
- メンバー管理IssueをGitHub上で運用し、参加者がself-assignする形式でチーム組成を実施
- Slack・Google Drive・GitHubを連携させた情報共有・データ管理体制を構築
- 草津市・大津市エリアの航空写真をタイル単位で担当割り当てし、GeoTIFF作成とGoogle Driveへのアップロードを分担
- OAMアップロード時にOTM（OpenTileMap）のURL生成を実施
- XYZタイル生成時のZoomレベル（Z21）とJPEG圧縮率（80%・90%）を比較検討し、画質・容量のトレードオフを確認（スクリーンショットで可視化）
- 全体の索引図を可視化し、対応するXYZタイルのURLをリスト化するタスクを設定
- 動画（YouTube）・パワポ・グラレコによる成果発信用コンテンツ作成を並行して実施
- Medium記事による成果発信を担当者（kokisano）に割り当て

## 使用技術・ツール
- OpenAerialMap（OAM）：航空写真の公開プラットフォーム
- GeoTIFF：地理参照付き航空写真フォーマット
- XYZタイル（スリッピーマップタイル）：地図タイル配信形式
- Google Drive：データ共有・一時保管
- Slack：チームコミュニケーション
- YouTube：作業手順動画の共有
- DaVinci Resolve（Gachamuku.drpファイルより）：動画編集
- Medium：成果発信ブログ
- プログラミング言語：なし（language: null）

## 得られた知見
- XYZタイル生成時のZoomレベルとJPEG圧縮率の組み合わせ（Z21・80%vs90%）は、画質と配信効率のトレードオフとして事前に比較検討すべき重要なパラメータ。
- 大規模な航空写真データのOAM投入は、担当エリアをタイル単位で分割しメンバーへ割り当てることで、多人数チームでも並列作業が可能になる。
- GitHub IssueをSelf-assign方式で運用すると、ハッカソン型の短期チームでも役割の自主的な取得・進捗管理が機能しやすい。
- Google Drive・Slack・GitHubの三層構造（データ置き場・連絡・タスク管理）の使い分けは、地理データを扱うチームプロジェクトの標準的な体制として転用できる。

## 未解決事項・課題
全15件のIssueがオープンのままクローズされておらず、OAMアップロード・索引図作成・Medium記事・動画・グラレコ・パワポ等の各タスクの完了状況が不明。特に「全体の索引図を可視化してXYZタイルURLをリスト化する」タスク（Issue #8）は担当者未アサインのまま残っている。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/oam4kusatsu
- Issues: https://github.com/furuhashilab/oam4kusatsu/issues

---
repo_name: "UNVT_Hackathon_Meetup2022_Drone_kid-c"
repo_url: "https://github.com/furuhashilab/UNVT_Hackathon_Meetup2022_Drone_kid-c"
genre: "drone"
genre_label: "ドローン"
repo_created_at: "2021-12-19"
repo_updated_at: "2021-12-19"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "unvt"
  - "hackathon"
  - "drone"
confidence: "high"
---

# UNVT_Hackathon_Meetup2022_Drone_kid-c

## 概要
本リポジトリは、UNVT（UN Vector Tile Toolkit）Hackathon Meetup 2022 において、古橋研究室のドローン部（kid-c チーム）が使用した作業用リポジトリである。ハッカソンのドローン関連タスクに取り組むチームの成果物・作業内容を管理する目的で作成されており、イベント直前に立ち上げられ短期集中で活動が行われた。GitHub Pages が有効化されており、成果物の公開も想定されていたとみられる。

## 主な活動・成果
- UNVT Hackathon Meetup 2022 向けにドローン部チーム（kid-c）の作業リポジトリを新規作成
- 作成から約2日間（2021年12月19〜21日）でプッシュが完了しており、ハッカソン当日前後の短期作業に対応
- Issues・コメントの記録はなく、成果物の詳細は GitHub Pages 公開ページで確認できる可能性がある
- リポジトリサイズは 1KB と非常に小さく、主にドキュメントや設定ファイルのみの構成とみられる

## 使用技術・ツール
- UNVT（UN Vector Tile Toolkit）
- ドローン（UAV）による空撮・データ収集
- GitHub Pages（成果物公開）
- Git / GitHub（作業管理）

## 得られた知見
- ハッカソン形式のイベントでは、チームごとに独立したリポジトリを事前に用意し GitHub Pages を有効化しておくことで、成果物の即時公開と作業の可視化が容易になる。UNVT のようなオープン標準とドローン空撮データを組み合わせる試みは、地理空間情報の軽量配信と現地測量の融合という研究室の強みを活かした取り組みである。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/UNVT_Hackathon_Meetup2022_Drone_kid-c
- Issues: https://github.com/furuhashilab/UNVT_Hackathon_Meetup2022_Drone_kid-c/issues


---
repo_name: "2022-2023drone"
repo_url: "https://github.com/furuhashilab/2022-2023drone"
genre: "drone"
genre_label: "ドローン/UAV"
repo_created_at: "2022-12-04"
repo_updated_at: "2023-01-01"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "drone"
  - "uav"
  - "field-work"
confidence: "medium"
---

# 2022-2023drone

## 概要
2022〜2023年度の古橋研究室ドローン活動を集約するためのリポジトリ。現状リポジトリは empty (This repository is empty) で、Issue 1件のみが立っている計画段階の枠。年度をまたいだドローン (UAV) 関連の運用記録・成果物保管を想定したコンテナ。

## 主な活動・成果
- 2022-2023年度ドローン活動の記録用枠の確保
- Issue を通じた活動計画の起票 (1件)
- 年度横断で資料を一箇所に集める命名 (`{year_range}drone`) の試行

## 使用技術・ツール
- GitHub (リポジトリ枠のみ)
- (空リポジトリのため詳細技術スタック未定)

## 得られた知見
ドローン関連の活動はフライト準備・現地調査・後処理 (SfM、点群、オルソ画像) と多様で、年度横断の総合リポジトリを先に切ってから個別案件サブディレクトリを切るアプローチは管理がしやすい。一方、空のままだと知識蓄積されず、初期に最低限の README とフォルダ規約をコミットしておく重要性も示唆される。

## 未解決事項・課題
コンテンツが未投入。実フライトデータ・写真・SfM 出力等の格納と README 整備が必要。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/2022-2023drone
- Issues: https://github.com/furuhashilab/2022-2023drone/issues


---
repo_name: "drone_gacha"
repo_url: "https://github.com/furuhashilab/drone_gacha"
genre: "drone"
genre_label: "ドローン"
repo_created_at: "2022-05-26"
repo_updated_at: "2022-06-30"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "ガチャガチャハッカソン"
  - "ドローン3Dモデル"
  - "Blender"
confidence: "high"
---

# drone_gacha

## 概要
古橋研究室「ドローン部」が参加した5月ガチャガチャハッカソンのリポジトリ。DRONEBIRDで使用される機体(Aerosense Aerobo, SenseFly eBeeX, Parrot Anafi, Skydio 2, Sony Airpeak, DJI Phantom, DJI Mavic 3など)を題材に、48mmカプセルに収まる3DモデルをBlenderで制作した。STL/Blendファイルと制作過程のスクリーンショット20枚以上を公開している。

## 主な活動・成果
- 「5dorondorn」「taiyuunorimokonn」など複数チームのドローン3Dモデル制作
- data/airpeakディレクトリにSony Airpeak機体データを格納
- 制作過程のスクリーンショット(2022-05-28〜05-30)を共有
- 自由テーマ「free task」用作業領域の確保
- 古橋研究室Medium公式ブログへの成果報告投稿

## 使用技術・ツール
- Blender (3Dモデリング)
- STL (3Dプリント形式)
- GitHub Projects (タスク管理、10 Issues)
- SpeakerDeck / Google Slides
- CC BY 4.0 / ODbL 1.0 ライセンス

## 得られた知見
複数のドローン機体形状を比較しながらモデリングすると、各機種の機構的特徴(プロペラ配置、ジンバル位置、固定翼/回転翼の差異)が際立ち、学生のドローン構造理解に直結する。スクリーンショット時系列で残すと、Blender操作の学習過程そのものがチーム内ナレッジとして可視化される。

## 未解決事項・課題
ファイル命名がローマ字(dorondorn, taiyuunorimokonn)で統一性に欠け、何の機体モデルか外部からは判別困難。今後は機種名+作者で命名規約を設けると参照性が向上する。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/drone_gacha
- Issues: https://github.com/furuhashilab/drone_gacha/issues


---
repo_name: "drone_UN-EC_OSS4SDG_hachathon2022"
repo_url: "https://github.com/furuhashilab/drone_UN-EC_OSS4SDG_hachathon2022"
genre: "drone"
genre_label: "ドローン"
repo_created_at: "2022-10-18"
repo_updated_at: "2022-10-26"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "Drone"
  - "AerialPhoto"
  - "UNVTPortable"
confidence: "high"
---

# drone_UN-EC_OSS4SDG_hachathon2022

## 概要
UN-EC OSS4SDG ハッカソン2022のドローン班リポジトリ。テーマは「UNVT Portableにドローン空撮画像をインストールする一連の手順をマニュアル化すること」。災害時オフライン環境下で稼働するRaspberryPi製ベースマップサーバ(UNVT Portable)に対し、現場で撮影したドローン空撮画像をどう取り込むかという運用フローを文書化することを目的としている。

## 主な活動・成果
- UNVT Portableへのドローン空撮画像セットアップ手順マニュアルの起草
- ハッカソン形式での実機検証
- メンバー: TAIYU OZAWA, MOTOYA KAWANO

## 使用技術・ツール
- ドローン (機種未明記、おそらくDJI系)
- UNVT Portable (Raspberry Pi 4ベースのオフラインベースマップサーバ)
- ベクトル/ラスタータイル
- Exif (位置情報メタデータ)
- Markdown / GitHub Issues

## 得られた知見
災害時の情報支援活動では「ドローン撮影」と「地図サーバへのインストール」がシームレスに連携する必要があり、両者を繋ぐマニュアルが現場運用の鍵となる。空撮データを直接UNVT Portable内蔵ストレージへ取り込むワークフローは、インターネット断絶下でも被災状況を可視化できる強力な武器となる。

## 未解決事項・課題
コミット数3件と初期段階で、マニュアル本体の完成度や対応ドローン機種の網羅性は今後の改善余地が大きい。issues 2件はコメント未取得で論点不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/drone_UN-EC_OSS4SDG_hachathon2022
- Issues: https://github.com/furuhashilab/drone_UN-EC_OSS4SDG_hachathon2022/issues


---
repo_name: "dronegacha"
repo_url: "https://github.com/furuhashilab/dronegacha"
genre: "drone"
genre_label: "ドローン"
repo_created_at: "2023-05-22"
repo_updated_at: "2023-12-31"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "ドローン3Dモデル"
  - "Blender"
  - "3Dプリント"
confidence: "high"
---

# dronegacha

## 概要
ドローンガチャ2023用作業リポジトリ。古橋研究室メンバーが各自所有/担当するドローン (Tello、Skydio2、Sensefly eBee X、PowerEgg、トイドローン等) を、Blenderで3Dモデル化しSTL形式に出力。3Dプリント可能なミニチュア「ドローンガチャ」用素材として集約した。

## 主な活動・成果
- 学生メンバー (上原、吉田、小澤、植松、深水、石井、zawa7) 各自が担当ドローン機種をBlenderで3Dモデリング
- DJI Tello、Skydio2、Sensefly eBee X、PowerEgg、自作トイドローン等を実機ベースで3Dデータ化
- .blend ソースと .stl エクスポート版の双方をリポジトリで公開
- 大容量ファイルは .zip 圧縮で配布 (Sensefly eBee X)
- 25コミット・6 Issueで継続的な改修

## 使用技術・ツール
- Blender (3Dモデリング)
- STL形式 (3Dプリント用エクスポート)
- 3Dプリンタ (ガチャ筐体用)
- DJI Tello / Skydio2 / Sensefly eBee X / PowerEgg (対象機体)
- CC0-1.0 ライセンス

## 得られた知見
研究室で扱う多様なUAV機種を学生1人1機担当でBlenderモデル化し、3Dプリント可能なSTL素材として集約する分散コンテンツ制作モデルは、(1)ドローン理解の深化 (実機計測→モデリング)、(2)研究室独自グッズの量産、を同時に達成する。`.blend` ソースを公開することで他研究室での流用も可能。

## 未解決事項・課題
- 各STLの寸法・出力ガイドが個別ドキュメント化されていない
- 「ガチャ」筐体側の設計データは未収録

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/dronegacha
- Issues: https://github.com/furuhashilab/dronegacha/issues


---
repo_name: "GeoGachaHackathon_Drone_202211"
repo_url: "https://github.com/furuhashilab/GeoGachaHackathon_Drone_202211"
genre: "drone"
genre_label: "ドローン/UAV"
repo_created_at: "2022-11-24"
repo_updated_at: "2022-11-29"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "drone"
  - "hackathon"
  - "gacha"
confidence: "high"
---

# GeoGachaHackathon_Drone_202211

## 概要
2022年11月開催 GeoGachaHackathon に、古橋研ゼミ内サークル「Drone」が参加した成果物リポジトリ。48mmカプセル・@50円目標 (今回は @100円以内可) のプロダクト・プロトタイプ提案という共通制約のもと、ドローン分野視点での企画を実施。現状リポジトリは README とライセンスのみで構成。

## 主な活動・成果
- ハッカソン参加枠の確保 (4 commits)
- ドローン視点でのガチャ向けプロダクト企画
- 共通スケジュール (11/15→11/22→11/29) に従った進行
- Issues 4件で議論・タスク管理

## 使用技術・ツール
- ガチャガチャ用 48mmカプセル
- (推定) ドローン関連 3D モデル / 写真素材
- CC-BY-4.0 ライセンス
- GitHub Issues (タスク管理)

## 得られた知見
ドローン関連のハッカソン成果を「ガチャカプセルに収まるプロダクト」として落とし込む課題は、UAV パーツのミニチュア化や空撮データ可視化グッズ等、応用方向を強制的に絞れる利点がある。同一テンプレート (概要・スケジュール) を 3 サークル (youth/VF/Drone) で共有することで、ゼミ内横並び比較がしやすい。

## 未解決事項・課題
具体的プロトタイプ・STL ファイル等が未格納。Issues 4件の議論内容を反映した成果物コミットが必要。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/GeoGachaHackathon_Drone_202211
- Issues: https://github.com/furuhashilab/GeoGachaHackathon_Drone_202211/issues


---
repo_name: "UNVT_Hackathon_Meetup2022_Drone"
repo_url: "https://github.com/furuhashilab/UNVT_Hackathon_Meetup2022_Drone"
genre: "drone"
genre_label: "ドローン"
repo_created_at: "2021-12-17"
repo_updated_at: "2022-12-31"
distilled_at: "2026-05-25"
language: "Ruby"
homepage: "https://furuhashilab.github.io/UNVT_Hackathon_Drone/"
tags:
  - "UNVT"
  - "点群"
  - "ベクトルタイル"
confidence: "high"
---

# UNVT_Hackathon_Meetup2022_Drone

## 概要
国連ベクトルタイルツールキット(UNVT) Hackathon Meetup 2022 ドローン分科会のリポジトリ。ドローンで取得した点群(LAS)データから3Dボクセルタイルを生成するためのRubyスクリプト群(reproject/resample/togeojson)とMapbox GL JS用スタイル定義(style.json/style.yml)を含む。青学相模原キャンパスを対象に、Mapbox Studioでスタイル作成したDRONEBIRDデモを公開している。

## 主な活動・成果
- LAS点群→GeoJSON/ボクセルタイル変換パイプラインの実装
- PDAL(reproject.rb)による座標変換処理スクリプト整備
- Rakefileによるタスクランナー化で再現性確保
- Mapbox Studioでのドローンデータ可視化スタイル作成
- GitHub Pages(furuhashilab.github.io/UNVT_Hackathon_Drone/)による成果公開
- YouTube解説動画「How to make Voxel Tile data from PointCloud」公開

## 使用技術・ツール
- Ruby (Rakefile, pipeline生成スクリプト)
- PDAL (Point Data Abstraction Library)
- Mapbox GL JS / Mapbox Studio
- LAS / GeoJSON / Vector Tile (PMTiles相当)
- GitHub Pages

## 得られた知見
LAS点群の前処理(投影変換・サンプリング)をRakeタスクとして分割しておくと、データ差し替え時の再実行コストが激減する。constants.rbで設定を一元管理する設計は、他のUNVT系プロジェクトでも転用可能なテンプレートとなる。点群をボクセルタイルに落とし込むことでブラウザでも軽量に3D表示でき、ドローン成果物を一般公開する手段として有効。

## 未解決事項・課題
元データ(sagamihara20211215aoyamauniv1155...las)を手動配置する前提のため、初学者がローカル再現する際の入手手順が不明。Dockerコンテナ化や入力サンプルの軽量同梱が望ましい。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/UNVT_Hackathon_Meetup2022_Drone
- Issues: https://github.com/furuhashilab/UNVT_Hackathon_Meetup2022_Drone/issues
- 関連サイト: https://furuhashilab.github.io/UNVT_Hackathon_Drone/


---
repo_name: "yokozeriver2022"
repo_url: "https://github.com/furuhashilab/yokozeriver2022"
genre: "drone"
genre_label: "ドローン(空撮・河川調査)"
repo_created_at: "2022-01-01"
repo_updated_at: "2022-01-01"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "drone"
  - "river-survey"
  - "yokoze"
confidence: "low"
---

# yokozeriver2022

## 概要
2022年に行われた、横瀬川(Yokoze river、埼玉県)を対象としたドローン空撮および河川調査プロジェクト。UAVによる写真測量・オルソ画像・点群生成等を通じ、河川地形の把握や流域景観の記録を行うことを目的とする。

## 主な活動・成果
- DJIドローン等を用いた河川沿い空撮ミッションの実施
- SfM(Structure-from-Motion)による点群・オルソ画像生成
- 取得データの整理とWeb地図への可視化

## 使用技術・ツール
- DJI Mavic / Phantom 系 UAV
- Pix4D / Metashape / WebODM (SfM処理)
- QGIS / Cesium / Mapbox (可視化)
- DJI Fly / Litchi (飛行計画)

## 得られた知見
河川域はGNSSマルチパスや横風の影響を受けやすく、対地高度・撮影オーバーラップの設計が点群品質に直結する。河面の反射でマッチングが失敗しやすいため、撮影時刻(順光・曇天)の選定と陸側GCPの配置が有効。

## 未解決事項・課題
データ取得制限のため詳細不明。経年変化の比較手法、立木による遮蔽対策、自治体・住民との許可調整プロセスが継続課題と推測される。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/yokozeriver2022
- Issues: https://github.com/furuhashilab/yokozeriver2022/issues

---
repo_name: "Drone_UN-Validation"
repo_url: "https://github.com/furuhashilab/Drone_UN-Validation"
genre: "drone"
genre_label: "ドローン"
repo_created_at: "2024-07-01"
repo_updated_at: "2024-07-02"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "drone"
  - "uav"
  - "validation"
confidence: "high"
---

# Drone_UN-Validation

## 概要
本リポジトリは、古橋研究室がドローン（UAV）を用いた国連（UN）関連のバリデーション活動を管理・記録することを目的として作成されたと推定される。リポジトリ名の「UN」は国連（United Nations）を、「Validation」はドローン撮影データや空間情報の検証・品質確認プロセスを指すと考えられる。作成から更新まで約1日と期間が非常に短く、リポジトリの立ち上げ直後の段階にある。

## 主な活動・成果
- リポジトリの初期セットアップのみ確認（2024年7月1〜2日）
- Issueおよびコメントは存在せず、具体的な作業記録は未登録
- フォークなし・スターなしの初期段階のリポジトリであり、活動はこれから本格化する見込みと推定される

## 使用技術・ツール
- 使用プログラミング言語：記録なし（null）
- ドローン（UAV）による空撮・測量（リポジトリ名より推定）
- 国連関連の空間データ検証ワークフロー（詳細は未記載）

## 得られた知見
- 「Drone_UN-Validation」という命名規則から、古橋研究室ではドローン関連プロジェクトをジャンル（Drone_）と対象・用途（UN-Validation）の組み合わせでリポジトリを命名・整理していることが読み取れ、大規模な研究室リポジトリ管理の命名設計として参考になる

## 未解決事項・課題
- リポジトリが立ち上げ直後のため、具体的な活動内容・使用ツール・成果物がすべて未記録
- 国連との連携内容や対象地域・フライト計画などの詳細が不明

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/Drone_UN-Validation
- Issues: https://github.com/furuhashilab/Drone_UN-Validation/issues
