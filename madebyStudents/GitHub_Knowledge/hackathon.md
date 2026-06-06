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

---
repo_name: "V-F_OnlineHackathon_Nov"
repo_url: "https://github.com/furuhashilab/V-F_OnlineHackathon_Nov"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-10-26"
repo_updated_at: "2021-11-10"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "hackathon"
  - "V&F"
  - "online-event"
confidence: "high"
---

# V-F_OnlineHackathon_Nov

## 概要
古橋研究室が主催・運営した11月のV&F（映像・フィールド）オンラインハッカソン用のリポジトリ。オンライン形式で実施されたハッカソンイベントの成果物や議論を管理することを目的として作成された。リポジトリ名の「V-F」は研究室内のV&F（Video & Field）活動を指すと考えられる。

## 主な活動・成果
- 2021年10月下旬から11月上旬にかけてオンラインハッカソンを実施
- Issues・コメントともに記録がなく、成果物の詳細は別途ドキュメントまたは外部サービスで管理されたと推定される
- リポジトリサイズが小さく（63KB）、主に告知・連絡・管理用途で活用されたと考えられる

## 使用技術・ツール
- GitHub（イベント管理・Issues運用）
- オンライン会議・コラボレーションツール（推定）

## 得られた知見
- ハッカソンの管理リポジトリとして GitHub を活用することで、参加者への情報共有や成果物のバージョン管理を一元化できる。ただし活動記録をIssuesに残さないと、後から活動内容を追跡・参照することが困難になるため、イベント記録のIssue活用が重要。

## 未解決事項・課題
特になし（Issueは0件、活動は完結している）

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/V-F_OnlineHackathon_Nov
- Issues: https://github.com/furuhashilab/V-F_OnlineHackathon_Nov/issues

---
repo_name: "hackathon2021-11_drone"
repo_url: "https://github.com/furuhashilab/hackathon2021-11_drone"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-11-01"
repo_updated_at: "2021-11-09"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "drone"
  - "hackathon"
  - "graphicrecording"
confidence: "high"
---

# hackathon2021-11_drone

## 概要
古橋研究室のドローン部が2021年11月に開催したハッカソンの成果物・タスク管理用リポジトリ。ドローンに関連するテーマでアイデアを出し合い、発表資料や記録物を制作することを目的としたイベントとして実施された。複数の学生メンバーがIssuesで役割分担しながら共同作業を進めた。

## 主な活動・成果
- Issue #1「グラレコ」：グラフィックレコーディングの作成（担当：MatsuyamaRan）
- Issue #2「発表用プレゼン」：ハッカソン発表スライドの作成（担当：yunapanpan12）
- Issue #3「Medium作成」：成果報告記事のMediumへの投稿（担当：naoki2123）
- Issue #4「イラスト作成」：ビジュアル素材の制作（複数名担当）
- Issue #5「案だし」：アイデア出しセッション（複数名担当）
- 全Issueがオープンのまま残っており、クローズ処理は行われなかった

## 使用技術・ツール
- GitHub Issues（タスク管理・役割分担）
- Medium（成果報告記事の公開）
- グラフィックレコーディング（視覚的議事録）
- プレゼンテーションツール（推定）

## 得られた知見
- ハッカソンのタスクをGitHub Issuesで担当者付きで管理することで、短期集中イベントでも役割分担を明確化できる。グラレコ・Medium記事・イラストといった多様なアウトプット形式を組み合わせることで、ドローン関連の成果を多角的に発信できる体制を構築できる。

## 未解決事項・課題
5件のIssueがすべてオープンのまま残っており、ハッカソン終了後にクローズ処理が行われなかった。成果物の最終状態はリポジトリ外（Medium等）で管理されたと推定される。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/hackathon2021-11_drone
- Issues: https://github.com/furuhashilab/hackathon2021-11_drone/issues

---
repo_name: "tokyoOSShakathon2021"
repo_url: "https://github.com/furuhashilab/tokyoOSShakathon2021"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2021-11-20"
repo_updated_at: "2022-09-15"
distilled_at: "2026-05-25"
language: null
homepage: "https://furuhashilab.github.io/tokyoOSShakathon2021/"
tags:
  - "unvt-portable"
  - "vector-tile"
  - "openstreetmap"
confidence: "high"
---

# tokyoOSShakathon2021

## 概要
古橋研究室（furuhashilab）が2021年11月〜12月に実施した「UNVT Portable」開発ハッカソンのリポジトリ。東京都のオープンデータ（ハザードマップ・消火栓位置・OSMデータ）をベクトルタイル化し、RaspberryPi上でオフライン動作するウェブ地図システムの構築を目標とした。GitHub Pagesでポータルサイトをホスティングし、成果発表まで行った。

## 主な活動・成果
- ハッカソンゴールの設定：八王子市ハザードマップ・東京消防庁消火栓データ・東京都全域OSMデータの3種をベクトルタイル化
- RaspberryPiにWebサーバを構築し、Mapbox GL JSでドローン空撮画像を含む重ね合わせウェブ地図を実装
- Mapbox GL JS → MapLibre GL JSへの置き換えによる完全オフライン化（Ethernet/Wi-FiAPいずれかで接続）を計画・着手
- M1 Pro MacへのHomebrew・tippecanoe・unvt/charitesのインストール手順をIssueでメンバー間共有
- GeoJSONからPBF（ベクトルタイル）を生成するtippecanoeコマンドのノウハウを整備
- ベクトルタイルレンダリング用style.jsonの作成方法・Maputnikの使い方をメンバー間で共有
- GitHub Pagesでハッカソンポータルサイトをホスティングしてdocsフォルダで管理
- ハッカソン終了後に反省Issueを作成し、次回改善を検討（未クローズ）

## 使用技術・ツール
- **ベクトルタイル生成**: tippecanoe、unvt/charites
- **スタイル編集**: Maputnik（style.json GUI editor）
- **地図レンダリング**: Mapbox GL JS → MapLibre GL JS
- **ホスティング**: RaspberryPi（オンライン/オフライン両対応）、GitHub Pages
- **データ形式**: GeoJSON、PBF（Protobuf Binary Format）、ベクトルタイル（MVT）
- **パッケージ管理**: Homebrew、npm（Node.js）
- **コラボレーション**: Mural、Google Spreadsheet
- **ライセンス**: CC0-1.0

## 得られた知見
- M1 ProチップのMacではHomebrewのインストールパスが `/opt/homebrew/` に変わるため、シェルのPATH設定を手動で追記する必要がある（`~/.zprofile`への`eval "$(brew shellenv)"`追記が必須）
- `npm install -g` はsudoなしでEACCESエラーになりやすく、グローバルインストール時はsudo付与か npmのprefix設定変更が必要
- tippecanoeでは `-z`（最大ズーム）と `-Z`（最小ズーム）の大文字小文字を混同しないよう注意が必要
- RaspberryPiを完全オフライン地図サーバとして運用する際は、Mapbox GL JSからMapLibre GL JSへの差し替えが必要（ライセンス・通信要件の違い）
- ハッカソンのタスク管理をGitHub Issuesで行うことで、作業ログ・ノウハウ共有・担当者管理を一元化できる

## 未解決事項・課題
- MapLibre GL JS への完全置き換えとRaspberryPiの完全オフライン化（Issue #7）が未クローズ
- 東京都全域OSMデータのベクトルタイル化（Issue #5）・消火栓データのベクトルタイル化（Issue #4）が未クローズ
- ハッカソンの反省点まとめ（Issue #17）が未クローズ（内容は未記載）
- style.jsonの作成ノウハウ共有（Issue #15）・Maputnik活用（Issue #14）が未クローズ

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/tokyoOSShakathon2021
- Issues: https://github.com/furuhashilab/tokyoOSShakathon2021/issues
- 関連サイト: https://furuhashilab.github.io/tokyoOSShakathon2021/

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
repo_name: "riverxsaunaxfuruhashilab"
repo_url: "https://github.com/furuhashilab/riverxsaunaxfuruhashilab"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2020-07-21"
repo_updated_at: "2020-07-27"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "hackathon"
  - "sauna"
  - "remote-work"
confidence: "medium"
---

# riverxsaunaxfuruhashilab

## 概要
「川とサウナと古橋ゼミ」をテーマに、古橋研究室のゼミ生が取り組んだハッカソン向け企画プロジェクトのリポジトリ。リモートワーク環境における川・サウナを組み合わせたアイデアを軸に、企画立案からハッカソン発表資料の作成まで進められた。Issues を使ってミーティング記録・タスク管理を行うゼミ型の軽量プロジェクト運営スタイルが採用されている。

## 主な活動・成果
- メンバー管理 Issue を設け、GitHub Assign でプロジェクト参加者を自己登録する運用を確立
- 第1回ミーティングを開催し、プロジェクトの方向性を議論
- テキストベースの企画書を作成（Issue #6）
- ハッカソン向け発表資料を作成・共有（Issue #8）
- 「リモートワークと川とサウナ」をテーマに再度ミーティングを実施し、コンセプトを深堀り（Issue #11）

## 使用技術・ツール
- GitHub Issues（タスク管理・ミーティング記録）
- GitHub Assign / Milestone（メンバー・進捗管理）
- テキストベース企画書（具体ツール不明）

## 得られた知見
- ハッカソンの企画フェーズでも GitHub Issues をミーティング記録やタスクトラッカーとして活用することで、アイデア段階から成果物（発表資料）への進行を可視化できる。「メンバー管理 Issue」パターンは参加意思表明と担当整理を同時に行えるシンプルかつ再現性の高い手法で、他のゼミプロジェクトにも横展開しやすい。

## 未解決事項・課題
- 全 Issues（5件）がオープンのまま残っており、企画書・発表資料の完成状況や最終的なハッカソン参加・結果が不明。リポジトリの更新が2020年7月末で停止しており、その後の活動記録が確認できない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/riverxsaunaxfuruhashilab
- Issues: https://github.com/furuhashilab/riverxsaunaxfuruhashilab/issues

---
repo_name: "2020_gps_ga-es"
repo_url: "https://github.com/furuhashilab/2020_gps_ga-es"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2020-06-26"
repo_updated_at: "2020-06-30"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "hackathon"
  - "location-based-game"
  - "gps-game"
confidence: "high"
---

# 2020_gps_ga-es

## 概要
2020年6月に開催されたハッカソン「位置ゲー部（GPS Game Analysis & Enhancement Study）」のリポジトリ。Pokémon GO・ドラゴンクエストウォーク・Ingress・Minecraft Earth（マイクラアース）といった GPS を活用した位置情報ゲームの仕組みやレベル設計を分析・研究し、2020年6月30日の発表に向けて各ゲーム担当者が分担して調査・資料化を行った。成果物は Medium の記事としてまとめられ、Issue に URL がリンクされている。

## 主な活動・成果
- Pokémon GO のレベル見直し・設定分析（Issue #1、Medium 記事化）
- ドラゴンクエストウォークのレベル設定分析（Issue #2、Medium 記事化）
- Minecraft Earth のレベル設定検討（Issue #3、Medium 記事化）
- Ingress の作業効率化分析（Issue #5、Medium 記事化）
- 各ゲームのドキュメント Issue として Ingress・マイクラアース・ドラクエウォーク・Pokémon GO の Medium 記事をそれぞれ Issue にリンク
- 2020/06/30 発表用 Google スライドを作成・Issue でリンク共有（Issue #6）
- Milestone「2020年6月30日」で全タスクを一元管理

## 使用技術・ツール
- GitHub Issues / Milestones（タスク管理・発表準備）
- Medium（調査・分析記事の公開）
- Google スライド（発表資料）
- 対象ゲーム：Pokémon GO・ドラゴンクエストウォーク・Ingress・Minecraft Earth

## 得られた知見
- 位置情報ゲームのレベル設計を比較分析することで、各ゲームが GPS・現実空間の移動をどのようにゲームプレイに組み込んでいるかの知見が得られる。担当者ごとにゲームを割り当て Medium 記事として成果を公開する形式は、ハッカソン内でのスコープ分割と成果物の外部発信を同時に実現する効果的なアプローチ。

## 未解決事項・課題
- 全 Issues（9件）がオープンのまま。Milestone「2020年6月30日」もクローズされておらず、発表後のフォローアップが記録されていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/2020_gps_ga-es
- Issues: https://github.com/furuhashilab/2020_gps_ga-es/issues

---
repo_name: "2020_YOKOZExSAUNA"
repo_url: "https://github.com/furuhashilab/2020_YOKOZExSAUNA"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2020-06-26"
repo_updated_at: "2020-06-26"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "hackathon"
  - "yokoze"
  - "sauna"
confidence: "medium"
---

# 2020_YOKOZExSAUNA

## 概要
埼玉県横瀬町とサウナを組み合わせた2020年6月のハッカソン企画リポジトリ。description は空だが、リポジトリ名と Issues の内容から、横瀬町の地域資源（ホルモンカレーなど）とサウナ体験を掛け合わせた観光・体験コンテンツの企画・制作を目指したプロジェクトと推定される。`riverxsaunaxfuruhashilab` リポジトリと同時期に立ち上げられており、関連する活動の一部とみられる。

## 主な活動・成果
- 横瀬ホルモンカレーガイドのレシピ動画作成タスクを Issue 化（Issue #4）
- 翌日（2020年6月30日）の発表に向けた準備 Issue を作成（Issue #7「明日で」）
- リポジトリへのコミットは作成から1日以内に完了しており、短期集中の活動が確認できる

## 使用技術・ツール
- GitHub Issues（タスク管理）
- 動画制作（レシピ動画、具体ツール不明）

## 得られた知見
- 地域の食文化（横瀬ホルモンカレー）をレシピ動画という形でコンテンツ化し、サウナと組み合わせることで地域観光に新しい体験価値を加えるアプローチは、地域連携型ハッカソンのコンセプト設計として参考になる。短期間（数日）で企画から発表資料まで仕上げる際は、Issues で成果物単位のタスクを立てておくと抜け漏れを防ぎやすい。

## 未解決事項・課題
- 2件の Issues がオープンのまま。レシピ動画の完成・公開状況が不明。リポジトリへの更新が2020年6月26日の1日のみで、発表後の記録が残っていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/2020_YOKOZExSAUNA
- Issues: https://github.com/furuhashilab/2020_YOKOZExSAUNA/issues

---
repo_name: "hackathon-grareco"
repo_url: "https://github.com/furuhashilab/hackathon-grareco"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2020-12-21"
repo_updated_at: "2020-12-21"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "graphic-recording"
  - "gsi-japan"
  - "illustration"
confidence: "medium"
---

# hackathon-grareco

## 概要
古橋研究室（furuhashilab）によるハッカソン向けグラフィックレコーディング（グラレコ）活動を管理するリポジトリ。国土地理院（GSI）のTwitter投稿内容をイラスト化・視覚化するプロジェクトとして立ち上げられた。発表資料の作成とグラレコ制作の2本柱で活動が進められた。

## 主な活動・成果
- 国土地理院Twitterの専門用語・投稿内容をイラスト化するタスクを設定し、複数メンバー（yukiohgishi・Ayaka0324・kahorusato）がアサインされて作業を分担
- グラフィックレコーディング（グラレコ）の制作をissueとして独立管理し、担当者を明示して進行
- ハッカソン発表用スライド・資料の作成をissueで追跡管理

## 使用技術・ツール
- GitHub Issues（タスク・進捗管理）
- グラフィックレコーディング（手描き・デジタルイラスト等による視覚的議事録）
- 国土地理院（GSI）Twitter（情報ソース）
- プログラミング言語：なし（language: null）

## 得られた知見
- ハッカソンのような短期集中イベントでも、GitHubのIssueを活用してグラレコや発表資料といった非コード成果物のタスク管理を行うことで、役割分担と進捗の可視化が実現できる。専門的な地理情報（国土地理院コンテンツ）をイラスト化・グラレコ化することで、難解な概念を一般向けに伝えるビジュアルコミュニケーション手法として応用可能。

## 未解決事項・課題
全3件のissue（国土地理院Twitterのイラスト化・グラレコ・発表用資料）がいずれもオープンのままクローズされておらず、成果物の最終的な完成・確認状況が不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/hackathon-grareco
- Issues: https://github.com/furuhashilab/hackathon-grareco/issues


---
repo_name: "chatgpt4plateau"
repo_url: "https://github.com/furuhashilab/chatgpt4plateau"
genre: "hackathon"
genre_label: "ハッカソン・ハンズオン"
repo_created_at: "2023-07-20"
repo_updated_at: "2023-08-03"
distilled_at: "2026-05-25"
language: "Game Maker Language"
homepage: null
tags:
  - "ChatGPT"
  - "PLATEAU"
  - "Code Interpreter"
confidence: "high"
---

# chatgpt4plateau

## 概要
2023年8月3日開催「生成AIによるコード生成とCode Interpreterの活用ハンズオン with Project PLATEAU」用の公開リポジトリ。神奈川県相模原市のPLATEAU CityGML/GeoJSON/3DTiles/MVTおよびDRONEBIRDによる空撮GeoTIFF・3D Point Cloud (LAS) をサンプルデータとして配布し、ChatGPT Code InterpreterでのGISデータ加工を試すハンズオンを実施。

## 主な活動・成果
- 相模原市のPLATEAUデータをCityGML、GeoJSON、3DTiles、MVT、ShapeZIPで多形式提供
- 建築物・都市計画決定・道路・土地利用・地形・洪水浸水想定区域・土砂災害警戒区域モデルを網羅
- DRONEBIRD空撮 (GeoTIFF + LAS点群) のサンプルも併載
- 33件のIssue (ハンズオン参加者の成果共有)
- ISSUE_TEMPLATEを整備し、参加者が試行結果を統一フォーマットで投稿できる仕組みを構築
- 7 stars獲得 (担当群中トップ)

## 使用技術・ツール
- ChatGPT Code Interpreter (GPT-4)
- PLATEAU CityGML / GeoJSON / 3DTiles / MVT
- DRONEBIRD GeoTIFF / LAS点群
- GitHub Issue Templates
- CC0-1.0 ライセンス

## 得られた知見
ハンズオン参加者の試行結果をIssueテンプレで投稿させる仕組みは、(1)成果の見える化、(2)後続学習者のサンプル集積、(3)講師側のフィードバック効率化、を同時に達成する。生成AI×GISハンズオンでは「サンプルデータの多形式同梱」が再現性確保の鍵。

## 未解決事項・課題
- リポジトリのprimary languageが "Game Maker Language" と誤判定されている (実態はサンプルデータ)
- ハンズオン以降の継続的な事例追加更新が止まっている

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/chatgpt4plateau
- Issues: https://github.com/furuhashilab/chatgpt4plateau/issues


---
repo_name: "DMP_hackathon2022_teamAandB"
repo_url: "https://github.com/furuhashilab/DMP_hackathon2022_teamAandB"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2022-01-01"
repo_updated_at: "2022-12-31"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "hackathon"
  - "dmp"
  - "team-collaboration"
confidence: "low"
---

# DMP_hackathon2022_teamAandB

## 概要
2022年に開催された DMP (Digital Mapping Party / Data Management Plan 系) ハッカソンにおける、チーム A とチーム B の合同成果物を格納するリポジトリ。古橋研究室ゼミ内のチーム単位の開発・プロトタイピング成果をまとめる場所として運用された。リポジトリ HTML 取得時にコンテンツが取得できず、詳細は限定的。

## 主な活動・成果
- 2022年開催のハッカソンにおけるチームA・チームB の合同成果物の集約
- ゼミ内チーム間コラボレーションの実証
- 成果物のリポジトリ単位でのアーカイブ化

## 使用技術・ツール
- GitHub (リポジトリベースの成果物管理)
- (詳細不明: README/言語情報を取得できず)

## 得られた知見
ハッカソンの成果を A/B 両チーム合同のリポジトリで保存することで、後年の振り返りや他ゼミ生への引き継ぎが行いやすい。研究室イベントの成果物リポジトリは命名規則 (`{event}_{year}_{teams}`) を統一すると検索性が高い。

## 未解決事項・課題
リポジトリ取得時にコンテンツが空またはアクセス制限のため内容詳細が不明。README やコミット履歴の整備が必要。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/DMP_hackathon2022_teamAandB
- Issues: https://github.com/furuhashilab/DMP_hackathon2022_teamAandB/issues


---
repo_name: "furulab2022hackathon_kitten"
repo_url: "https://github.com/furuhashilab/furulab2022hackathon_kitten"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2022-09-30"
repo_updated_at: "2022-10-03"
distilled_at: "2026-05-25"
language: null
homepage: "https://docs.google.com/spreadsheets/d/1zZuaiRNXYX1onp3-dPjoYrhQy6Qd0072-fQ8OwN72j0/edit"
tags:
  - "Ukraine"
  - "Georeferencing"
  - "OSINT"
confidence: "high"
---

# furulab2022hackathon_kitten

## 概要
古橋研究室2022年9月ウクライナ・ハッカソン参加チーム「kitten」のリポジトリ。テーマは、ロシアによるウクライナ侵攻状況に関する未アーカイブの衛星画像・ドローン空撮映像・3Dデータ等を収集し、地理座標と紐付け(ジオリファレンス)してデジタル証跡を蓄積すること。成果はGoogleスプレッドシートに集約されている。

## 主な活動・成果
- 未アーカイブの衛星/ドローン画像のジオリファレンス作業
- 3Dデータ等関連コンテンツの収集とメタデータ整理
- 最終成果物Googleスプレッドシートへの集約 (1zZuaiRNXYX1onp3-...)
- メンバー: OZAWA TAIYU, MOTOYA KAWANO

## 使用技術・ツール
- Google Earth Pro / Google Spreadsheet
- 衛星画像 / ドローン映像 / 3Dデータ
- ジオリファレンス手法 (画像オーバーレイ)
- Markdown / GitHub Issues
- CC-BY-4.0 ライセンス

## 得られた知見
紛争地のオープンソース・インテリジェンス(OSINT)では、SNS等で拡散される映像を「いつ・どこで撮影されたか」を地理座標に紐付ける「ジオリファレンス」作業が、事実関係の検証と歴史記録の双方で重要。Googleスプレッドシートを共通成果物プラットフォームとすることで、複数チームの並行作業を集約しやすい。

## 未解決事項・課題
ジオリファレンス精度の検証や、収集データの長期アーカイブ方針が課題として残る可能性が高い。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/furulab2022hackathon_kitten
- Issues: https://github.com/furuhashilab/furulab2022hackathon_kitten/issues
- 関連サイト: https://docs.google.com/spreadsheets/d/1zZuaiRNXYX1onp3-dPjoYrhQy6Qd0072-fQ8OwN72j0/edit

---
repo_name: "furulab2022hackathon_NERV"
repo_url: "https://github.com/furuhashilab/furulab2022hackathon_NERV"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2022-09-27"
repo_updated_at: "2022-10-01"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "Ukraine"
  - "KMZ"
  - "TimeAnimation"
confidence: "high"
---

# furulab2022hackathon_NERV

## 概要
古橋研究室2022年9月ウクライナ・ハッカソン参加チーム「NERV」のリポジトリ。前線抽出班として、自衛隊公式TwitterからUkraine情勢の画像をダウンロードし、Google Earth Pro上でジオリファレンスして時系列付きの前線ラインKMZファイルを生成する作業を実施。成果物は `UkraineFrontLines_JSDF_latest.kmz` (TimeStamp付) として公開。

## 主な活動・成果
- 自衛隊公式Twitter発信画像のジオリファレンス
- Google Earth ProでのオーバーレイとTimeStamp付前線ライン作成
- 時間アニメーション対応KMZファイルの配布
- GitHub Projects (UkraineHackathon_NERV_project) でのタスク管理
- メンバー: Urara Nagashima, Kohki Kikuchi

## 使用技術・ツール
- Google Earth Pro
- KML/KMZ (`<TimeStamp>` 要素による時系列表現)
- Twitter (情報ソース: 自衛隊公式)
- GitHub Projects (issue 36件)
- CC-BY-4.0 ライセンス

## 得られた知見
KML/KMZの`<TimeStamp>`要素を用いることで、Google Earthの時間スライダー機能と連動した前線変化アニメーションを低コストで実現可能。SNS発信のスクリーンショットを公的ソースとして検証・ジオリファレンスするワークフローは、現代的なOSINT手法のひとつとして再利用性が高い。2名1組のペア体制とSlack #seminar2022での進捗共有がハッカソン運営に有効。

## 未解決事項・課題
issues 36件・コミット50件と活発だがコメント未取得で詳細論点は要追跡。前線データの精度検証、情報ソース(自衛隊Twitter)の信頼性評価が継続課題。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/furulab2022hackathon_NERV
- Issues: https://github.com/furuhashilab/furulab2022hackathon_NERV/issues


---
repo_name: "furulab2022hackathon_NW"
repo_url: "https://github.com/furuhashilab/furulab2022hackathon_NW"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2022-10-03"
repo_updated_at: "2022-10-03"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "satellite-imagery"
  - "drone"
  - "geo-reference"
confidence: "medium"
---

# furulab2022hackathon_NW

## 概要
furuhashilab内ハッカソンにおけるNWチーム (Naoya Uematsu, Wataru Yoshida) の作業用リポジトリ。ロシアによるウクライナ侵攻に関連する未アーカイブの衛星画像・ドローン映像・3Dデータ等を収集し、ジオリファレンスを付与する課題に取り組んだ。災害・紛争地域の地理空間情報をオープンに整理することを目的とする。

## 主な活動・成果
- ハッカソンチーム「NW」の活動拠点としてリポジトリを開設
- 衛星・ドローン画像・3DデータをOSINT的に収集する作業フレームを定義
- ジオリファレンス手法に関する初期検討を実施

## 使用技術・ツール
- GitHub (ドキュメンテーション・コラボレーション)
- CC-BY-4.0 ライセンス採用
- 衛星画像・ドローン画像・3Dデータ (ジオリファレンス対象)
- OSINT 的ワークフロー

## 得られた知見
研究室内ハッカソンを少人数チーム単位で並走させ、それぞれ独立したリポジトリに成果物・議論を集約する運用パターンが有効。地理参照付きの紛争地マッピングは、データ供給源 (衛星/UAV) の信頼性とライセンス整理が初動の鍵となる。

## 未解決事項・課題
README は課題定義のみで成果物コミットがなく、ジオリファレンスの実装フロー・最終アウトプットが公開されていない。複数チーム間の成果統合プロセスが不明確。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/furulab2022hackathon_NW
- Issues: https://github.com/furuhashilab/furulab2022hackathon_NW/issues


---
repo_name: "furulab2022hackathon_plusn"
repo_url: "https://github.com/furuhashilab/furulab2022hackathon_plusn"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2022-09-26"
repo_updated_at: "2022-09-26"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "satellite-imagery"
  - "drone"
  - "geo-reference"
confidence: "medium"
---

# furulab2022hackathon_plusn

## 概要
furuhashilab内ハッカソン「+n」チーム (ShogoHirasawa, halgraphic) の作業用リポジトリ。NWチームと同様、ロシアのウクライナ侵攻に関連する未アーカイブの衛星画像・ドローン映像・3Dデータを収集してジオリファレンスを行うテーマに取り組んだ。

## 主な活動・成果
- 「+n」チームの作業拠点としてリポジトリ運用 (7コミット)
- 衛星/UAV映像・3Dデータの収集とジオリファレンスのワークフロー検討
- CC-BY-4.0 ライセンスでのオープンコラボ体制を構築

## 使用技術・ツール
- GitHub (リポジトリ運用)
- 衛星画像・ドローン画像・3Dデータ
- CC-BY-4.0 ライセンス
- OSINT 系データソース

## 得られた知見
同一テーマを複数チーム (NW / +n) が並行して扱うことで、収集アプローチ・ジオリファレンス手法の比較検討が可能になる。チームごとに独立した小さなリポジトリを切る運用は、ハッカソン形式と相性が良い。

## 未解決事項・課題
コミット数が少なく、成果物 (ジオリファレンス済データ・ビューア等) の公開には至っていない。チーム間の成果共有・統合方針が明文化されていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/furulab2022hackathon_plusn
- Issues: https://github.com/furuhashilab/furulab2022hackathon_plusn/issues


---
repo_name: "furulab2022hackathon_ramen"
repo_url: "https://github.com/furuhashilab/furulab2022hackathon_ramen"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2022-09-28"
repo_updated_at: "2022-10-04"
distilled_at: "2026-05-25"
language: "Python"
homepage: null
tags:
  - "Ukraine"
  - "Georeferencing"
  - "PythonScript"
confidence: "high"
---

# furulab2022hackathon_ramen

## 概要
古橋研究室2022年ウクライナ・ハッカソン参加チーム「ramen」のリポジトリ。kittenチームと同様に未アーカイブの衛星/ドローン画像と3Dデータを収集・ジオリファレンスする活動に加え、画像へクレジット文字を自動付与するPythonスクリプト `Automated-credit-input.py` を独自開発した点が特徴。

## 主な活動・成果
- ジオリファレンス対象の衛星画像 (`satelliteimageries/`) 収集
- Pillowを用いた画像クレジット自動挿入Pythonスクリプト開発 (`Automated-credit-input.py`)
- ファイル選択ダイアログによる複数画像一括処理機能
- メンバー: Ibuki Shibayama, Sota Suzuki, Yasuda Haruka, Shogo Hirasawa

## 使用技術・ツール
- Python 100% (PIL/Pillow + Tkinter ファイル選択)
- 衛星画像/ドローン画像/3Dデータ
- ジオリファレンス手法
- macOS環境での開発・検証
- CC-BY-4.0 ライセンス

## 得られた知見
ハッカソンでは「定型作業の手動繰り返し」がボトルネックになりがちで、これを小さなPythonスクリプトで自動化するだけでも生産性が大幅向上する。クレジット文字の位置を絶対座標で指定する実装は画像サイズ非互換を生むため、相対座標化が次の改善ポイントとなる(README自身が指摘)。

## 未解決事項・課題
- テキスト挿入位置を絶対座標→相対座標へ変更すること
- macOSのみでの動作確認のため、Windowsでの検証が未実施
- フォント調整 (READMEに「Upcoming updates」として明記)
- issues 27件と多く、コメント未取得で議論詳細は追跡余地あり

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/furulab2022hackathon_ramen
- Issues: https://github.com/furuhashilab/furulab2022hackathon_ramen/issues

---
repo_name: "Gachagacha_Hackathon_2023_-teamA"
repo_url: "https://github.com/furuhashilab/Gachagacha_Hackathon_2023_-teamA"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2023-04-15"
repo_updated_at: "2023-04-19"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "hackathon"
  - "blender-3d"
  - "character-design"
confidence: "high"
---

# Gachagacha_Hackathon_2023_-teamA

## 概要
古橋研究室ガチャガチャ・ハッカソン2023のチームA成果物リポジトリ。研究室マスコット「ふるはしくん」の冬仕様3Dモデル、ピカチュウ風マップデザイン、研究室活動紹介グラフィックレコーディング (グラレコ) の3つを成果物として開発。Blenderによる3Dキャラクター制作とマップカートグラフィを横断する内容。

## 主な活動・成果
- ふるはしくん冬仕様 Blenderモデル (.blend) 制作
- ピカチュウ風マップデザインの企画
- 古橋研究室活動紹介グラレコの作成
- 4件のissueで進行管理、10コミットで成果物を集約

## 使用技術・ツール
- Blender (3Dモデリング、.blendファイル)
- Adobe Illustrator (グラレコ・マップデザイン想定)
- GitHub (CC-BY-4.0ライセンス)

## 得られた知見
ハッカソン形式で3Dキャラクター制作 (Blender) とカートグラフィ表現 (マップデザイン) と図解 (グラレコ) を並走させることで、研究室の多面的活動を一括して可視化できる。Blenderファイルをそのままレポジトリに置くことで、後輩のリミックス素材として再利用しやすい。

## 未解決事項・課題
ピカチュウ風マップとグラレコは見出しのみで成果物がコミットされておらず、ハッカソン後の成果ドキュメント化が不十分。3Dモデルのレンダリング結果や用途も明示されていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/Gachagacha_Hackathon_2023_-teamA
- Issues: https://github.com/furuhashilab/Gachagacha_Hackathon_2023_-teamA/issues


---
repo_name: "Gachagacha_Hackathon_2023_teamB"
repo_url: "https://github.com/furuhashilab/Gachagacha_Hackathon_2023_teamB"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2023-04-15"
repo_updated_at: "2023-04-21"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "hackathon"
  - "gachagacha"
  - "prototype-design"
confidence: "high"
---

# Gachagacha_Hackathon_2023_teamB

## 概要
古橋研究室で開催されたガチャガチャ・ハッカソン2023のチームB成果物リポジトリ。ジオ展用ガチャ (48mmカプセル) と芦ヶ久保駅ASTABA用ガチャ (48mm/75mmカプセル) の2案を企画・プロトタイピングした。物理プロダクト (カプセルトイ) を題材とする珍しいハッカソンの記録である。

## 主な活動・成果
- 4/18(火) 成果発表、4/21(金) ジオ展でガチャガチャ販売
- 「ジオ展用ガチャ」と「芦ヶ久保駅ASTABA用ガチャ」の2系統を企画
- プロトタイプフォルダにデザイン案を格納
- 5件のissueで企画議論を進行

## 使用技術・ツール
- ガチャガチャカプセル (48mm / 75mm)
- 物理プロトタイピング (3Dモデル想定)
- GitHub Issues (CC-BY-4.0ライセンス)

## 得られた知見
短期間ハッカソンで物理プロダクト (ガチャガチャ) を企画から販売まで完結させるワークフロー。展示会 (ジオ展) や地域 (横瀬町) という具体的な利用シーンを設定することでアイデアの方向性が定まりやすい。価格帯 (100円/500円/1000円) に応じたカプセルサイズの使い分けが実用的。

## 未解決事項・課題
README記載が最小限で、プロトタイプの最終デザインや販売実績、参加者の振り返りが文書化されていない。物理在庫管理や継続販売の仕組みは未整備。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/Gachagacha_Hackathon_2023_teamB
- Issues: https://github.com/furuhashilab/Gachagacha_Hackathon_2023_teamB/issues


---
repo_name: "GeoGachaHackathon_youth_202211"
repo_url: "https://github.com/furuhashilab/GeoGachaHackathon_youth_202211"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2022-11-15"
repo_updated_at: "2022-12-09"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "hackathon"
  - "3d-print"
  - "gacha"
confidence: "high"
---

# GeoGachaHackathon_youth_202211

## 概要
2022年11月、古橋研ゼミ内サークル「youth」が参加した GeoGachaHackathon の成果物リポジトリ。48mmカプセルに収まる、目標コスト50円/個のプロトタイプを作る制約のもと、青山学院大学相模原キャンパス B棟の 3D モデルを 3 分割し凹凸ジョイント付き STL として 3D プリント、ガチャガチャ景品化した。

## 主な活動・成果
- 相模原キャンパス B棟の 3D モデル (Ibuki Shibayama 2022卒論成果) を 3 分割し STL 出力
- 各パーツに同幅の凹凸を付け、欠番でも連結遊びを可能にする設計
- Blender からスケール 1.0 / 0.75 の 2 系統で STL を書き出し、0.75 でプロトタイプ印刷
- 11/15 キックオフ → 11/22 コアタイム → 11/29 成果発表の 2 週間ハッカソン進行

## 使用技術・ツール
- Blender (3D モデリング / STL エクスポート)
- 3D プリンタ (FDM 推定)
- 48mm ガチャカプセル
- CC-BY-4.0 ライセンス

## 得られた知見
卒論の建物 3D モデルを「連結可能なミニチュア」として再利用することで、研究成果の社会的展示価値を高められる。コスト @50円/個・48mm カプセル制約は厳しいが、形状分割設計と凹凸ジョイントによりコレクション性も生まれる。Blender スケール (0.75 等) で印刷時間・材料費と造形精度のバランス調整が肝要。

## 未解決事項・課題
量産時の塗装・組立工程、印刷失敗率の低減、@50円目標達成のための材料最適化。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/GeoGachaHackathon_youth_202211
- Issues: https://github.com/furuhashilab/GeoGachaHackathon_youth_202211/issues


---
repo_name: "Mapathon4Turkey"
repo_url: "https://github.com/furuhashilab/Mapathon4Turkey"
genre: "hackathon"
genre_label: "ハッカソン・マッパソン"
repo_created_at: "2023-02-08"
repo_updated_at: "2023-02-28"
distilled_at: "2026-05-25"
language: null
homepage: "https://tasks.hotosm.org/projects/14233"
tags:
  - "マッパソン"
  - "クライシスマッピング"
  - "OSM"
confidence: "high"
---

# Mapathon4Turkey

## 概要
2023年2月のトルコ・シリア大地震を受けて開催された、トルコのクライシスマッピングを目的とするマッパソンに関するリポジトリ。HOT (Humanitarian OpenStreetMap Team) のTasking Manager上のプロジェクト #14233 を対象に、参加者がOSMへ建物・道路をトレースし、人道支援活動を地図面でサポートした。

## 主な活動・成果
- マッパソンポスター (.ai/.png) を制作・公開し参加者を募集
- Certificationテンプレート (.ai/.png) を制作し参加者へ修了証を発行
- 工程表.md・応募フォーム・プレゼン資料 (Google Slides) を整備しイベント運営を一本化
- HOTタスクマネージャと連動した実マッピング作業を主導

## 使用技術・ツール
- Adobe Illustrator (.ai) (ポスター・修了証制作)
- HOT Tasking Manager
- OpenStreetMap (OSM)
- Google Forms / Google Slides
- Markdown (工程表)

## 得られた知見
災害発生からマッパソン開催までを2〜3週間で立ち上げるには、(1)ポスター・修了証等のクリエイティブ、(2)応募〜参加〜証明発行のフォーム導線、(3)HOTタスクID等の対象指定、をGitHub一箇所に集約するのが効率的。Illustratorソースを公開することで再利用・派生開催にも繋がる。

## 未解決事項・課題
- 開催後の成果 (マッピング件数等) のサマリードキュメントが残されていない
- 1 Issueのみで議論ログの蓄積が限定的

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/Mapathon4Turkey
- Issues: https://github.com/furuhashilab/Mapathon4Turkey/issues
- 関連サイト: https://tasks.hotosm.org/projects/14233


---
repo_name: "plateauhackathon2023"
repo_url: "https://github.com/furuhashilab/plateauhackathon2023"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2023-07-06"
repo_updated_at: "2023-07-20"
distilled_at: "2026-05-25"
language: null
homepage: "https://furuhashilab.github.io/plateauhackathon2023/"
tags:
  - "PLATEAU"
  - "ストーリーテリング"
  - "Re:Earth"
confidence: "high"
---

# plateauhackathon2023

## 概要
青山学院大学・フェリス女学院大学合同で開催された「PLATEAU ストーリーテリングハッカソン 2023」の公式リポジトリ。Project PLATEAUの3D都市モデルとRe:Earthのストーリーテリング機能を活用し、参加11チームが「自分の想いとPLATEAUを組み合わせるストーリー」を制作。7/6キックオフ→7/13ハンズオン→7/19提出→7/20発表という2週間のスケジュールで実施された。

## 主な活動・成果
- 11チームの作品 (富嶽三十六景江戸巡り、Re:Earth Museum、奈阿、ラテグミ他) をGitHub Pagesで公開
- 各賞 (最優秀賞、PLATEAU賞、古橋賞、岡田賞、コンテンツ賞) を選定
- Re:Earth公式Discordチャンネル (#hackathon2023_ja) でリアルタイム支援
- 個人/チーム登録〜成果物提出までGoogle Forms中心の運用
- 第三者著作物は許諾不要ライセンスのみ使用するルールを徹底

## 使用技術・ツール
- Project PLATEAU (3D都市モデル)
- Re:Earth / PLATEAU VIEW 2.0 (ビューワ)
- GitHub Pages (作品公開)
- Discord (コミュニケーション)
- Google Forms (応募/提出)
- embed機能 (作品の外部埋め込み)

## 得られた知見
3D都市モデル×ストーリーテリングのハッカソンでは、(1)Re:Earthのstory機能のような既製ツールに乗ることで2週間という短期間でも全11チームが成果物を完成可能、(2)成果物を全てGitHub Pagesで公開させる規約により、ハッカソン後も継続的に作品が閲覧される資産が残る、という運用パターンが有効。

## 未解決事項・課題
- 1チーム「奈阿」がRe:Earthのみ公開でGitHubリポジトリ化が未完
- 提出後の作品継続改善や外部公開プラットフォーム化は次年度課題

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/plateauhackathon2023
- Issues: https://github.com/furuhashilab/plateauhackathon2023/issues
- 関連サイト: https://furuhashilab.github.io/plateauhackathon2023/


---
repo_name: "Tochizi-hai-OpenDataHackathon"
repo_url: "https://github.com/furuhashilab/Tochizi-hai-OpenDataHackathon"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2022-01-01"
repo_updated_at: "2022-12-31"
distilled_at: "2026-05-25"
language: "HTML"
homepage: "https://furuhashilab.github.io/Tochizi-hai-OpenDataHackathon/"
tags:
  - "open-data"
  - "hackathon"
  - "unvt-portable"
confidence: "high"
---

# Tochizi-hai-OpenDataHackathon

## 概要
都知事杯オープンデータハッカソン参加チーム (古橋研) のリポジトリ。プレゼン資料・ドローン空撮データのオープン化・Mapbox Style 仕様日本語ドキュメント完成・Raspberry Pi 上のオフライン地図サーバ (UNVT Portable) 開発を成果物として束ねる、ハッカソン期間の活動拠点として機能した。

## 主な活動・成果
- ドローン空撮データのオープン化 (dronebird/oam_sagamihara20211215aoyamauniv1155mapconcierge00arw01)
- Mapbox Style Specification の日本語ドキュメント完成 (StyleSpecification4mapbox)
- Raspberry Pi 上で動くオフライン地図サーバ UNVT Portable の開発
- 12 件の Issue で UNVT Portable の Wi-Fi/DHCP/Ethernet/FTP 等の動作検証を実施
- Mapbox GL JS → MapLibre GL JS への置き換え検証 (完全オフライン化)
- 東京都ベクトルタイルと八王子市ハザードマップ + ドローン空撮の重ね合わせ

## 使用技術・ツール
- HTML (100%) / Mapbox GL JS / MapLibre GL JS
- UNVT Portable (Raspberry Pi)
- Mapbox Style Specification
- ドローン空撮 (OpenAerialMap 互換)
- Speaker Deck (発表資料配信)

## 得られた知見
ハッカソンのリポジトリは「成果物リンク集 + Issue による作業ログ」という構成にしておくと、当日の試行錯誤 (Wi-Fi が繋がらない、DHCP の IP が割り振られない、FTP の使い方など) がそのまま再現手順書化する。Mapbox GL JS から MapLibre GL JS への切替検証もハッカソン期間の自然な選択肢として記録できている。

## 未解決事項・課題
UNVT Portable で「PC から Wi-Fi 経由で繋ぐと指定 DHCP の IP が割り振られない」という Issue が残存。MapLibre 置き換え後の運用安定性、ローカル Wi-Fi AP 化の永続化方法も継続検討事項。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/Tochizi-hai-OpenDataHackathon
- Issues: https://github.com/furuhashilab/Tochizi-hai-OpenDataHackathon/issues
- 関連サイト: https://furuhashilab.github.io/Tochizi-hai-OpenDataHackathon/


---
repo_name: "tokyoOSShakathon2022"
repo_url: "https://github.com/furuhashilab/tokyoOSShakathon2022"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2022-08-23"
repo_updated_at: "2022-08-23"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "open-data"
  - "vector-tile"
  - "tokyo"
confidence: "high"
---

# tokyoOSShakathon2022

## 概要
東京都知事杯オープンデータハッカソン2022における、チーム「UNVT」の公開リポジトリ。東京都および関東甲信越エリアを対象に、ベクトルタイルベースマップ、地形ラスタタイル、衛星画像、避難所、行政界などの各種データセットを生成・ホスティングし、防災ユースケースの可視化に取り組んだ。First Stage発表用スライドへのリンクも含む。

## 主な活動・成果
- 関東甲信越のベクトルタイルベースマップ、地形RGB Elevationタイル、衛星画像タイル、行政界タイルを作成
- 東京都の避難所ベクトルタイル (UNVT_for_Tokyo-to) を派生リポジトリで公開
- GitHub Pages 上に複数のテーマ別 Web マップをホスティング (Kanto_basemap, Tokyo_Terrain-map, Tokyo_satellit_map, etc.)
- First Stage 発表資料を Google Slides で公開

## 使用技術・ツール
- UN Vector Tile Toolkit (UNVT)
- ベクトルタイル / ラスタタイル (zxy 形式)
- RGB Elevation (地形タイル)
- GitHub Pages (ホスティング)
- CC0-1.0 License

## 得られた知見
オープンデータハッカソンにおいては、テーマ別 (基盤地図・地形・衛星・避難所・行政界) にリポジトリを分割し、それぞれ GitHub Pages で個別公開してから index 集約する構成が、短期開発・発表で扱いやすい。ベクトルタイル + ラスタタイルの組み合わせで防災ユースを横断的に表現できる。

## 未解決事項・課題
「東京都のハザードマップベクトルタイル」と「ハザードマップホスティング」は未完了 (チェックボックス未消化)。複数の GitHub Pages 配信を統合したフロントUIは未整備。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/tokyoOSShakathon2022
- Issues: https://github.com/furuhashilab/tokyoOSShakathon2022/issues


---
repo_name: "youth_UN-EC_OSS4SDG_hachathon2022"
repo_url: "https://github.com/furuhashilab/youth_UN-EC_OSS4SDG_hachathon2022"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2022-10-18"
repo_updated_at: "2022-10-23"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "PLATEAU"
  - "OpenStreetMap"
  - "YouthMappers"
confidence: "high"
---

# youth_UN-EC_OSS4SDG_hachathon2022

## 概要
UN-EC (国連経済委員会) OSS4SDG ハッカソン2022における、YouthMappers AGU・古橋研究室・青山学院大学チームの作業リポジトリ。テーマはPLATEAU 3D都市モデルデータをOpenStreetMapにインポートすることで、対象地域は東京都東村山市。CC-BY-4.0ライセンスで成果を共有している。

## 主な活動・成果
- 東村山市のPLATEAUデータをOSMへインポートするワークフロー策定
- インポートマニュアル草案(nyampire氏Qiita記事)に基づく作業手順検証
- インポート作業のパフォーマンス測定
- メンバー: Ibuki Shibayama, Sota Suzuki, Shogo Hirasawa

## 使用技術・ツール
- PLATEAU (3D都市モデル)
- OpenStreetMap (OSM)
- yuuhayashi/citygml-osm 変換ツール
- GitHub Issues / Markdown

## 得られた知見
PLATEAU→OSMインポートは既存OSSコンバータと整備されたインポートマニュアルの組み合わせで実行可能だが、自治体単位での実証が品質確保に重要。YouthMappersのような若手マッパーコミュニティとUN系ハッカソンの連携が、SDGsデータ整備の継続的推進力となる。

## 未解決事項・課題
TODOにて「マニュアル完成」「パフォーマンス検証」「東村山市データのOSM本番反映」が未完項目として残されている。issues 9件はコメント未取得で詳細議論内容は要追跡。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/youth_UN-EC_OSS4SDG_hachathon2022
- Issues: https://github.com/furuhashilab/youth_UN-EC_OSS4SDG_hachathon2022/issues


mapboxjpmeetup

概要

本リポジトリは、古橋研究室（furuhashilab）が主催する「mapbox/OpenStreetMap meetup in Japan」の運営管理用公開リポジトリである。2019年10月から2020年2月にかけて計4回開催されたMeetupイベントの準備・運営・広報に関するタスクをGitHub Issueで管理している。ゲスト登壇者の調整、会場設営、学生ボランティアスタッフの確保、メディア掲載管理、今後のテーマ企画など、イベント運営全般を対象としている。

主な活動・成果

- 計4回のMeetupを開催（#01: 2019年10月、#02: 2019年11月、#03: 2019年12月、#04: 2020年2月）
- Issue #1：第2回で学生スタッフが集まらず、OSGeo JapanメンバーやSoftBankチームの支援で乗り切った。継続性の課題として記録（未クローズ）
- Issue #2：会場（WeWork日比谷パークフロント）のプロジェクター接続改善のためEZ Cast Proの導入を検討（未クローズ）
- Issue #3：会場の定員上限を超えた参加希望者・遠隔参加者向けのライブ配信を検討→クローズ済み
- Issue #4：Mapbox本家向けにMeetup紹介ブログを日本語で執筆→完了・クローズ
- Issue #5・6：第3回のハンズオン・Meetupの準備タスク（テーマ決定、資料作成、会場予約、ゲスト登壇者・LT調整）→完了・クローズ
- Issue #7：第4回に向けた国土地理院（藤村氏）との登壇調整→完了・クローズ
- Issue #8：遅刻参加者の増加による運営スタッフの負担増加への対応として、18:30以降の入場を原則禁止とするルールを策定
- Issue #9：新型コロナウイルス対応として、ケータリングを個別包装に変更することを決定
- Issue #10：今後のMeetupテーマ・ゲスト候補を古橋私案としてリスト化（CARTO、DECK.GL、Mapillary、ヤマップ、Tier IV、国境なき医師団等）
- Issue #11：メディア・ブログ掲載リストを管理（GeoNews、INTERNET Watch、Medium等）

使用技術・ツール

- Mapbox / Mapbox GL JS：地図プラットフォーム・レンダリングライブラリ
- OpenStreetMap（OSM）：オープン地理空間データ
- GitHub Issues：イベント運営タスク管理
- HackMD：共同編集メモ・資料作成
- EZ Cast Pro：会場プロジェクターのワイヤレス接続ツール
- WeWork 日比谷パークフロント：イベント会場
- Medium：ブログ発信プラットフォーム

得られた知見

- GitHub Issueをイベント運営のタスク管理に活用するパターンは、技術系コミュニティMeetupにおいて透明性の高い運営を実現できる。クローズ済みIssueが完了タスクのアーカイブとして機能し、引き継ぎや振り返りにも有効。
- 学生ボランティアスタッフの確保は継続開催の最大のボトルネックになりやすい。早期から募集告知チャネルを多様化し、外部コミュニティ（OSGeo Japan等）との連携体制を事前に構築しておくことが重要。
- 遅刻参加者対応のルール化（18:30以降入場禁止）は、運営スタッフが登壇内容を聴けない問題を解消するための実践的な工夫として参考になる。
- 新型コロナウイルス（2020年2月時点）への対応として、ケータリングの個別包装化という現場レベルの判断をIssueに残したことで、感染症対応の意思決定プロセスが記録されている。

未解決事項・課題

- Issue #1（学生スタッフ不足）、#2（プロジェクター接続）、#8（遅刻者対応ルール）、#9（コロナ対応）、#10（今後のテーマ・ゲスト案）、#11（広報資料管理）の計6件がオープンのまま。2020年2月以降の活動記録がなく、コロナ禍による活動停止の可能性が高い。

参考リンク

- リポジトリ: https://github.com/furuhashilab/mapboxjpmeetup
- Issues: https://github.com/furuhashilab/mapboxjpmeetup/issues
- 関連ブログ（なぜMapbox Meetupを主催するか）: https://link.medium.com/Nno2Albd81
- GeoNews掲載記事: https://geo-news.jp/archives/1176
---
repo_name: "2025Mapathon"
repo_url: "https://github.com/furuhashilab/2025Mapathon"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2025-06-14"
repo_updated_at: "2025-08-02"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "mapathon"
  - "OpenStreetMap"
  - "YouthMappers"
confidence: "high"
---

# 2025Mapathon

## 概要
古橋研究室（AGU YouthMappers）が2025年8月に開催した、日本・タイ間の学生による国際共同マッパソン「Japan-Thailand YouthMappers Joint Mapathon with TomTom 2025 Aug.」の企画・運営リポジトリである。青山学院大学の学生とタイ・Srinakharinwirot大学の学生が連携し、与論島（日本）とHua Hin（タイ）をOpenStreetMap上でマッピングすることで、異文化間協力とグローバルな地図作成スキルの育成を目的としている。TomTomが企業パートナーとして参画した。

## 主な活動・成果
- イベント概要をIssue #5に整理：2025年8月9日20:00〜22:00（JST）、Zoom開催、参加者はAGU YouthMappers 8名＋Srinakharinwirot学生15名＋Kiran氏
- HOT Tasking Managerを使用したマッピング対象地域を決定：与論島（Project #25614）とHua Hin（Project #26175）
- TomTomとのコミュニケーション（Issue #3）：ゲストトーク・フィードバックセッション・技術QA・ノベルティ提供・SNS発信などの協力内容を検討。「ふるはしくんGPT」を活用して提案内容を整理
- Srinakharinwirot大学とのコミュニケーション窓口をIssue #2として設置
- マッパソンの目的・意義（Issue #7）とHua Hin選定理由（Issue #6）について議論を継続中
- 当日使用スライドおよび参加者応募フォームをGoogle DocsおよびGoogle Formsで作成・共有

## 使用技術・ツール
- OpenStreetMap（マッピング対象プラットフォーム）
- HOT Tasking Manager（タスク管理・マッピング分担）
- Zoom（オンライン開催プラットフォーム）
- Google Slides（当日スライド）
- Google Forms（参加者応募フォーム）
- ChatGPT（「ふるはしくんGPT」としてイベント企画の壁打ちに活用）
- プログラミング言語：なし（language: null）

## 得られた知見
- 企業（TomTom）をマッパソンに巻き込む際は「短めのゲストトーク＋参加者マッピング成果へのフィードバック」が最も教育効果が高く、参加者のモチベーション向上にもつながる。
- 対照的な2地域（地図化不十分な離島と発展した都市部）を同一イベントで扱うことで、参加者が多様な地理的文脈に対応できる実践的スキルを習得できる。
- ChatGPT等のAIツールをイベント企画の壁打ち相手として活用することで、企業への提案文草案や役割整理を効率化できる。

## 未解決事項・課題
- マッパソンの目的（Issue #7）とHua Hin選定理由（Issue #6）の議論がOpenのまま
- Srinakharinwirot大学とのコミュニケーション（Issue #2）にコメントがなく、連携状況が不明
- 当日の進行（タイムライン）に「未定」部分が残っており、最終化が必要

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/2025Mapathon
- Issues: https://github.com/furuhashilab/2025Mapathon/issues

---
repo_name: "YouthMappersAGU_Mapathon"
repo_url: "https://github.com/furuhashilab/YouthMappersAGU_Mapathon"
genre: "hackathon"
genre_label: "ハッカソン"
repo_created_at: "2024-12-03"
repo_updated_at: "2024-12-09"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "mapathon"
  - "openstreetmap"
  - "youthmappers"
confidence: "high"
---

# YouthMappersAGU_Mapathon

## 概要
本リポジトリは、青山学院大学・古橋研究室のYouthMappers AGUが主催するマッパソン（Mapathon）の企画・調査・運営ナレッジを蓄積するために作成された。マッパソンとは、ボランティアが集まりOpenStreetMap等のオープンな地図プラットフォームを用いて協力して地図を作成するイベントであり、災害・人道支援地域を対象とした地図データの充実を目的としている。CC BY 4.0 ライセンスで公開されている。

## 主な活動・成果
- Issue #1（マッパソンとは）：マッパソンの定義・目的・作業手順を文献（Missing Maps）をもとに整理。麗澤大学主催の「6th Annual Humanitarian Mapathon」など国内事例も紹介
- Issue #2（マッパソンを開催するのに必要なこと）：目的設定・開催形式・ツール準備・参加者募集・スケジュール・当日運営・事後フォローアップの9ステップを体系的にまとめた開催チェックリストを作成
- Issue #3（古橋ゼミが過去開催・参加したマッパソン）：研究室の過去のマッパソン参加・開催履歴の収集（情報収集中・未完）
- Issue #4（開催メンバーを集める方法）：国際会議での告知・SNS活用（Facebook・Twitter・Instagram）・パートナーシップ構築・初心者向けワークショップ設置の4手法を整理
- Issue #5（他団体が企画しているマッパソンの例）：他団体の事例収集（担当変更あり・調査継続中）

## 使用技術・ツール
- OpenStreetMap（OSM）
- JOSM / iD Editor（マッピング編集ツール）
- Tasking Manager（HOT）
- Zoom / Slack / Google Meet（オンライン開催用）
- Google フォーム（参加登録）
- GitHub Issues（企画・調査内容の管理）

## 得られた知見
- マッパソン開催には「目的設定→形式決定→ツール準備→参加者募集→当日運営→事後共有」の一連のワークフローが必要であり、これをGitHub Issuesで分担・文書化することで、次回開催時の引き継ぎコストを大幅に削減できる。
- 初心者の参加障壁を下げるには、事前マニュアル・ワークショップ・フレンドリーな雰囲気づくりが有効であり、SNSと教員経由の告知を組み合わせることで参加者数を拡大できる。

## 未解決事項・課題
- 全5件のIssueがオープンのまま
- 過去のマッパソン履歴（Issue #3）および他団体事例（Issue #5）の情報収集が未完了
- 実際の開催日程・結果についての記録がリポジトリ内に見当たらない

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/YouthMappersAGU_Mapathon
- Issues: https://github.com/furuhashilab/YouthMappersAGU_Mapathon/issues
- 
