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

