---
repo_name: "InformationSociety2021AGU"
repo_url: "https://github.com/furuhashilab/InformationSociety2021AGU"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-06-15"
repo_updated_at: "2021-06-15"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "情報社会論"
  - "オープンライセンス"
  - "教育"
confidence: "high"
---

# InformationSociety2021AGU

## 概要
青山学院大学・古橋研究室が2021年度に開講した「情報社会論」の授業管理リポジトリである。GitHub Issuesを課題提出プラットフォームとして活用し、学生が各週の課題成果物（図・URL等）をコメントとして投稿、そのPermalinkをGoogle Classroomに提出する運用が採られた。情報社会における著作権・ライセンス・オープンデータといったテーマを扱う講義内容が中心となっている。

## 主な活動・成果
- Issue #1（6/15課題）: Apache・GPL3.0・MIT・WTFPL・None・The Unlicensedの6種類のソフトウェアライセンスの関係性を図化する課題。32件のコメントが寄せられ、学生が各自の図をIssueに投稿した。
- Issue #3（6/22課題）: 「正しい引用」「剽窃」「盗用」「盗作」「オマージュ」「パロディ」の違いを図にまとめる課題。33件のコメントが集積された。
- Issue #4・#5（6/29課題）: 「政府標準利用規約（第2.0版）」を採用しているウェブサイトや配布データを調査し、URLと概要を投稿する課題。2つのIssueに分散して受け付ける形式が取られた（計34件のコメント）。
- Issue #8（7/29）: スクリーンショットのみの投稿で詳細不明の課題提出と思われる。
- GitHub IssuesとGoogle Classroomを連携させた課題管理フローが確立された。

## 使用技術・ツール
- GitHub Issues（課題提出・ディスカッション基盤）
- Google Classroom（課題管理・提出確認）
- 画像ファイル添付（図化課題の成果物共有）

## 得られた知見
- GitHub Issuesを授業課題の提出先として使うことで、学生の成果物が一覧性高く蓄積され、クラス全体での相互参照が可能になる。PermalinkをLMS（Google Classroom等）にリンク提出する運用は、GitHubに不慣れな学生のGit/GitHub習熟にも寄与する実践的な教育設計である。
- ライセンス（Apache・GPL・MIT等）やオープンデータ規約（政府標準利用規約）を「図化」させる課題設計は、抽象的な法的概念を学生に能動的に整理させる有効な手法である。

## 未解決事項・課題
- 全Issueがopenのままクローズされておらず、最終的な課題完了確認フローが明確でない。
- Issue #8はスクリーンショットのみで内容が不明瞭であり、課題の趣旨が把握しきれない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/InformationSociety2021AGU
- Issues: https://github.com/furuhashilab/InformationSociety2021AGU/issues

---
repo_name: "slcmd"
repo_url: "https://github.com/furuhashilab/slcmd"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-06-15"
repo_updated_at: "2021-06-15"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "slack"
  - "cli"
  - "command"
confidence: "low"
---

# slcmd

## 概要
古橋研究室が作成したリポジトリで、リポジトリ名「slcmd」からSlack連携またはコマンドライン操作に関するツール・スクリプトと推察される。descriptionは設定されておらず、Issuesも存在しないため詳細な用途は不明。MIT Licenseが付与されており、OSS的な位置付けと考えられる。

## 主な活動・成果
- Issuesが存在せず、具体的な活動・議論の記録は確認できない。
- リポジトリサイズが1KBと極小であり、初期コミットのみの状態と推察される。
- MIT Licenseが適用されている。

## 使用技術・ツール
- MIT License
- 言語・フレームワーク等は未確認（languageフィールドがnull）

## 得られた知見
- リポジトリ名「slcmd」はSlack + commandの略と考えられ、SlackのSlash CommandやBot連携を試みた可能性がある。Slack APIを活用したコマンドツールの雛形リポジトリとして参照できる可能性がある。

## 未解決事項・課題
- descriptionが未設定、Issuesが空、コードもほぼ存在しないため、リポジトリの目的・実装内容の把握が困難。用途の明確化とREADMEの整備が必要。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/slcmd
- Issues: https://github.com/furuhashilab/slcmd/issues

---
repo_name: "qrdots"
repo_url: "https://github.com/furuhashilab/qrdots"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-06-02"
repo_updated_at: "2021-06-02"
distilled_at: "2026-05-25"
language: "HTML"
homepage: null
tags:
  - "QRコード"
  - "ドット"
  - "HTML"
confidence: "medium"
---

# qrdots

## 概要
古橋研究室が taisukef/qrdots をフォークしたリポジトリである。元リポジトリはQRコードをドット（点）で表現するHTML/JavaScriptツールと推察され、MIT Licenseで公開されている。フォーク直後に活動の記録はなく、元リポジトリの調査・活用を目的とした参照フォークの可能性が高い。

## 主な活動・成果
- taisukef/qrdots（HTML言語、MIT License）をフォーク。
- フォーク後のIssues・コミット・独自の変更は確認できない。
- 元リポジトリはQRコードのドット表現に関するツールで、GitHub Pages上で公開されていた（元リポジトリにhas_pages: true）。

## 使用技術・ツール
- HTML（元リポジトリの主要言語）
- MIT License
- GitHub Pages（元リポジトリで利用）

## 得られた知見
- QRコードをドット状に視覚的にカスタマイズするHTMLツールとして、地図や位置情報と組み合わせたQRコード表現の応用可能性がある。古橋研究室がフォークした背景として、地図系プロジェクトや発表物へのQRコード埋め込みニーズが考えられる。

## 未解決事項・課題
- フォーク後の利用目的・カスタマイズ内容が一切記録されておらず用途不明。元リポジトリ（https://github.com/taisukef/qrdots）を参照することで詳細な実装内容を確認できる。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/qrdots
- Issues: https://github.com/furuhashilab/qrdots/issues
- フォーク元: https://github.com/taisukef/qrdots

---
repo_name: "Up3date"
repo_url: "https://github.com/furuhashilab/Up3date"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-09-17"
repo_updated_at: "2021-09-17"
distilled_at: "2026-05-25"
language: "Python"
homepage: null
tags:
  - "CityJSON"
  - "Blender"
  - "3D都市モデル"
confidence: "high"
---

# Up3date

## 概要
古橋研究室が cityjson/Up3date をフォークしたリポジトリである。Up3dateはCityJSON v1.0形式でエンコードされた3D都市モデルをBlenderにインポート・編集・エクスポートするためのBlenderアドオンで、ジオメトリ・属性・セマンティクスを保持したまま操作できる。古橋研究室は3D都市モデルや地理空間データの研究文脈でこのツールを参照・活用するためにフォークしたと推察される。

## 主な活動・成果
- cityjson/Up3date（Python、MIT License、star数76）をフォーク。
- フォーク後のIssues・独自コミットは確認できない。
- フォーク元（cityjson/Up3date）はCityJSON関連ツールとして現在も活発に開発・メンテナンスされている（2024年3月に最終プッシュ）。
- トピックタグとして `3dcitymodels`・`blender`・`cityjson`・`etl` が付与されている（フォーク元より）。

## 使用技術・ツール
- Python（主要言語）
- Blender（3DCGソフトウェア・アドオン実行環境）
- CityJSON v1.0（3D都市モデルのオープンフォーマット）
- MIT License

## 得られた知見
- CityJSONはOGC標準のCityGMLをJSONで表現した軽量フォーマットであり、BlenderアドオンであるUp3dateを使うことで、建物・道路・植生などの3D都市モデルをGUI上で直接編集・可視化できる。PLATEAU等の日本の3D都市モデルデータの編集・検証用途にも転用可能。

## 未解決事項・課題
- フォーク後の利用目的・カスタマイズ内容が記録されておらず用途不明。フォーク元（https://github.com/cityjson/Up3date）を参照することで最新の実装・Issueを確認できる。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/Up3date
- Issues: https://github.com/furuhashilab/Up3date/issues
- フォーク元: https://github.com/cityjson/Up3date

---
repo_name: "museo"
repo_url: "https://github.com/furuhashilab/museo"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-06-07"
repo_updated_at: "2021-06-07"
distilled_at: "2026-05-25"
language: "JavaScript"
homepage: "https://museo.app"
tags:
  - "パブリックドメイン"
  - "美術館"
  - "画像検索"
confidence: "high"
---

# museo

## 概要
古橋研究室が chasemccoy/museo をフォークしたリポジトリである。Museoは世界の主要美術館（メトロポリタン美術館・シカゴ美術館等）のパブリックドメイン画像を横断検索できるWebツールで、JavaScript製のOSSとして公開されている（元リポジトリは star数105、2024年11月まで活発に更新）。古橋研究室は地図・空間情報・オープンデータの文脈でこのパブリックドメイン画像ツールを参照・活用するためにフォークしたと推察される。

## 主な活動・成果
- chasemccoy/museo（JavaScript、star数105）をフォーク。
- フォーク後のIssues・独自コミットは存在しない。
- 元リポジトリは https://museo.app として公開されており、現在も稼働中。

## 使用技術・ツール
- JavaScript（主要言語）
- museo.app（Webアプリケーション）
- 各美術館API（メトロポリタン美術館・シカゴ美術館等のオープンAPI）

## 得られた知見
- Museoは複数の主要美術館（Met・Art Institute of Chicago等）のパブリックドメイン画像APIを統合した横断検索ツールであり、授業資料・地図デザイン・プレゼン素材等にライセンスフリーの美術画像を活用したい場合に有用。パブリックドメイン画像の一括検索という用途は、古橋研究室の教育・デザイン系プロジェクトへの素材調達に転用可能。

## 未解決事項・課題
- フォーク後の利用目的・カスタマイズ内容が記録されておらず用途不明。最新の機能・対応美術館一覧は元リポジトリ（https://github.com/chasemccoy/museo）またはhttps://museo.appを参照。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/museo
- Issues: https://github.com/furuhashilab/museo/issues
- 関連サイト: https://museo.app
- フォーク元: https://github.com/chasemccoy/museo

---
repo_name: "pytorch-Deep-Learning"
repo_url: "https://github.com/furuhashilab/pytorch-Deep-Learning"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-02-17"
repo_updated_at: "2021-02-17"
distilled_at: "2026-05-25"
language: "Jupyter Notebook"
homepage: "https://atcold.github.io/pytorch-Deep-Learning"
tags:
  - "deep-learning"
  - "pytorch"
  - "jupyter-notebook"
confidence: "high"
---

# pytorch-Deep-Learning

## 概要
古橋研究室が Atcold/NYU-DLSP20（NYU Deep Learning Spring 2020）をフォークしたリポジトリである。元リポジトリはニューヨーク大学のYann LeCun・Alfredo Canziani両氏によるPyTorchを用いたディープラーニング講義の教材で、Jupyter Notebookにより実装例と講義資料が公開されている（star数6,806、fork数2,234の主要OSSコース教材）。古橋研究室はAI・機械学習の教育・研究文脈での参照・活用を目的としてフォークしたと推察される。

## 主な活動・成果
- Atcold/NYU-DLSP20（Jupyter Notebook、star数6,806）をフォーク。
- フォーク後のIssues・独自コミットは存在しない。
- 元リポジトリは https://atcold.github.io/NYU-DLSP20/ でコース全体が公開されており、現在も更新が継続されている。

## 使用技術・ツール
- PyTorch（ディープラーニングフレームワーク）
- Jupyter Notebook（実装・演習環境）
- Python（主要実装言語）
- deep-learning・neural-nets・pytorch（トピックタグ）

## 得られた知見
- NYU Deep Learning（Atcold/NYU-DLSP20）はPyTorchによるニューラルネットワーク・CNNなどの実装を網羅した世界的に参照される教材であり、古橋研究室のAI・機械学習学習の出発点として参照できる。地理空間データへのディープラーニング適用（衛星画像分類・点群処理等）を検討する際の基礎教材として位置づけられる。

## 未解決事項・課題
- フォーク後の利用目的・カスタマイズ内容が記録されておらず用途不明。最新の講義資料・Notebookは元リポジトリ（https://github.com/Atcold/NYU-DLSP20）を参照。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/pytorch-Deep-Learning
- Issues: https://github.com/furuhashilab/pytorch-Deep-Learning/issues
- 関連サイト: https://atcold.github.io/pytorch-Deep-Learning
- フォーク元: https://github.com/Atcold/NYU-DLSP20

---
repo_name: "temp"
repo_url: "https://github.com/furuhashilab/temp"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-12-22"
repo_updated_at: "2021-01-28"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "一時作業"
  - "スクラッチパッド"
  - "作業用"
confidence: "high"
---

# temp

## 概要
古橋研究室の一時作業用リポジトリである。descriptionに「一時作業用レポジトリ」と明記されており、恒久的なプロジェクトではなく試験・検証・一時保管を目的として作成された。Issuesは存在せず、2020年12月から2021年1月にかけて短期間利用されたのみで、その後は実質的に休眠状態にある。

## 主な活動・成果
- Issuesが存在せず、具体的な活動記録は確認できない。
- 作成から約1か月後（2021年1月）に最終プッシュが行われており、短期の一時作業に使用された。
- リポジトリサイズは471KBと一定量のデータが存在するため、何らかのファイル・スクリプトが格納されている可能性がある。

## 使用技術・ツール
- 言語・フレームワーク等は未確認（languageフィールドがnull）

## 得られた知見
- 研究室規模のGitHub Organization運用では、一時作業・検証用リポジトリをあらかじめ用意しておくことで、本番リポジトリを汚染せずに実験や一時保管ができる。ただし長期放置になりやすいため、定期的なアーカイブや削除ポリシーを設けることが望ましい。

## 未解決事項・課題
- リポジトリの内容（格納ファイル・スクリプト）が不明。一時用途のため削除・アーカイブが検討されてよい状態にある。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/temp
- Issues: https://github.com/furuhashilab/temp/issues

---
repo_name: "citygml-osm"
repo_url: "https://github.com/furuhashilab/citygml-osm"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-12-15"
repo_updated_at: "2021-12-15"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "CityGML"
  - "OpenStreetMap"
  - "geodata-conversion"
confidence: "high"
---

# citygml-osm

## 概要
CityGML形式の3D都市モデルデータをOpenStreetMap（OSM）形式に変換するためのツール。国土交通省のPLATEAU等で提供されるCityGMLデータをOSMエコシステムで活用できるようにすることを目的としている。古橋研究室は yuuhayashi/citygml-osm をフォークして参照・研究利用している。

## 主な活動・成果
- フォーク元（yuuhayashi/citygml-osm）においてCityGML→OSM変換ロジックの開発・継続メンテナンスが行われている
- フォーク元は Star 21件・Fork 3件を獲得し、2025年12月まで更新が継続
- 古橋研究室フォーク自体にはIssuesが無効化されており、独自の活動記録はなく、参照・調査目的のフォークと考えられる

## 使用技術・ツール
- Game Maker Language（フォーク元の主要言語として記録されているが、XML/GML処理ツールである可能性が高い）
- CityGML（ISO 19107準拠の3D都市モデル標準フォーマット）
- OpenStreetMap（OSM）データフォーマット

## 得られた知見
- CityGMLはPLATEAUなど日本の公的3D都市データで広く使われているが、GISツールやWebマップへの直接利用には変換が必要であり、OSM形式へのコンバーターは研究・シビックテック両面で実用性が高い。
- フォーク元の language が「Game Maker Language」と誤検出されているケースは、バイナリや特殊拡張子ファイルをGitHubが誤判定した可能性があり、言語情報の扱いには注意が必要。

## 未解決事項・課題
フォーク元では16件のオープンIssueが残存しており、変換精度・属性マッピング・対応CityGMLバージョンなどに関する議論が継続中と推定される。古橋研究室フォークでの独自開発・改良は現時点では確認されない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/citygml-osm
- Issues: https://github.com/furuhashilab/citygml-osm/issues

---
repo_name: "github"
repo_url: "https://github.com/furuhashilab/github"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-11-18"
repo_updated_at: "2021-11-18"
distilled_at: "2026-05-25"
language: null
homepage: "https://kaityo256.github.io/github/"
tags:
  - "git"
  - "github-education"
  - "version-control"
confidence: "high"
---

# github

## 概要
GitおよびGitHubの基本操作を学ぶための演習教材リポジトリ。kaityo256/github（Star 618件）をフォークして古橋研究室が教育目的で参照している。コミット・ブランチ・プルリクエスト・コンフリクト解消など、研究室での共同開発に必要なGitワークフローを体系的に習得することを目的としている。

## 主な活動・成果
- kaityo256 による HTML形式の演習テキストを研究室教育に活用
- フォーク元は Star 618件・Fork 19件を持つ広く利用される教材として継続的に更新（2026年2月まで更新）
- CC BY 4.0 ライセンスのもとで自由に利用・改変可能な教材として整備
- 古橋研究室フォーク自体にはIssuesが無効化されており、独自の改変・議論は行われていない

## 使用技術・ツール
- Git（バージョン管理）
- GitHub（リモートリポジトリ・Pull Request・Issues）
- HTML（教材フォーマット）
- GitHub Pages（教材の公開）

## 得られた知見
- 既存の高品質なOSS教材（Star数の多いリポジトリ）をフォークして研究室の学習環境に取り込むことで、教材開発コストをかけずに即戦力となる演習環境を整備できる。CC BY 4.0 のような開放的なライセンスの教材を積極的に活用することが、研究室教育の効率化につながる。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/github
- Issues: https://github.com/furuhashilab/github/issues
- 関連サイト: https://kaityo256.github.io/github/

---
repo_name: "miraiclass4iwate"
repo_url: "https://github.com/furuhashilab/miraiclass4iwate"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-07-12"
repo_updated_at: "2021-11-03"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "SDGs"
  - "civic-tech"
  - "map-education"
confidence: "high"
---

# miraiclass4iwate

## 概要
岩手町のSDGs未来都市共創プロジェクト「未来の教室」の一環として実施された、「まちを楽しむ地図を作る」ワークショッププロジェクト。地域の子どもや住民が自分たちのまちを題材にWebマップを作成することを通じて、地理情報技術とSDGsへの関心を育てることを目的としている。CC BY 4.0 ライセンスで公開されている。

## 主な活動・成果
- 2021年7月〜11月にかけてワークショップを実施し、岩手町のまちを題材にした地図制作を進めた
- Issue #1「Screenshots」にてワークショップ成果のスクリーンショット（地図UI画面）が共有・記録された
- mapconcierge（古橋教授）がIssueを作成・管理し、2件のコメントによる議論が行われた
- リポジトリサイズが73MBと比較的大きく、地図データや画像素材が含まれていると推定される

## 使用技術・ツール
- Webマッピング技術（地図作成ワークショップ用、具体的ライブラリは未確認）
- GitHub Issues（成果スクリーンショットの共有・記録）
- CC BY 4.0（オープンライセンス）

## 得られた知見
- SDGs・地域共創文脈でのWebマップ制作ワークショップは、教育と実践を兼ねたアウトリーチ活動として有効。GitHubリポジトリをワークショップの成果アーカイブとして活用することで、活動の透明性と再利用性を確保できる。CC BY 4.0 での公開は、他自治体や教育機関への横展開を促進する。

## 未解決事項・課題
Issue #1「Screenshots」が1件オープンのままになっており、正式なクローズ処理が行われていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/miraiclass4iwate
- Issues: https://github.com/furuhashilab/miraiclass4iwate/issues

---
repo_name: "citygml-tools-1"
repo_url: "https://github.com/furuhashilab/citygml-tools-1"
genre: "other"
genre_label: "その他"
repo_created_at: "2022-01-26"
repo_updated_at: "2022-01-19"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "citygml"
  - "cityjson"
  - "3d-city-model"
confidence: "high"
---

# citygml-tools-1

## 概要
CityGMLファイルを処理するためのツール群をまとめたリポジトリ。citygml4j/citygml-tools（Star 159件）をフォークしたもので、CityGMLデータのバリデーション・変換・統計取得などの処理機能を提供する。古橋研究室におけるPLATEAU等の3D都市モデルデータ活用のための調査・研究目的でフォークされたと考えられる。

## 主な活動・成果
- citygml4j organization が開発・保守するCityGML処理ツール群を研究室環境に取り込んだ
- フォーク元（citygml4j/citygml-tools）は2026年5月まで活発にメンテナンスが継続されており、Star 159件・Fork 26件の実績を持つ
- 古橋研究室フォークではIssuesが無効化されており、独自の開発・議論は行われていない
- Apache License 2.0 のもとで自由に利用・改変・再配布が可能

## 使用技術・ツール
- Java（フォーク元の主要言語）
- CityGML（3D都市モデル標準フォーマット）
- CityJSON（CityGMLのJSON代替フォーマット）
- citygml4j（Java向けCityGML処理ライブラリ）
- Apache License 2.0

## 得られた知見
- citygml-tools は CityGML 2.0/3.0 両対応の実用的なCLIツールであり、PLATEAUデータの前処理や形式変換に活用できる。Java製のため環境依存が少なく、研究室の複数環境での利用に適している。フォーク元が2026年現在も活発に更新されており、CityGML 3.0 対応など最新仕様への追従も期待できる。

## 未解決事項・課題
特になし（furuhashilab フォーク自体にIssuesなし）

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/citygml-tools-1
- Issues: https://github.com/furuhashilab/citygml-tools-1/issues

---
repo_name: "freetothemap4boe"
repo_url: "https://github.com/furuhashilab/freetothemap4boe"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-07-22"
repo_updated_at: "2021-10-26"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "GIGAスクール"
  - "map-education"
  - "filtering-whitelist"
confidence: "high"
---

# freetothemap4boe

## 概要
GIGAスクール構想で小中学生に配布されたデジタル端末（ChromebookやiPad）における地図サービスへのアクセス制限問題を調査・改善するための公開リポジトリ。教育委員会のフィルタリング設定によって地理院地図・OpenStreetMap・Google Maps等の地図教育に不可欠なサービスがブロックされているケースを全国から収集し、ホワイトリスト化・改善提案につなげることを目的としている。「一億総伊能化」を掲げた古橋研究室の社会実装・アドボカシー活動の一環。

## 主な活動・成果
- 所沢市・調布市・岩手町・千葉市・東京都港区・埼玉県朝霞市・川越市など複数自治体のアクセス制限状況をIssueとして収集・記録
- Issue #1「所沢市 Chromebook がアクセスできないウェブサイトメモ」：地理院地図・OSM・Google Maps・Mapboxなど主要地図サービスが軒並みブロックされていることを確認
- Issue #3「岩手町のChromebookの状況」：Google Mapsはブロックされるが地理院地図・OSMはアクセス可能という地域差を記録
- Issue #6「千葉市の状況」：フィルタリングツールとして i-FILER が使用され、ホワイトリスト管理が教育委員会ではなく市役所担当課にあることを確認
- Issue #7「所沢市は夏休み期間限定アクセス制限」：時期によって制限内容が変わるケースを記録
- Issue #9「提案」：ホワイトリスト方式を基本とし、Google FormとSpreadsheetで市民提案・公開する運用案を策定
- Issue #11「一億総伊能化ホワイトリスト v0.6」：地理院地図・PLATEAU・RESAS・OSM・Google Mapsなど推奨ホワイトリストをまとめた最新版を公開
- Issue #4「所沢市教育委員会への報告」：教育委員会・市議会議員への働きかけをタスクとして設定（8コメントの活発な議論）
- 文科省ガイドライン（令和3年5月版）のフィルタリング方針を調査・整理（Issue #5）

## 使用技術・ツール
- GitHub Issues（自治体別アクセス状況の収集・管理）
- Google Form / Google Spreadsheet（ホワイトリスト提案の収集・公開、提案）
- Chromebook / iPad（対象の配布端末）
- i-FILER（千葉市で確認されたフィルタリングツール）
- CC BY 4.0 / ODC BY / ODbL（収集データのオープンライセンス化提案）

## 得られた知見
- GIGAスクール端末のフィルタリングは自治体・時期・端末種別によって大きく異なり、地理院地図・PLATEAU・RESASなど行政が提供する地図サービスでさえブロックされるケースがある。ホワイトリスト方式を採用する自治体では、教育委員会ではなく別の担当課がリストを管理しているケースがあり、働きかけ先の特定が重要。GitHub Issuesを自治体別ラベルで分類することで、分散した情報を効率的に集約・可視化できる。

## 未解決事項・課題
13件のIssueがすべてオープンのまま残っており、所沢市教育委員会への働きかけ（Issue #4）も未完了。ホワイトリストの正式な提案・採択プロセスは引き続き未解決。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/freetothemap4boe
- Issues: https://github.com/furuhashilab/freetothemap4boe/issues

---
repo_name: "courseofstudy4highschool2022japan"
repo_url: "https://github.com/furuhashilab/courseofstudy4highschool2022japan"
genre: "other"
genre_label: "その他"
repo_created_at: "2018-02-14"
repo_updated_at: "2024-06-20"
distilled_at: "2026-05-25"
language: "HTML"
homepage: null
tags:
  - "地理総合"
  - "学習指導要領"
  - "map-education"
confidence: "high"
---

# courseofstudy4highschool2022japan

## 概要
2022年度から施行された文科省の高等学校新学習指導要領（地理・歴史科目）をMarkdown形式でオープンデータ化したリポジトリ。特に新設必履修科目「地理総合」への地理院地図・OpenStreetMap・GISツール活用をいかに実現するかを検討するための議論の場として機能している。The Unlicenseで公開されており、誰でも自由に利用・改変できる。Star 7件・Fork 9件を獲得し、外部からの貢献者もいる。

## 主な活動・成果
- 高等学校学習指導要領（地理・歴史）全文をMarkdown形式でGitHub上に公開・構造化
- Issue #2「地理総合でアクティブラーニング」・Issue #3「地理院地図の活用法」・Issue #4「OSM活用方法検討」など、地図教育の具体的な実践方法を議論
- Issue #7「パブコメについて」：2018年3月15日締切の文科省パブリックコメントへの参加を呼びかけ・議論
- Issue #14「日本地図センターのパブリックコメント」：地形図・地理院地図・500万分1地図の学習指導要領への明記を求める意見書を記録
- Issue #12「Markdown見出し階層構造」：ドキュメント構造の整備についての技術的議論
- Issue #13「原文ソースが存在しない」：外部コントリビューターによるリンク切れ報告
- Issue #8「高等学校学習指導要領解説の動向メモ」として継続的な追跡を記録

## 使用技術・ツール
- HTML / Markdown（学習指導要領の構造化・公開）
- GitHub Issues（政策議論・教育実践の検討）
- 地理院地図（教育活用候補ツール）
- OpenStreetMap（教育活用候補ツール）
- GIS / 地理情報システム（授業実践ツールとして検討）
- The Unlicense（パブリックドメイン相当のオープンライセンス）

## 得られた知見
- 法令・指導要領などの公的文書をGitHubでMarkdown管理することで、差分確認・バージョン管理・パブリックコメントの議論をオープンに行える。地理教育の文脈では、地理院地図・OSMを学習指導要領と整合させながら授業に組み込むことが有効であり、特にネット環境が限られた教室を想定したオフライン活用の検討が重要である。

## 未解決事項・課題
10件のIssueがオープンのまま残っており、地理総合でのOSM・地理院地図活用方法の具体化（Issue #3・#4）や学習指導要領解説の追跡（Issue #8）が未完了。また Issue #16 はリポジトリと無関係な外部スパム投稿（中国語）がオープンのまま残っている。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/courseofstudy4highschool2022japan
- Issues: https://github.com/furuhashilab/courseofstudy4highschool2022japan/issues

---
repo_name: "dm-keisatsu"
repo_url: "https://github.com/furuhashilab/dm-keisatsu"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-09-20"
repo_updated_at: "2021-09-20"
distilled_at: "2026-05-25"
language: null
homepage: "https://dm-keisatsu.herokuapp.com"
tags:
  - "slack"
  - "bot"
  - "dm-notification"
confidence: "high"
---

# dm-keisatsu

## 概要
Slackのダイレクトメッセージ（DM）を検知・通知する「DM警察」ボットのリポジトリ。rockymanobi/dm-keisatsu（Star 91件）をフォークしたもので、Slackワークスペース内でDMが送受信された際にチャンネル通知などを行うことで、チームのコミュニケーションを透明化・可視化することを目的としている。古橋研究室での研究室内Slack運用改善の調査目的でフォークされたと推定される。

## 主な活動・成果
- rockymanobi による JavaScript製 Slack Bot を研究室環境で参照・調査
- フォーク元は Star 91件・Fork 8件を持つ実用的なOSSとして継続メンテナンス（2023年1月まで更新）
- Heroku 上での Bot 稼働を想定した構成（homepage: dm-keisatsu.herokuapp.com）
- 古橋研究室フォークではIssuesが無効化されており、独自の開発・改変は行われていない

## 使用技術・ツール
- JavaScript（フォーク元の主要言語）
- Slack API / Slack Bot
- Heroku（ホスティングプラットフォーム）
- MIT License

## 得られた知見
- Slack DMの可視化ボットは、研究室・チーム内のコミュニケーションを透明化し、重要な情報がDMに埋もれることを防ぐ手段として有効。Heroku上でのBot常時稼働はコスト面で手軽だが、2022年のHeroku無料プラン廃止以降は代替ホスティングの検討が必要。

## 未解決事項・課題
特になし（furuhashilab フォーク自体にIssuesなし）

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/dm-keisatsu
- Issues: https://github.com/furuhashilab/dm-keisatsu/issues
- 関連サイト: https://dm-keisatsu.herokuapp.com

---
repo_name: "chizunazori"
repo_url: "https://github.com/furuhashilab/chizunazori"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-07-17"
repo_updated_at: "2021-07-17"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "地図なぞり"
  - "board-game"
  - "map-education"
confidence: "medium"
---

# chizunazori

## 概要
「地図なぞり」という地図をテーマにしたボードゲーム・教材に関連するリポジトリ。descriptionは空だが、Issue内容から、古橋研究室が「地図なぞり」という製品・教材の品質改善・バグ報告の受け皿として本リポジトリを用意したと考えられる。リポジトリ作成直後（2021年7月）のみ活動があり、サイズは0KB。

## 主な活動・成果
- Issue #1「琵琶湖に多景島がない」：Twitterで報告された「地図なぞり」製品への不具合報告を記録。琵琶湖の地図に多景島が描かれていないという地理的な誤りをバグ・不具合として登録した
- ラベルとして「バグ報告/bug」「不具合報告/invalid」が設定されており、製品フィードバック収集の体制が整えられていた

## 使用技術・ツール
- GitHub Issues（製品フィードバック・バグ報告の収集）
- Twitter（ユーザーからの不具合情報の収集元）

## 得られた知見
- 地図系の教材・ゲーム製品に対してGitHub Issuesをフィードバック窓口として活用することで、地理的な誤りや改善要望をオープンに収集・管理できる。Twitterなど外部SNSでの言及をIssueとして取り込む運用は、製品改善の可視化と記録に有効。

## 未解決事項・課題
Issue #1「琵琶湖に多景島がない」がオープンのまま残っており、修正対応の有無は不明。リポジトリ自体の活動が開設直後の1日で終わっており、継続的な運用には至らなかった。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/chizunazori
- Issues: https://github.com/furuhashilab/chizunazori/issues

---
repo_name: "www4i18n"
repo_url: "https://github.com/furuhashilab/www4i18n"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-09-01"
repo_updated_at: "2021-09-01"
distilled_at: "2026-05-25"
language: null
homepage: "http://international.gsc.aoyama.ac.jp/"
tags:
  - "GSC"
  - "i18n"
  - "international"
confidence: "high"
---

# www4i18n

## 概要
青山学院大学地球社会共生学部（GSC）の国際向けウェブサイト（GSC International）のリポジトリ。ayaishizuka/www4i18n をフォークしたもので、GSCの国際広報・多言語対応（i18n）Webページの管理・更新を目的としている。関連サイトは青山学院大学 GSC 国際ページ（international.gsc.aoyama.ac.jp）。

## 主な活動・成果
- フォーク元（ayaishizuka/www4i18n）は2018年に GSC の学生（ayaishizuka）が作成し、古橋研究室が2021年9月にフォークして参照
- リポジトリサイズが175MBと大きく、Webサイトのアセット・コンテンツ一式を含んでいると推定される
- 古橋研究室フォークではIssuesが無効化されており、独自の改変・活動記録はない

## 使用技術・ツール
- CSS（フォーク元の主要言語）
- GitHub Pages（静的サイトホスティング）
- 多言語対応（i18n）Webサイト構成

## 得られた知見
- 大学学部の国際向け広報サイトをGitHub Pagesで管理・公開することで、学生主導での継続的なコンテンツ更新が可能になる。i18n対応の静的サイトをGitHubで版管理することは、複数人での多言語コンテンツ編集フローの透明化に有効。

## 未解決事項・課題
特になし（furuhashilab フォーク自体にIssuesなし）

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/www4i18n
- Issues: https://github.com/furuhashilab/www4i18n/issues
- 関連サイト: http://international.gsc.aoyama.ac.jp/

---
repo_name: "wwwdev4gsc2019"
repo_url: "https://github.com/furuhashilab/wwwdev4gsc2019"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-09-01"
repo_updated_at: "2021-09-01"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "GSC"
  - "website"
  - "web-development"
confidence: "high"
---

# wwwdev4gsc2019

## 概要
青山学院大学地球社会共生学部（GSC）公式ウェブサイトの改良版テスト用リポジトリ。2019年度の改良作業を想定して作成されたと考えられ、本番公開前の検証・開発環境として機能していた。Issuesは無効化されており、テスト・作業用途に限定したリポジトリと推定される。

## 主な活動・成果
- GSCウェブサイトの改良・更新作業のテスト環境として整備
- リポジトリサイズが232MBと大きく、Webサイトのフルコンテンツ（画像・アセット含む）を含んでいると推定
- 最終pushは2021年7月であり、2021年9月に古橋研究室アカウントへ移管・整理された
- Issuesなし・独自活動記録なし

## 使用技術・ツール
- HTML / CSS（GSCウェブサイトの構成技術、推定）
- GitHub（バージョン管理・テスト環境）

## 得られた知見
- 大学学部サイトの改良作業をGitHubのテスト用リポジトリで管理することで、本番環境への影響を避けながら段階的な開発・検証が可能になる。年度を含んだリポジトリ命名（wwwdev4gsc2019）は、複数年度にまたがる開発履歴の整理に有効。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/wwwdev4gsc2019
- Issues: https://github.com/furuhashilab/wwwdev4gsc2019/issues

---
repo_name: "wwwdev4i18n"
repo_url: "https://github.com/furuhashilab/wwwdev4i18n"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-09-01"
repo_updated_at: "2021-09-01"
distilled_at: "2026-05-25"
language: null
homepage: "https://gsc-aoyama.github.io/wwwdev4i18n/"
tags:
  - "GSC"
  - "i18n"
  - "web-development"
confidence: "high"
---

# wwwdev4i18n

## 概要
青山学院大学地球社会共生学部（GSC）の国際向けウェブサイト（International）の動作確認・開発テスト環境用リポジトリ。`www4i18n`（本番相当）に対する開発・検証ブランチとして位置づけられており、変更内容を GitHub Pages 上でプレビュー確認するための環境として整備された。Issuesは無効化されており、テスト専用運用。

## 主な活動・成果
- GSC International サイトの改修・多言語対応（i18n）作業の動作確認環境として構築
- GitHub Pages（gsc-aoyama.github.io/wwwdev4i18n/）でのプレビュー公開を想定した構成
- リポジトリサイズは92MBで、Webアセット一式を含む
- 最終pushは2021年7月、2021年9月に古橋研究室アカウントへ移管・整理

## 使用技術・ツール
- HTML / CSS（GSCウェブサイト構成技術、推定）
- GitHub Pages（開発プレビュー環境）
- 多言語対応（i18n）Webサイト構成

## 得られた知見
- 本番リポジトリ（www4i18n）と開発確認用リポジトリ（wwwdev4i18n）を分離することで、本番への影響を避けながら多言語対応の動作検証が行える。GitHub Pagesを開発環境として活用する構成は、静的サイトの段階的リリースに適している。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/wwwdev4i18n
- Issues: https://github.com/furuhashilab/wwwdev4i18n/issues
- 関連サイト: https://gsc-aoyama.github.io/wwwdev4i18n/

---
repo_name: "www4gsc"
repo_url: "https://github.com/furuhashilab/www4gsc"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-09-01"
repo_updated_at: "2021-09-01"
distilled_at: "2026-05-25"
language: null
homepage: "http://www.gsc.aoyama.ac.jp/"
tags:
  - "GSC"
  - "website"
  - "aoyama-gakuin"
confidence: "high"
---

# www4gsc

## 概要
青山学院大学地球社会共生学部（GSC）の公式ウェブサイト（2019〜2021年7月1日版）のアーカイブリポジトリ。mapconcierge/www4gsc（古橋教授個人アカウントで管理されていた2018年版）をフォークし、furuhashilab組織アカウントへ移管した形で保存されている。2021年7月1日以降は新サイトへ移行したと考えられる。

## 主な活動・成果
- mapconcierge（古橋教授）が2018年に作成した GSC 公式サイトを、2019〜2021年7月にかけて運用
- 2021年9月に古橋研究室組織アカウントへフォーク・移管してアーカイブ化
- Issuesは無効化されており、独自の活動記録はない
- リポジトリサイズが236MBと大きく、画像・CSS・HTMLコンテンツを一式含む
- フォーク元（mapconcierge/www4gsc）はFork 4件で、複数のGSC関係者に活用されていた

## 使用技術・ツール
- CSS（フォーク元の主要言語）
- HTML（静的Webサイト）
- GitHub Pages / gh-pages ブランチ（静的サイトホスティング）

## 得られた知見
- 大学学部の公式サイトをGitHub Pagesで運用することで、学生・教員が協力してコンテンツを更新・管理できる。年度ごとに運用リポジトリをアーカイブ化することで、サイトの変遷を記録・参照しやすくなる。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/www4gsc
- Issues: https://github.com/furuhashilab/www4gsc/issues
- 関連サイト: http://www.gsc.aoyama.ac.jp/

