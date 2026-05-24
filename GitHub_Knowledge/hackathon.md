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

---
repo_name: "M6_HackathonVF"
repo_url: "https://github.com/furuhashilab/M6_HackathonVF"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-06-07"
repo_updated_at: "2021-06-07"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "ハッカソン"
  - "グラフィックレコーディング"
  - "ルート考察"
confidence: "medium"
---

# M6_HackathonVF

## 概要
古橋研究室のメンバー（rensanrenren）が参加したハッカソンの作業管理リポジトリと推察される。リポジトリ名「M6_HackathonVF」のVFはVision/Final等の略と考えられる。Issuesにより「応募」「スライド」「medium」「ルート考察」「グラレコ」といった作業タスクが立てられており、ハッカソン参加に向けた成果物制作の進行管理に用いられた。

## 主な活動・成果
- Issue #1（応募）: ハッカソンへの応募作業を担当者（rensanrenren）にアサイン。
- Issue #2（スライド）: 発表用スライドの作成タスクとして起票・担当者アサイン済み。
- Issue #3（medium）: Mediumへの記事投稿またはドキュメント作成タスクと推察。
- Issue #4（ルート考察）: 提案するルートやソリューションの検討タスク。
- Issue #5（グラレコ）: グラフィックレコーディング（グラレコ）の作成タスク。
- 全Issueが同日（2021-06-07）に一括起票されており、ハッカソン直前の作業洗い出しと分担が行われた。

## 使用技術・ツール
- GitHub Issues（タスク管理）
- Medium（アウトプット発信媒体として想定）
- グラフィックレコーディング（視覚的議事録・アイデア整理手法）

## 得られた知見
- ハッカソン参加時に「応募・スライド・記事執筆・ルート考察・グラレコ」といった成果物を事前にIssueとして洗い出し、担当者アサインまで行うことで、短期集中の開発イベントでも作業の抜け漏れを防ぐタスク管理が可能になる。グラレコをアウトプットの一形式として位置づけている点も、古橋研究室の発表スタイルの特徴として参照できる。

## 未解決事項・課題
- 全Issueのbodyおよびコメントがすべてなくタスクの詳細・完了状況が不明。ハッカソンの名称・テーマ・結果も記録されていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/M6_HackathonVF
- Issues: https://github.com/furuhashilab/M6_HackathonVF/issues

- ---
repo_name: "hackathon_yokozemap"
repo_url: "https://github.com/furuhashilab/hackathon_yokozemap"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-06-03"
repo_updated_at: "2021-06-04"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "ハッカソン"
  - "ドローン"
  - "地図"
confidence: "high"
---

# hackathon_yokozemap

## 概要
古橋研究室ドローン部が2021年6月に参加したハッカソン（"横ざマップ"または横断的地図系ハッカソンと推察）の作業管理リポジトリである。descriptionに「ドローン部　６月ハッカソン」と明記されており、ドローン・地図・測量に関連するテーマで取り組んだイベントとみられる。複数メンバー（MatsuyamaRan・yunapanpan12・cancancanda・naoki2123）が協働し、発表資料・記事執筆・グラレコ・コース設計・応募用紙作成といった成果物を分担した。

## 主な活動・成果
- Issue #1（スライド）: 発表用スライドの作成タスクとして起票。
- Issue #2（メディウム）: Medium記事の執筆・投稿タスクとして起票。
- Issue #3（グラレコ）: グラフィックレコーディングの作成タスクとして起票。
- Issue #4（コース決め）: ドローン飛行コースまたはハッカソン提案ルートの検討タスク。MatsuyamaRan・yunapanpan12・cancancanda・naoki2123の4名がアサインされており、チーム全体で取り組む中心課題であったと推察。
- Issue #5（応募用紙作成）: ハッカソンへの正式応募書類の作成タスク。MatsuyamaRanが担当。

## 使用技術・ツール
- GitHub Issues（タスク管理・担当者アサイン）
- Medium（成果アウトプット媒体として想定）
- グラフィックレコーディング（アイデア可視化）
- ドローン関連技術（descriptionより推察）

## 得られた知見
- ハッカソン参加時のタスクを「スライド・記事・グラレコ・コース設計・応募」の5カテゴリに分解してIssue化し、担当者を明示する管理手法は、短期間のチーム制作において役割分担を明確にする上で有効。特に「コース決め」に複数名をアサインする形は、地図・空間系テーマで合意形成が必要なタスクへの適切な対応といえる。

## 未解決事項・課題
- 全Issueのbodyおよびコメントがすべてなくタスクの詳細・完了状況が不明。ハッカソンの正式名称・テーマ・結果も記録されていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/hackathon_yokozemap
- Issues: https://github.com/furuhashilab/hackathon_yokozemap/issues

---
repo_name: "hachathon_3dmodel"
repo_url: "https://github.com/furuhashilab/hachathon_3dmodel"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-05-12"
repo_updated_at: "2021-05-24"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "3Dモデル"
  - "ドローン"
  - "フォトグラメトリ"
confidence: "high"
---

# hachathon_3dmodel

## 概要
古橋研究室ドローン部が取り組んだ「ガチャガチャ3Dモデル」制作ハッカソンの作業管理リポジトリである。ドローン機体（DJI Mavic Air・Phantom 2・Parrot Disco FPV・ピッコロ等）の3DモデルをSTL・OBJ形式で作成し、ガチャガチャの景品として利用することを目指したプロジェクトと推察される。Blenderによるモデリングとスマホアプリを用いた3Dスキャンの両アプローチが試みられた。

## 主な活動・成果
- Issue #5（ガチャガチャのテーマ）: テーマを全員（MatsuyamaRan・yunapanpan12・cancancanda・naoki2123）でアサイン。チームの中心課題として取り組んだ。
- Issue #6（GIFからSTLへ変換）: LiDARスキャナ非搭載端末のため「Qlone 3Dスキャナー」アプリでGIF出力したが、STL/OBJへの変換は有料だったため断念。オンライン変換サービスでも変換不可だった。
- Issue #7（DJI Mavic Air STL・OBJ）: yunapanpan12・cancancandaがアサイン。ドローン機体の3Dデータ作成。
- Issue #8（Parrot Disco FPV STL・OBJ）: cancancandaが起票。
- Issue #9（ブレンダーで作成）: MatsuyamaRan・cancancandaがBlenderで3Dモデルを制作。
- Issue #10（Phantom 2 STL・OBJ）: priorityラベル付きで優先タスクとして管理。
- Issue #11（DRONE BIRDロゴ STL・OBJ）: ロゴの3Dデータ化を実施。
- Issue #12（ピッコロ STL・OBJ）: 小型ドローン「ピッコロ」の3Dデータ作成。
- Issue #4（フォトグラメトリで撮影）: bugラベルがつき、撮影に何らかの問題が発生した。
- Issue #14（データ置き場）: 成果データの共有・格納用Issueとして設置。

## 使用技術・ツール
- Blender（3Dモデリング）
- Qlone 3Dスキャナー（iOS向けスマホ3Dスキャンアプリ）
- STL・OBJ（3Dデータフォーマット）
- フォトグラメトリ（写真測量による3Dモデル生成）
- GitHub Issues（タスク管理・データ置き場）

## 得られた知見
- LiDARスキャナ非搭載デバイスで3Dスキャンを試みる場合、「Qlone」等のアプリではGIF出力にとどまりSTL/OBJ変換が有料となるため、フォトグラメトリ（複数枚写真からの3D生成）やBlenderでの手動モデリングが現実的な代替手段となる。ドローン機体のような細部の多い立体物のモデリングはBlenderで直接作成する方が精度・コスト面で優位になる場合がある。

## 未解決事項・課題
- 全Issueがopenのままで、各機体の3Dモデル完成・データ提出状況が不明。フォトグラメトリ撮影のbugも未解決。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/hachathon_3dmodel
- Issues: https://github.com/furuhashilab/hachathon_3dmodel/issues

---
repo_name: "fc_game"
repo_url: "https://github.com/furuhashilab/fc_game"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-05-18"
repo_updated_at: "2021-05-18"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "ハッカソン"
  - "ゲーム"
  - "Medium"
confidence: "high"
---

# fc_game

## 概要
古橋研究室のメンバー（plinplin22・naoki2123）が2021年5月18日に開催したハッカソンの作業管理リポジトリである。「fc_game」というリポジトリ名とIssue #1のタイトル「5/18ハッカソン」から、ゲーム制作をテーマにした1日集中型のハッカソンと推察される。CC BY 4.0ライセンスが付与されており、成果物の共有を前提とした取り組みであった。Issue #3にはMedium記事（タコさんウインナーをテーマにした記事と推察）、Issue #2にはGoogle Slidesのプレゼン資料へのリンクが記録されており、成果の一部はすでに公開されている。

## 主な活動・成果
- Issue #1（5/18ハッカソン）: ハッカソン全体の管理Issueとして起票。
- Issue #2（プレゼン資料）: Google Slidesで制作した発表資料へのリンクを共有（plinplin22）。
- Issue #3（medium）: Medium記事「タコさんウインナー」を公開・リンク共有（https://medium.com/furuhashilab/タコさんウインナー-cf1b0c251fcd）。
- Issue #4・5・6・7・8: マイルストーン「2020/05/18」に紐づいた当日タスクとして、テーマ決め・制作・プレゼン資料・Medium・GitHub作成の5タスクをnaoki2123が一括起票しplinplin22にアサイン。

## 使用技術・ツール
- GitHub Issues（タスク管理・マイルストーン運用）
- Google Slides（プレゼン資料制作）
- Medium（成果記事公開）
- CC BY 4.0 License

## 得られた知見
- ハッカソン当日にマイルストーンを設定してタスクを一括起票し、担当者にアサインする運用は、短時間イベントでの進捗見える化に有効。また成果物（プレゼン・Medium記事）のリンクをIssueに貼ることで、事後の振り返りやアーカイブとしてリポジトリを活用できる。

## 未解決事項・課題
- 全Issueがopenのままで完了記録がない。ハッカソンのテーマ・成果の詳細はMedium記事（https://medium.com/furuhashilab/タコさんウインナー-cf1b0c251fcd）を参照することで把握できる可能性がある。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/fc_game
- Issues: https://github.com/furuhashilab/fc_game/issues
- Medium記事: https://medium.com/furuhashilab/タコさんウインナー-cf1b0c251fcd

---
repo_name: "Hackathon_VF"
repo_url: "https://github.com/furuhashilab/Hackathon_VF"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-05-18"
repo_updated_at: "2023-04-14"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "ハッカソン"
  - "動画編集"
  - "3Dモデル"
confidence: "high"
---

# Hackathon_VF

## 概要
古橋研究室のV&F（動画編集部）が2021年5月に参加したハッカソンの作業管理リポジトリである。descriptionに「V＆F（動画編集部）」と明記されており、映像・動画制作チームによるハッカソン取り組みであることが明確。「ガチャガチャ」をテーマにしたカメラ機材（GoPro・OSMO・ふるはしくん）の3Dモデル制作と、発表・Medium記事・グラレコ等の成果物制作を並行して行った。CC BY 4.0ライセンスが付与されている。

## 主な活動・成果
- Issue #1（発表）: Natsumi917・Shiorinlouが発表担当としてアサイン。
- Issue #2（スクリプト作成）: 「発表のスクリプト作り」として起票。Natsumi917・Shiorinlouがアサイン。
- Issue #3（ガチャガチャっぽい説明書作ります）: rensanrenrenが担当。コメント1件あり。
- Issue #4（ふるはしくん）: Blenderでの「ふるはしくん」3Dモデル制作タスク。コメント3件あり。
- Issue #5（GoProをBlenderで作成）: GoPro（機種未定）の3DモデルをDimensionかBlenderで制作するタスク。コメント4件あり。
- Issue #6（ブレンダー作業）: rensanrenrenがBlender全般の作業を担当。
- Issue #7（グラレコ）: Babby168がグラフィックレコーディングを担当。
- Issue #8（OSMO）: DJI OSMOの3Dモデル制作タスク。Babby168・SahoYoshiharaがアサイン。コメント4件あり。
- Issue #9（アイデアぎめ）: rensanrenrenがアイデア出しを担当。
- Issue #10（スライド作成）: rensanrenrenがスライド担当。
- Issue #11（medium）: rensanrenrenがMedium記事執筆を担当。

## 使用技術・ツール
- Blender（3Dモデリング）
- Adobe Dimension（3Dモデリング候補）
- GitHub Issues（タスク管理・担当者アサイン）
- Medium（成果アウトプット媒体）
- CC BY 4.0 License

## 得られた知見
- V&F（映像制作）チームがハッカソンで3Dモデル制作（Blender・Dimension）に挑戦した事例として、映像・CG制作スキルのクロスオーバーが記録されている。カメラ機材（GoPro・OSMO）のガチャガチャ用3Dモデル制作という具体テーマは、実在機材の3D化による学習・展示活用モデルとして参照できる。ハッカソン参加チームを「発表・スクリプト・3D制作・グラレコ・記事執筆」に分業する役割設計も再利用可能。

## 未解決事項・課題
- 全Issueがopenのままで、各成果物の完成・提出状況が不明。ほとんどのIssueのbodyが空欄で詳細が把握できない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/Hackathon_VF
- Issues: https://github.com/furuhashilab/Hackathon_VF/issues

---
repo_name: "gsi_airportmap"
repo_url: "https://github.com/furuhashilab/gsi_airportmap"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-01-13"
repo_updated_at: "2021-01-18"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "地理院地図"
  - "ハッカソン"
  - "ドローン"
confidence: "high"
---

# gsi_airportmap

## 概要
古橋研究室ドローン部が「地理院地図ハッカソン」に参加した際の成果管理リポジトリである。descriptionに「地理院地図ハッカソン ドローン部」と明記されており、国土地理院が提供する地理院地図のAPIやデータを活用した空港・飛行関連地図アプリケーションの開発に取り組んだと推察される。リポジトリ名の「airportmap」からドローン飛行に関連する空港・飛行制限区域の可視化地図が成果物と考えられる。

## 主な活動・成果
- Issuesが存在せず、具体的な議論・作業記録は確認できない。
- 2021年1月13日に作成後、約5日間（1月18日まで）でコミットが行われており、ハッカソン期間中の集中作業と推察される。
- リポジトリサイズは765KBで、地図データまたはソースコードが格納されていると考えられる。

## 使用技術・ツール
- 地理院地図（国土地理院タイル・API）
- ドローン関連地理空間データ（空港・飛行制限区域等）
- GitHub（成果物管理）

## 得られた知見
- 地理院地図ハッカソンでは国土地理院の地図タイルやAPIを活用したWebGISアプリケーションを短期間で開発する形式が取られる。ドローン部としての参加テーマとして「空港周辺飛行制限区域の可視化」は、実際の飛行計画立案への応用価値が高く、国土地理院のオープンデータとドローン規制情報の組み合わせという独自性がある。

## 未解決事項・課題
- Issuesおよびコメントが存在せず、成果物の詳細・完成度・発表結果が不明。リポジトリ内のコードやデータを直接参照する必要がある。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/gsi_airportmap
- Issues: https://github.com/furuhashilab/gsi_airportmap/issues

---
repo_name: "ingress-mission-"
repo_url: "https://github.com/furuhashilab/ingress-mission-"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-01-18"
repo_updated_at: "2021-01-18"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "地理院地図"
  - "Ingress"
  - "位置情報ゲーム"
confidence: "high"
---

# ingress-mission-

## 概要
古橋研究室の位置情報ゲーム部が「地理院地図ハッカソン」に参加した際の作業管理リポジトリである。descriptionに「位置情報ゲーム部　地理院地図ハッカソン」と明記されており、位置情報ゲーム「Ingress」のミッション設計と地理院地図の組み合わせをテーマにした取り組みと推察される。Issue #5のタイトル「淵野辺駅でミッションを決める」から、青山学院大学相模原キャンパス最寄りの淵野辺駅周辺をフィールドにしたIngressミッションの企画・設計が中心作業であったと考えられる。

## 主な活動・成果
- Issue #1（テーマ決め）: sy7676・plinplin22・naoki2123の3名がアサインされ、チーム全体でテーマを協議。actionラベル付き。
- Issue #2（グラレコ作成）: naoki2123がグラフィックレコーディングを担当。documentationラベル付き。
- Issue #3（medium作成）: sy7676がMedium記事執筆を担当。documentationラベル付き。
- Issue #4（パワポ作成）: sy7676が発表用PowerPoint資料を担当。documentationラベル付き。
- Issue #5（淵野辺駅でミッションを決める）: plinplin22がアサイン。淵野辺駅周辺のIngressミッション設計という実作業タスク。actionラベル付き。
- 全Issueがマイルストーン「2020/1/18」に紐づいており、当日完結型のハッカソンとして実施。

## 使用技術・ツール
- Ingress（位置情報ゲーム・ミッション設計）
- 地理院地図（国土地理院タイル・API）
- Medium（成果アウトプット媒体）
- GitHub Issues（タスク管理・マイルストーン運用）
- グラフィックレコーディング

## 得られた知見
- 位置情報ゲーム（Ingress）のミッション設計に地理院地図を活用する手法は、地図リテラシー教育と位置情報技術の融合事例として興味深い。淵野辺駅周辺という具体的なフィールドを定めることで、地域の地理的特徴を活かしたミッションルートの企画が可能になる。ハッカソン当日に「テーマ決め→制作→発表資料・記事・グラレコ」という流れを当日完結型で行うタスク設計は再利用可能。

## 未解決事項・課題
- 全Issueがopenのままで成果の完成・発表結果が不明。Issueのbodyがすべて空欄のため、各タスクの詳細内容が記録されていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/ingress-mission-
- Issues: https://github.com/furuhashilab/ingress-mission-/issues

---
repo_name: "OSM-GSI"
repo_url: "https://github.com/furuhashilab/OSM-GSI"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-01-14"
repo_updated_at: "2021-01-17"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "OpenStreetMap"
  - "地理院地図"
  - "Wheelmap"
confidence: "high"
---

# OSM-GSI

## 概要
古橋研究室が地理院地図ハッカソンに参加した際の成果管理リポジトリである。リポジトリ名「OSM-GSI」からOpenStreetMap（OSM）と国土地理院（GSI）の組み合わせをテーマにした取り組みと推察される。Issue #1でWheelmapのデータ活用（車椅子アクセシビリティ情報のOSMベースのマッピングサービス）が議論されており、地理院地図上にバリアフリー・アクセシビリティ情報をオーバーレイ表示するアプリケーション開発が成果物と考えられる。

## 主な活動・成果
- Issue #1（WheelmapのデータをGitHub上に書くときのURLが何かを明らかにする）: f1kuni・YoshidaSuzuka・ky-38・mamiy1002の4名がアサイン。WheelmapのデータURL仕様の調査が中心課題。
- Issue #3（地理院地図のGitHubをフォークする）: ky-38が起票。地理院地図のGitHubリポジトリをフォークして開発基盤を整備するタスク。本文にサイバージャパン地理院地図のURLが共有されている（横浜市付近の地図タイル）。
- Issue #4（グラレコ作成）: mamiy1002が起票。グラフィックレコーディングの作成タスク。
- Issue #5（メディウム作成）: mamiy1002が起票。Medium記事の執筆タスク。

## 使用技術・ツール
- OpenStreetMap（OSMデータ・マッピング基盤）
- 地理院地図（国土地理院タイル・WebGIS）
- Wheelmap（OSMベースの車椅子アクセシビリティマッピングサービス）
- GitHub Pages / GSI CyberJapan（地図表示基盤）
- Medium（成果アウトプット媒体）

## 得られた知見
- WheelmapはOSMのアクセシビリティデータ（車椅子対応情報）を可視化するサービスであり、地理院地図と組み合わせることで日本の施設のバリアフリー情報を国産地図上に表示する新しい活用モデルが考えられる。地理院地図のGitHubリポジトリをフォークして独自レイヤーを追加する手法は、国土地理院のオープンデータ活用の基本パターンとして参照価値が高い。

## 未解決事項・課題
- 全Issueがopenのままで成果の完成・発表結果が不明。Wheelmap URLの特定（Issue #1）・地理院地図フォーク（Issue #3）の実施状況が記録されていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/OSM-GSI
- Issues: https://github.com/furuhashilab/OSM-GSI/issues

