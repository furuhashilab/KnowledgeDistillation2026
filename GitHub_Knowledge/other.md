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

---
repo_name: "jageocoder"
repo_url: "https://github.com/furuhashilab/jageocoder"
genre: "other"
genre_label: "その他"
repo_created_at: "2022-02-16"
repo_updated_at: "2022-02-16"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "address"
  - "geocoding"
  - "python"
confidence: "high"
---

# jageocoder

## 概要
本リポジトリは、Pure Python 製の日本語住所ジオコーダー「jageocoder」（オリジナル: t-sagara/jageocoder）を古橋研究室（furuhashilab）がフォークしたものである。オリジナルはオフライン・オンライン双方で動作する日本語住所のジオコーディングライブラリとして開発されており、Python のみで実装されている点が特徴である。研究室での地理空間データ処理や住所解析への応用を目的として取り込まれたと考えられる。

## 主な活動・成果
- t-sagara/jageocoder からのフォーク取得（2022年2月）
- Issues・コメントは本フォークリポジトリ上では作成されておらず、独自の開発活動は記録されていない
- オリジナルリポジトリ（t-sagara/jageocoder）は2026年4月時点でも継続的にメンテナンスされており、Star数96を獲得するアクティブな OSS として機能している

## 使用技術・ツール
- Python（オリジナルリポジトリの主要言語）
- jageocoder ライブラリ（日本語住所ジオコーディング）
- オフライン・オンライン両対応のジオコーディングアーキテクチャ

## 得られた知見
- jageocoder は Pure Python 実装のため、外部バイナリ依存なしに日本語住所のジオコーディングを導入できる。地理空間プロジェクトで住所文字列を座標に変換する必要がある場合、pip 一発で組み込める軽量な選択肢として有効である。
- オリジナルリポジトリがアクティブにメンテナンスされているため、フォークを長期維持するよりもオリジナルを直接依存として使用するほうが運用コストが低い。

## 未解決事項・課題
- フォーク後の独自変更・Issue・活動が一切記録されておらず、研究室内でどのような目的・文脈で利用されたかは本リポジトリからは読み取れない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/jageocoder
- Issues: https://github.com/furuhashilab/jageocoder/issues
- オリジナル: https://github.com/t-sagara/jageocoder

---
repo_name: "s2geometry"
repo_url: "https://github.com/furuhashilab/s2geometry"
genre: "other"
genre_label: "その他"
repo_created_at: "2022-01-07"
repo_updated_at: "2022-01-07"
distilled_at: "2026-05-25"
language: null
homepage: "http://s2geometry.io/"
tags:
  - "geometry"
  - "s2"
  - "spatial-indexing"
confidence: "high"
---

# s2geometry

## 概要
本リポジトリは、Google が開発・公開している球面幾何学ライブラリ「s2geometry」（google/s2geometry）を古橋研究室（furuhashilab）がフォークしたものである。S2 は球面上の計算幾何学と空間インデックスを扱うライブラリで、地球を球体として正確にモデル化し、領域の包含判定や近傍検索などを高速に実行できる。研究室での地理空間解析・空間インデックス処理の調査・参照目的で取り込まれたと考えられる。

## 主な活動・成果
- google/s2geometry からのフォーク取得（2022年1月）
- フォーク後、本リポジトリ上での独自 Issue・コメント・変更は記録されていない
- オリジナル（google/s2geometry）は2026年5月時点でも活発にメンテナンスされており、Star数2,664・Fork数355を持つ大規模 OSS として継続している

## 使用技術・ツール
- C++（オリジナルリポジトリの主要言語）
- S2 Geometry ライブラリ（球面上の空間インデックス・幾何演算）
- Apache License 2.0

## 得られた知見
- S2 ライブラリは緯度経度を球面上のセル（S2Cell）で階層的に分割するため、地理的な近傍検索・範囲クエリを平面投影誤差なしに実行できる。ドローン測量や地図データの空間インデックス構築など、精度が重要な地理空間処理において有力な選択肢となる。
- フォークのみで独自変更がない場合、OSS を「手元に確保する」目的のミラーとして機能しており、バージョン固定や参照用として活用するパターンが研究室リポジトリに多く見られる。

## 未解決事項・課題
- フォーク後の独自活動・Issue が皆無であり、研究室内での具体的な活用内容は本リポジトリからは確認できない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/s2geometry
- Issues: https://github.com/furuhashilab/s2geometry/issues
- 関連サイト: http://s2geometry.io/
- オリジナル: https://github.com/google/s2geometry

---
repo_name: "pm"
repo_url: "https://github.com/furuhashilab/pm"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-12-30"
repo_updated_at: "2021-12-30"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "UNVT"
  - "project-management"
  - "vector-tile"
confidence: "high"
---

# pm

## 概要
本リポジトリは、UN Vector Tile Toolkit（UNVT）のプロジェクト管理リポジトリ「pm」（オリジナル: unvt/pm）を古橋研究室（furuhashilab）がフォークしたものである。UNVT は国連が推進するベクタータイル標準化プロジェクトであり、本リポジトリはその開発・運営上のタスクや課題をIssueで一元管理することを目的としている。古橋研究室は UNVT プロジェクトに深く関与しており、上流の活動を追跡・参照するためにフォークしたと考えられる。

## 主な活動・成果
- unvt/pm からのフォーク取得（2021年12月）
- フォーク後、本リポジトリ上での独自 Issue・コメント・変更は記録されていない
- オリジナル（unvt/pm）はフォーク時点で28件のオープン Issue を持ち、CC0-1.0 ライセンスのもとで UNVT の課題管理が行われている

## 使用技術・ツール
- GitHub Issues（プロジェクト管理）
- CC0-1.0（パブリックドメイン相当ライセンス）
- UN Vector Tile Toolkit（UNVT）エコシステム

## 得られた知見
- OSS プロジェクトのプロジェクト管理を GitHub Issues 単体で行う軽量な手法は、コード不要でタスク・議論・決定事項を追跡でき、研究室や小規模チームの活動記録にも転用しやすい。
- UNVT のような国際的な OSS プロジェクトの pm リポジトリをフォークして手元に置くことで、上流のロードマップや意思決定プロセスをウォッチする仕組みを作れる。

## 未解決事項・課題
- フォーク後の独自活動が皆無であり、研究室内での具体的な活用内容は本リポジトリからは確認できない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/pm
- Issues: https://github.com/furuhashilab/pm/issues
- オリジナル: https://github.com/unvt/pm

---
repo_name: "community-geocoder"
repo_url: "https://github.com/furuhashilab/community-geocoder"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-06-01"
repo_updated_at: "2020-06-01"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "geocoding"
  - "open-source"
  - "japan"
confidence: "high"
---

# community-geocoder

## 概要
本リポジトリは、日本国内向けのオープンソース・無償のジオコーディングAPIである `geolonia/community-geocoder` を古橋研究室がフォークしたものである。住所文字列から緯度経度座標への変換（ジオコーディング）を無償で利用できる環境を日本のコミュニティに提供することを目的としている。フォーク元（geolonia）が主体的に開発・維持しており、本フォークは研究・教育目的での参照・利用が主な用途と考えられる。

## 主な活動・成果
- geolonia/community-geocoder からのフォーク取得（2020年6月）
- Issues・コメントは本フォークリポジトリには存在せず、活動の実体はフォーク元リポジトリに集約されている
- フォーク元は196スターを獲得し、26フォーク・56オープンIssueを有する活発なOSSプロジェクトとして継続中

## 使用技術・ツール
- JavaScript（フォーク元の主要言語）
- ジオコーディングAPI（RESTful）
- MIT License
- GitHub Pages（フォーク元でホスティング）

## 得られた知見
- 日本の住所データに対応した無償ジオコーディングAPIとして `community-geocoder` を活用することで、有償サービス（Google Maps Geocoding API等）に依存せずに座標変換処理を実装できる。研究・教育プロジェクトにおいてコスト面での制約を回避する選択肢として有効である。
- OSSのフォークを研究組織のGitHub Organizationに取り込むことで、特定バージョンの固定・カスタマイズ・内部利用が可能になる。

## 未解決事項・課題
フォーク元（geolonia/community-geocoder）に56件のオープンIssueが存在しており、住所カバレッジや精度に関する課題が継続的に議論されていると推察される。本フォークリポジトリ自体には独自のIssue・活動は確認されていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/community-geocoder
- Issues: https://github.com/furuhashilab/community-geocoder/issues
- フォーク元: https://github.com/geolonia/community-geocoder

---
repo_name: "geo4jica"
repo_url: "https://github.com/furuhashilab/geo4jica"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-07-21"
repo_updated_at: "2020-07-29"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "jica"
  - "geojson"
  - "mapping"
confidence: "high"
---

# geo4jica

## 概要
JICAプロジェクトのマッピングを目的として作成されたリポジトリ。JICAが実施する海外援助プロジェクト（ブラジルを含む複数拠点）の地理情報を GeoJSON 形式で整備し、「見える化サイト」として公開・活用することを目指している。古橋研究室の学生複数名が分担して地理データの作成・整理を行うチーム作業の場として機能している。

## 主な活動・成果
- メンバー管理 Issue を設け、GitHub の Assign 機能でプロジェクト参加者を自己登録する運用を確立
- geojson.io を用いた GeoJSON ポリゴンデータの作成作業を分担実施（マイルストーン：32件のプロジェクト分 GeoJSON ファイル作成完了）
- JICA 見える化サイト向けブラジル版スプレッドシートの作成（Google スプレッドシートで管理）
- 暫定作業ファイルの改定作業（Google ドキュメントで管理・共有）
- チーム全員の Slack 参加を促す連絡・調整タスクを Issue 化
- グラフィックレコーディング（グラレコ）の作成タスクを Issue 化し担当者をアサイン

## 使用技術・ツール
- GeoJSON（地理情報フォーマット）
- geojson.io（GeoJSON ポリゴン作成ツール）
- Google スプレッドシート（プロジェクトデータ管理）
- Google ドキュメント（作業ファイル共有・改定）
- Slack（チームコミュニケーション）
- GitHub Issues / Milestones（タスク・進捗管理）

## 得られた知見
- GitHub Issues をタスク管理ツールとして活用し、Assign・Milestone 機能で担当者と締切を明確にすることで、地理データ作成のような分散作業を効率的に進められる。geojson.io のようなブラウザベースのツールと GitHub を組み合わせることで、GIS 専門ツールなしでも複数人でのジオデータ整備が可能。
- Google スプレッドシートで属性情報を管理し、GeoJSON と分離して運用するアーキテクチャは、非エンジニアのメンバーが多い研究室チームでも参加障壁を下げる有効なアプローチ。

## 未解決事項・課題
- 全 Issues（6件）がオープンのまま残っており、GeoJSON ポリゴンデータ作成・ブラジル版スプレッドシート・暫定作業ファイルの改定・Slack 全員参加・グラレコ作成がいずれも未クローズ。
- リポジトリの最終更新が2020年7月末で活動が停止している可能性があり、成果物の完成・公開状況が不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/geo4jica
- Issues: https://github.com/furuhashilab/geo4jica/issues

---
repo_name: "geocaching4yokoze"
repo_url: "https://github.com/furuhashilab/geocaching4yokoze"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-07-21"
repo_updated_at: "2020-07-24"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "geocaching"
  - "yokoze"
  - "location-based-game"
confidence: "high"
---

# geocaching4yokoze

## 概要
埼玉県横瀬町を舞台としたジオキャッシングプロジェクトのリポジトリ。ジオキャッシングとは GPS を使って隠されたキャッシュ（宝箱）を探す位置情報ゲームで、本プロジェクトはその横瀬町版の企画・実施を目的としている。古橋研究室が地域連携の一環として取り組んだ活動とみられる。

## 主な活動・成果
- メンバー管理 Issue を設け、GitHub Assign でプロジェクト参加者を自己登録する運用を確立
- 立ち上げ直後の段階でリポジトリの活動が停止しており、具体的な作業 Issue は確認できない

## 使用技術・ツール
- GitHub Issues（メンバー管理・タスク管理）
- ジオキャッシング（GPS を用いた位置情報ゲーム）

## 得られた知見
- 地域（横瀬町）×ジオキャッシングという組み合わせは、地理情報教育や地域活性化と親和性が高い。フィールドワーク型の地理教育コンテンツとして、授業やイベントへの転用が考えられる。立ち上げ期にリポジトリと Issues を先に整備しておく運用は、参加者募集と進捗管理を同時に始めるための有効な足場となる。

## 未解決事項・課題
- Issues がメンバー管理用の1件のみで、具体的な企画・実施内容が記録されていない。2020年7月24日以降の活動が確認できず、プロジェクトが実際に進展したかどうかは不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/geocaching4yokoze
- Issues: https://github.com/furuhashilab/geocaching4yokoze/issues

---
repo_name: "spatialchat4gsc"
repo_url: "https://github.com/furuhashilab/spatialchat4gsc"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-07-21"
repo_updated_at: "2020-07-24"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "spatialchat"
  - "remote-collaboration"
  - "virtual-space"
confidence: "high"
---

# spatialchat4gsc

## 概要
古橋ゼミ専用スペースおよびGSC（Global Shapers Community または授業・イベント用スペースと推定）向けに、バーチャル空間コミュニケーションツール SpatialChat（スペチャ）の空間設計・運用を行うプロジェクト。2020年のリモートワーク普及期に、オンライン上での自然なコミュニケーション環境を整備することを目的として立ち上げられた。Issues は「古橋ゼミ向け」と「GSC向け」の2系統に分けて管理されている。

## 主な活動・成果
- メンバー管理 Issue を設け、GitHub Assign でプロジェクト参加者を自己登録する運用を確立
- 古橋ゼミ専用 SpatialChat スペースの設計・構築担当者をアサイン（Issue #2）
- GSC 向け SpatialChat スペースの設計・構築担当者をアサイン（Issue #3）
- 発表・説明用スライドの作成タスクを Issue 化（Issue #4、`documentation` ラベル付き）
- メンバー管理 Issue に6件のコメントが寄せられており、参加表明や調整が活発に行われた形跡がある

## 使用技術・ツール
- SpatialChat（バーチャル空間コミュニケーションツール、通称「スペチャ」）
- GitHub Issues / Labels（タスク管理・用途別分類）

## 得られた知見
- SpatialChat のスペース設計を用途別（ゼミ内部用・対外イベント用）に分けて管理することで、参加者の混在を防ぎつつ運営できる。GitHub Issues のラベルで「スペチャ」「documentation」といった用途別分類を行う手法は、小規模チームでも作業の見通しを改善する。リモート環境下でのバーチャルスペース整備は、発表資料（スライド）とセットで運用すると説明・onboarding がしやすい。

## 未解決事項・課題
- 全 Issues（4件）がオープンのままで、各スペースの完成・公開状況が不明。Issue #2・#4 は2021年4月まで更新されており、一定期間にわたって参照されていたことが伺えるが、最終的な完了確認はされていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/spatialchat4gsc
- Issues: https://github.com/furuhashilab/spatialchat4gsc/issues

---
repo_name: "fabla-bu"
repo_url: "https://github.com/furuhashilab/fabla-bu"
genre: "other"
genre_label: "その他"
repo_created_at: "2019-06-28"
repo_updated_at: "2020-07-21"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "fabrication"
  - "processing"
  - "3d-printing"
confidence: "high"
---

# fabla-bu

## 概要
古橋研究室「ものづくり部」のメインリポジトリ。マニュアルやノウハウの共有を主目的とし、3Dプリンティング・CAD・プログラミングによる造形・AR など、幅広いファブリケーション活動の記録場として機能している。公開リポジトリのため、セキュリティ情報の取り扱いに注意するよう明示されている。

## 主な活動・成果
- Tinkercad を用いたスマホスタンドの 3D モデル試作（2020年5月、複数名が独立して試作品を作成・共有）
- 河合継ぎ手（KawaiTsugite）の STL ファイルを 20mm×20mm にリサイズして 3D 出力（2019年7月）
- Processing を用いた月齢自動生成シミュレーションプログラムの開発（Issue #4、14件のコメントで活発に議論）
- Processing による色・スピードがランダムな円アニメーションの実装と共有（Issue #6、コードをIssue本文に直接掲載）
- ガチャムクハッカソン向けに Processing で SVG を生成するタスクに取り組む（Issue #5）
- NyARToolkit for Processing を動作させる試み（Issue #7、AR マーカー認識への挑戦）

## 使用技術・ツール
- Processing（ビジュアルプログラミング・アニメーション・SVG生成）
- Tinkercad（ブラウザベース 3D CAD ツール）
- NyARToolkit（AR マーカー認識ライブラリ）
- STL / GX 形式（3D プリンタ出力ファイル）
- SVG（ベクター画像フォーマット）
- GitHub Issues（制作ログ・ノウハウ共有）

## 得られた知見
- Processing は入門コストが低く、月齢シミュレーションのような数理的ビジュアライゼーションから AR まで幅広く応用できる。Issues をものづくりの作業ログとして活用し、コードをそのまま本文に貼り付けることで、再現性の高いナレッジ共有が実現できる。Tinkercad はブラウザ上で完結するため、3D プリンタ初心者が CAD に慣れる最初のステップとして有効。
- ガチャムクハッカソンのような外部イベントと連携することで、ものづくり部の活動に具体的な締切と目標が生まれ、成果物の完成度が高まりやすい。

## 未解決事項・課題
- 全 Issues（7件）がオープンのまま。特に月齢シミュレーション（14コメント）とガチャムクSVG生成（5コメント）は議論が進んでいるが完了確認がされていない。NyARToolkit の動作確認も未解決のまま残っている。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/fabla-bu
- Issues: https://github.com/furuhashilab/fabla-bu/issues

---
repo_name: "aoyamavision2017"
repo_url: "https://github.com/furuhashilab/aoyamavision2017"
genre: "other"
genre_label: "その他"
repo_created_at: "2017-10-18"
repo_updated_at: "2020-07-07"
distilled_at: "2026-05-25"
language: "HTML"
homepage: "http://crisismapping.aoyamavision.com"
tags:
  - "crisis-mapping"
  - "aoyama-vision"
  - "conference"
confidence: "high"
---

# aoyamavision2017

## 概要
青山学院大学における「AOYAMA VISION クライシスマッピングプロジェクト」のリポジトリ。2018年2月に青山学院大学アスタジオで開催された CrisisMapping Conference の企画・運営および会場デザインを中心に、研究室学生が複数チームに分かれて取り組んだ。HTML で構築されたウェブサイトも GitHub Pages として公開されており、活動の発信拠点としても機能している。

## 主な活動・成果
- AOYAMA VISION CrisisMapping Conference の開催準備（2018年2月25日、青山学院大学アスタジオ）
- 会場を「作業スペース」「工作スペース」「くつろぎスペース」「スクリーン近辺」の4エリアに分けてチーム別にデザイン・備品検討を実施（Issues #5〜#9）
- カンファレンス用ロゴの複数案（Plan1・Plan2）を Keynote で作成し Issue に掲載して検討（Issue #12）
- グラレコ用マーカー・マスキングテープ・ホワイトボードペンなどワークショップ備品のリストアップ（Issue #10）
- 年次報告書（会場配布用）の作成・共有（Issue #13、9コメントで活発に協議）
- index.html の英訳対応を PR として提出（PR #21）
- 懇親会ライトニングトーク大会の企画（Issue #14）
- スタッフスケジュール調整（Issue #15、6コメント）
- 2018年版拠点提案 PDF の共有（Issue #22）
- 写真アーカイブ Issue での活動記録（Issue #2、13コメント）

## 使用技術・ツール
- HTML（ウェブサイト構築）
- GitHub Pages（サイト公開）
- Keynote（ロゴ・プレゼン資料作成）
- GitHub Issues / Milestones / Labels（タスク管理・デザイン案レビュー）
- グラフィックレコーディング用画材（水性ペン・ホワイトボードペン等）

## 得られた知見
- イベント会場を用途別エリアに分けて Issues を割り当て、チームごとに進捗を可視化する手法は、学生主体の大型イベント運営で再現性が高い。Milestone に「デザイン案最終提出」のような明確な締切を設定し、教員（古橋）がコメントで承認するワークフローは、教育現場での GitHub 活用モデルとして参考になる。また年次報告書を GitHub で管理することで、複数人での編集履歴が追跡でき、成果物の透明性が高まる。

## 未解決事項・課題
- 16件のオープン Issue が残っており、会場デザイン各班の最終成果確認・PR #19・#21のマージ・2018年版拠点提案の採否がいずれも未クローズ。リポジトリ自体は2020年7月まで更新されており、継続的に参照されてきた形跡がある。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/aoyamavision2017
- Issues: https://github.com/furuhashilab/aoyamavision2017/issues
- 関連サイト: http://crisismapping.aoyamavision.com

---
repo_name: "geo4teachers"
repo_url: "https://github.com/furuhashilab/geo4teachers"
genre: "other"
genre_label: "その他"
repo_created_at: "2018-11-13"
repo_updated_at: "2024-06-20"
distilled_at: "2026-05-25"
language: "JavaScript"
homepage: "https://furuhashilab.github.io/geo4teachers"
tags:
  - "education"
  - "crisis-mapping"
  - "teaching-materials"
confidence: "high"
---

# geo4teachers

## 概要
教員向け地理・クライシスマッピング教材のポータルサイトリポジトリ。Jekyll ベースのモダンブログテンプレート（Jekyll_modern-blog）をフォークして構築されており、GitHub Pages で公開されている。2019年度の「クライシスマッピング ウェブ教材開発」研究活動の成果をまとめ、教員が授業で活用できる地理教材を集積・整備することを目的としている。高校新学習指導要領（2022年施行）への対応も視野に入れた教材開発が行われていた。

## 主な活動・成果
- 2019年度報告書（クライシスマッピング ウェブ教材開発の研究報告書）を DOCX・PDF 形式で Issue に添付・共有（Issue #1）
- CrisisMapping2018 活動成果リストおよび機材使用状況 PDF も同 Issue で公開
- 投影法をテーマにした教材素材のメモを Issue 化（Issue #2）
- 高校新学習指導要領（courseofstudy4highschool2022japan）リポジトリの Markdown 化タスクを Issue として記録（Issue #3）

## 使用技術・ツール
- JavaScript / Jekyll（Jekyll_modern-blog テンプレートベース）
- GitHub Pages（教材ポータルサイト公開）
- Markdown（教材・学習指導要領のテキスト化）
- GitHub Issues（成果物アーカイブ・タスク管理）
- CC BY 4.0 ライセンス（教材の再利用・二次利用を推進）

## 得られた知見
- Jekyll + GitHub Pages の組み合わせは、教員向けポータルサイトを低コストで構築・公開する手法として有効。CC BY 4.0 ライセンスを採用することで、他の教員や研究者が教材を再利用しやすい環境を整備できる。学習指導要領を Markdown 化して GitHub で管理することで、教材と指導要領の対応関係を diff で追跡でき、カリキュラム改訂への対応が容易になる。

## 未解決事項・課題
- 3件の Issues がすべてオープンのまま。特に学習指導要領の Markdown 化（Issue #3）および投影法教材の整備（Issue #2）は着手確認が取れない。リポジトリへの最終 push は2020年7月で、その後の教材拡充状況は不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/geo4teachers
- Issues: https://github.com/furuhashilab/geo4teachers/issues
- 関連サイト: https://furuhashilab.github.io/geo4teachers

---
repo_name: "InformationSociety2020AGU"
repo_url: "https://github.com/furuhashilab/InformationSociety2020AGU"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-06-30"
repo_updated_at: "2021-09-06"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "education"
  - "license"
  - "information-society"
confidence: "high"
---

# InformationSociety2020AGU

## 概要
青山学院大学「情報社会論2020」（ハッシュタグ #AGU情報社会論）の授業運営リポジトリ。著作権・ライセンス・情報倫理を中心テーマとし、GitHub Issues を課題提出・ディスカッションの場として活用した実験的な授業設計が特徴。CC BY-SA 4.0 ライセンスが適用されており、授業コンテンツの再利用・共有を前提としている。

## 主な活動・成果
- ソフトウェアライセンス（Apache・GPL3・MIT・WTFPL・None・Unlicense）の関係を図化して Issue に投稿する課題を実施（Issue #1、20コメント）
- 「正しい引用」「剽窃」「盗用」「盗作」「オマージュ」「パロディ」の違いを図にまとめる課題（Issue #3、20コメント）
- 政府標準利用規約第2.0版を採用しているウェブサイト・データを調査・投稿する課題（Issue #4、22コメント）
- 架空または実在のオリジナルコンテンツにライセンスを定義し、選択理由を500文字で記述する課題（Issue #5、23コメント）
- 最終課題として Creative Commons 6種・政府標準利用規約・CC0・Public Domain・ソフトウェアライセンス・引用・剽窃・フェアユースをグラフィックレコーディング（A4手書き）で図化し提出（Issue #6、21コメント）
- GitHub Issues と Google Classroom を連携した課題提出フロー（Issue の Permalink を Classroom に投稿）を確立

## 使用技術・ツール
- GitHub Issues（課題提出・ディスカッション）
- Google Classroom（課題管理・リンク提出）
- グラフィックレコーディング（手書き図化、スキャン/撮影して Issue に Drag&Drop）
- CC BY-SA 4.0 ライセンス

## 得られた知見
- GitHub Issues を大学授業の課題提出プラットフォームとして活用することで、学生同士が互いの提出物をリアルタイムで参照・刺激し合えるオープンな学習環境が生まれる。Issue の Permalink を Google Classroom にリンクとして提出させるワークフローは、LMS と GitHub の二重管理を最小限のコストで実現する実践的な手法。グラレコ（グラフィックレコーディング）を最終課題のアウトプット形式に用いることで、テキストだけでは表現しにくい概念間の関係性を視覚的に整理させる効果がある。

## 未解決事項・課題
- 6件の Issues がすべてオープンのままで、授業終了後のクローズ処理が行われていない。課題提出状況は各 Issue のコメント（20〜23件）から確認できるが、最終的な採点・フィードバックの記録は Issue 上には残っていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/InformationSociety2020AGU
- Issues: https://github.com/furuhashilab/InformationSociety2020AGU/issues

---
repo_name: "2020_gurareco"
repo_url: "https://github.com/furuhashilab/2020_gurareco"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-06-23"
repo_updated_at: "2020-06-30"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "graphic-recording"
  - "illustration"
  - "design-competition"
confidence: "high"
---

# 2020_gurareco

## 概要
古橋研究室「グラレコ部」の2020年度活動リポジトリ。グラフィックレコーディング（グラレコ）とイラスト制作を軸に、外部のデザインコンペや公募への応募作品制作、および発表資料の作成を行った。2020年6月に開催されたハッカソンへの参加を起点として立ち上げられ、複数の公募案件への取り組みが Issues で管理されている。

## 主な活動・成果
- 2020年6月ハッカソンへの参加準備・活動記録（Issue #1、Milestone「提出画像締め切り」に紐付け）
- 福井市マンホールふたデザイン公募への応募検討（Issue #2）
- 琵琶湖システム ロゴマーク公募への応募検討（Issue #3）
- 高知県「KOCHI YUZU」ロゴマーク公募への応募検討（Issue #4）
- 2020/06/30 発表用プレゼンテーション資料を Google スライドで作成・Issue にリンク共有（Issue #5）
- Milestone「発表日まで」「提出画像締め切り」の2段階で締切管理を実施

## 使用技術・ツール
- グラフィックレコーディング（手書きビジュアル記録技法）
- イラスト制作（ラベル「イラスト」で分類）
- Google スライド（発表資料作成）
- GitHub Issues / Milestones（タスク・締切管理）

## 得られた知見
- 外部の公募・コンペを活動目標に設定することで、グラレコ・イラスト制作部活動に具体的な締切と評価基準が生まれ、成果物の質向上につながる。Milestone を「提出画像締め切り」と「発表日まで」に分けて二段階管理する手法は、制作フェーズと発表フェーズを分離して進捗を可視化するのに有効。

## 未解決事項・課題
- 全 Issues（5件）がオープンのまま。各公募への実際の応募有無・結果が記録されておらず不明。リポジトリへの最終更新が2020年6月末で活動が停止している。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/2020_gurareco
- Issues: https://github.com/furuhashilab/2020_gurareco/issues

---
repo_name: "missingmaps.github.io"
repo_url: "https://github.com/furuhashilab/missingmaps.github.io"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-06-28"
repo_updated_at: "2020-06-30"
distilled_at: "2026-05-25"
language: "HTML"
homepage: "http://www.missingmaps.org"
tags:
  - "missing-maps"
  - "crisis-mapping"
  - "openstreetmap"
confidence: "high"
---

# missingmaps.github.io

## 概要
Missing Maps プロジェクトの公式ウェブサイト（MissingMaps/missingmaps.github.io）を古橋研究室がフォークしたリポジトリ。Missing Maps は人道支援を目的としたクライシスマッピング活動で、OpenStreetMap を通じて地図が整備されていない脆弱地域を事前にマッピングする国際プロジェクト。古橋研究室は同プロジェクトと深く連携しており、ウェブサイトの日本語化や独自カスタマイズを目的としてフォークしたものと推定される。Issues は無効化されており、活動ログは残っていない。

## 主な活動・成果
- MissingMaps 公式サイトリポジトリを furuhashilab 組織にフォーク（2020年6月28日）
- フォーク後2日間でコミットが行われており、何らかのカスタマイズ・実験が実施された
- Issues は無効化されており、具体的な作業内容は Issues からは確認不可

## 使用技術・ツール
- HTML（主要言語）
- GitHub Pages（サイト公開）
- CC BY 4.0 ライセンス
- Jekyll（フォーク元のサイト構成から推定）

## 得られた知見
- Missing Maps のような国際的なクライシスマッピングサイトをフォークして独自運用する場合、フォーク元が旧バージョン（OLD version）であることに注意が必要。現行の公式サイトは mm-website-v2 リポジトリに移行済みであり、フォーク元の更新に追従するかどうかの判断が重要になる。

## 未解決事項・課題
- Issues が無効のため作業内容・目的の詳細が不明。フォーク後の活動が2020年6月末で停止しており、日本語化等のカスタマイズが完了したかどうか確認できない。フォーク元（MissingMaps/missingmaps.github.io）は現在も旧バージョンとして維持されており、現行サイトとの乖離が生じている可能性がある。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/missingmaps.github.io
- 関連サイト: http://www.missingmaps.org

