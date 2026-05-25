---
repo_name: "grareco"
repo_url: "https://github.com/furuhashilab/grareco"
genre: "other"
genre_label: "その他"
repo_created_at: "2018-04-18"
repo_updated_at: "2025-11-21"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "グラフィックレコーディング"
  - "アーカイブ"
  - "研究室"
confidence: "medium"
---

# grareco

## 概要
古橋研究室（furuhashilab）が開催する講義・勉強会・ゼミのグラフィックレコーディング（グラレコ）をアーカイブするためのリポジトリである。リポジトリ名「grareco」は「グラレコ」の略称に由来する。参加者がその場でビジュアル化した記録を画像ファイルとして蓄積・共有することを目的としており、2018年の創設以来継続的に運用されている。

## 主な活動・成果
- GitHubのIssueを提出窓口として活用し、各回のグラレコ画像（JPEG、最低1600×1200ピクセル）をIssueのコメントにアップロードする運用フローを確立
- 2018年4月：神奈川県大和市寄付講座（大木市長登壇）のグラレコをPDFおよびスクリーンショット形式で記録・保存（Issue #1）
- 2019年12月23日開催分のグラレコを11件のコメントで収集（Issue #2）
- 2020年1月6日開催分のグラレコを8件のコメントで収集（Issue #3）
- 全IssueはOpenのままアーカイブとして維持されており、提出締切後もコメントが追加された記録がある

## 使用技術・ツール
- GitHub Issues（画像アップロード・アーカイブの提出プラットフォームとして利用）
- JPEG画像形式（提出フォーマット：最低1600×1200ピクセル）
- PDF（補足資料の添付に使用）
- プログラミング言語：なし（language: null）

## 得られた知見
- GitHubのIssueは画像ファイルの提出・収集プラットフォームとして機能する。日付ベースのIssueタイトルを採番することで、開催回ごとの成果物を時系列アーカイブとして低コストで管理できる。
- グラレコの提出品質を担保するため「最低1600×1200ピクセル以上」という解像度基準を明示することで、後からの可読性・再利用性を確保できる。
- IssueをOpenのまま運用することで、後日追加コメントや補足画像を受け付ける柔軟な窓口として機能させられる。

## 未解決事項・課題
- Issue #1〜#3がすべてOpenのままであり、クローズ運用のルールが明確化されていない。アーカイブとして意図的にOpenにしているのか、管理上の未整理なのか判断できない状態が続いている。
- topicsが未設定のため、リポジトリの検索性・分類性が低い。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/grareco
- Issues: https://github.com/furuhashilab/grareco/issues---
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

---
repo_name: "digitaljournalism101geoversion"
repo_url: "https://github.com/furuhashilab/digitaljournalism101geoversion"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-12-14"
repo_updated_at: "2020-12-14"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "digital-journalism"
  - "media-literacy"
  - "geo"
confidence: "medium"
---

# digitaljournalism101geoversion

## 概要
メディアリテラシーにも役立つ「デジタル報道101」を地理・地理空間情報（ジオ）分野向けにカスタマイズしたリポジトリ。デジタルジャーナリズムの基礎知識をジオ系の文脈に合わせて再編集することを目的としている。CC BY 4.0ライセンスで公開されており、教育・研究目的での二次利用が想定されている。

## 主な活動・成果
- 「デジタル報道101」コンテンツの地理情報分野向けカスタマイズ版の作成
- CC BY 4.0ライセンスによるオープンな教育コンテンツとしての公開
- （Issuesなし：具体的な議論・作業記録は残されていない）

## 使用技術・ツール
- GitHub（コンテンツ管理・公開）
- Creative Commons Attribution 4.0 International（ライセンス）
- プログラミング言語：なし（language: null）

## 得られた知見
既存のデジタルジャーナリズム教育コンテンツを特定分野（地理・ジオ）向けにカスタマイズして公開するアプローチは、専門分野におけるメディアリテラシー教育の効率的な展開手法として転用できる。CC BY 4.0での公開により、他機関・研究者による改変・再配布が容易になる点も教育リソースの普及戦略として有効。

## 未解決事項・課題
Issuesが存在しないため、具体的な作業進捗や課題は不明。コンテンツの更新・充実が継続されているかどうか確認できない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/digitaljournalism101geoversion
- Issues: https://github.com/furuhashilab/digitaljournalism101geoversion/issues

---
repo_name: "history-of-Geocaching"
repo_url: "https://github.com/furuhashilab/history-of-Geocaching"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-11-10"
repo_updated_at: "2020-11-12"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "geocaching"
  - "location-based-game"
  - "gps"
confidence: "medium"
---

# history-of-Geocaching

## 概要
古橋研究室（furuhashilab）によるジオキャッシング（Geocaching）の歴史をまとめた調査・記録リポジトリ。GPSを活用した宝探しゲームであるジオキャッシングの成り立ちや発展について整理することを目的としていると推察される。descriptionは設定されていないが、リポジトリ名とサイズ（161KB）からある程度のコンテンツが存在することが確認できる。

## 主な活動・成果
- ジオキャッシングの歴史に関するコンテンツの作成・整理（Issuesなし：詳細な作業記録は残されていない）
- 2020年11月に作成・更新されており、短期間での初期コンテンツ整備が行われた

## 使用技術・ツール
- GitHub（コンテンツ管理・公開）
- プログラミング言語：なし（language: null）

## 得られた知見
ジオキャッシングはGPS技術の民間開放（2000年）を契機に普及した位置情報ゲームであり、その歴史を整理することで、GPSや位置情報技術が一般社会へ浸透してきた経緯を地理情報の教育文脈で活用できる。研究室の授業・ゼミ向けの調査レポートとして、位置情報サービスの歴史的背景を学ぶ教材として転用可能。

## 未解決事項・課題
Issuesが存在せず、コンテンツの完成度・公開状況・その後の更新有無が不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/history-of-Geocaching
- Issues: https://github.com/furuhashilab/history-of-Geocaching/issues

---
repo_name: "startbootstrap-clean-blog-jekyll"
repo_url: "https://github.com/furuhashilab/startbootstrap-clean-blog-jekyll"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-09-28"
repo_updated_at: "2020-10-05"
distilled_at: "2026-05-25"
language: "HTML"
homepage: "https://furuhashilab.github.io/startbootstrap-clean-blog-jekyll/"
tags:
  - "graphic-recording"
  - "jekyll"
  - "portfolio"
confidence: "medium"
---

# startbootstrap-clean-blog-jekyll

## 概要
StartBootstrapのClean Blog Jekyllテーマをフォークし、古橋研究室の「グラレコ部」のポートフォリオサイトとして構築したリポジトリ。GitHub Pagesで公開されており、グラフィックレコーディング作品の展示・発信を目的としている。MITライセンスのOSSテーマをカスタマイズして研究室活動の成果発信に活用した事例。

## 主な活動・成果
- グラレコ部のポートフォリオサイトをJekyll＋GitHub Pagesで構築・公開
- Issue #1「画像 2020/09/28」（コメント6件）・Issue #2「画像 2020/08/22」（コメント4件）にてグラレコ画像の投稿・レビューをIssue上で実施
- 画像素材の収集・掲載作業をShogoHirasawaが主導し、Issueをギャラリー的に活用

## 使用技術・ツール
- Jekyll：静的サイトジェネレータ
- StartBootstrap Clean Blog テーマ（MITライセンス）
- GitHub Pages：サイト公開・ホスティング
- HTML（主要言語）
- GitHub Issues：画像レビュー・素材管理の場として活用

## 得られた知見
OSSのJekyllテーマをフォークしてGitHub Pagesで公開することで、研究室のグラレコ部ポートフォリオサイトを短期間かつ低コストで構築できる。また、GitHub IssueをグラレコPNG画像の投稿・フィードバック場として活用するワークフローは、コードを書かないメンバーも参加しやすい成果物管理の手法として転用可能。

## 未解決事項・課題
Issue #1・#2がいずれもオープンのままで、掲載画像の最終確定・サイトへの反映状況が不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/startbootstrap-clean-blog-jekyll
- Issues: https://github.com/furuhashilab/startbootstrap-clean-blog-jekyll/issues
- 関連サイト: https://furuhashilab.github.io/startbootstrap-clean-blog-jekyll/

---
repo_name: "fieldart4gachamuku"
repo_url: "https://github.com/furuhashilab/fieldart4gachamuku"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-09-28"
repo_updated_at: "2020-09-28"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "ingress"
  - "field-art"
  - "location-based-game"
confidence: "high"
---

# fieldart4gachamuku

## 概要
古橋研究室の映像制作ユニット「ガチャムク」を題材にした、位置情報ゲーム「Ingress」のフィールドアート作品を制作するプロジェクト。Ingressのポータルを結んで地図上に巨大なイラストを描くフィールドアートの手法で、ガチャムクのキャラクター（ガチャピン・ムック）を表現することを目的としていた。マイルストーン「2020/10/5」が設定されており、短期集中型のプロジェクトとして運営された。

## 主な活動・成果
- マイルストーン（2020/10/5）を設定し、5つのタスクIssueをラベル・アサインで管理
- プレゼン作り（sy7676担当、ラベル：プレゼン）のタスクを設定
- ミーティングIssue（ラベル：meeting）で全メンバー（ShogoHirasawa・sy7676・plinplin22・naoki2123）を招集・調整
- Medium記事による成果発信（naoki2123担当、ラベル：documentation）を計画
- ガチャピンの作成（sy7676・plinplin22・naoki2123担当、ラベル：work）をタスク化
- グラレコの作成（ShogoHirasawa担当、ラベル：documentation）を並行タスクとして設定

## 使用技術・ツール
- Ingress：Nianticの位置情報AR型ゲーム（フィールドアートのプラットフォーム）
- GitHub Issues（ラベル・マイルストーン・アサインによるタスク管理）
- Medium（成果発信ブログ）
- プログラミング言語：なし（language: null）

## 得られた知見
Ingressフィールドアートは、GPS座標上にあるポータルを計画的に結ぶことで地図上に巨大なキャラクターイラストを描く表現手法であり、地理情報技術を創作活動に応用する好事例。GitHubのラベル（work・documentation・meeting・プレゼン）とマイルストーンを組み合わせることで、クリエイティブな短期プロジェクトでも役割分担と締切管理を可視化できる。

## 未解決事項・課題
全5件のIssueがマイルストーン期限（2020/10/5）を過ぎてもオープンのままであり、フィールドアート作品の実施・完成状況、Medium記事の公開状況が不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/fieldart4gachamuku
- Issues: https://github.com/furuhashilab/fieldart4gachamuku/issues

---
repo_name: "grareco4gachamuku"
repo_url: "https://github.com/furuhashilab/grareco4gachamuku"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-09-28"
repo_updated_at: "2020-09-28"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "graphic-recording"
  - "gachamuku"
  - "illustration"
confidence: "high"
---

# grareco4gachamuku

## 概要
グラフィックレコーディング（グラレコ）で使えるガチャムクキャラクター素材集を作成・管理するリポジトリ。防災・Covid-19・各サークルロゴなどをガチャムクキャラクターバージョンでイラスト化し、グラレコ制作者が汎用的に使える素材として整備することを目的としている。あわせてガチャムクの「絵描き歌動画」の制作も並行タスクとして管理されていた。

## 主な活動・成果
- Issue #2「使いやすいガチャムクグラレコ素材集作成」（yukiohgishi・Ayaka0324担当、コメント4件）にて以下の素材を全て完成：
  - 防災「おかしも」ガチャムクver.
  - Covid-19関連素材ガチャムクver.
  - サークルロゴ①（ドローン・ユース・位置ゲー・横瀬）ガチャムクver.
  - サークルロゴ②（ものづくり・グラレコ・空間デザイン・TEDx）ガチャムクver.
- Issue #1「ガチャムク絵描き歌動画作成」（yukiohgishi・Ayaka0324担当、コメント3件）として動画制作タスクを並行管理

## 使用技術・ツール
- グラフィックレコーディング（手描き・デジタルイラスト）
- GitHub Issues（チェックリスト形式でのタスク進捗管理）
- プログラミング言語：なし（language: null）

## 得られた知見
GitHub IssueのMarkdownチェックリスト（`- [x]`）形式は、複数のイラスト素材を一括管理・進捗確認する手法として非常に有効。グラレコ素材をGitHubリポジトリで一元管理することで、複数メンバー間での素材共有・バージョン管理が容易になる。また、防災・感染症対策・各種サークル活動など多様なテーマをキャラクターイラスト化して素材化することで、グラレコの表現の幅と制作スピードを向上させるアプローチは他コミュニティでも転用可能。

## 未解決事項・課題
Issue #2は全チェックリスト完了済みながらオープンのままクローズされておらず、Issue #1「絵描き歌動画作成」も未クローズのため完成状況が不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/grareco4gachamuku
- Issues: https://github.com/furuhashilab/grareco4gachamuku/issues

---
repo_name: "www_tedxagu"
repo_url: "https://github.com/furuhashilab/www_tedxagu"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-09-20"
repo_updated_at: "2020-10-05"
distilled_at: "2026-05-25"
language: "PHP"
homepage: null
tags:
  - "tedx"
  - "website"
  - "wordpress"
confidence: "medium"
---

# www_tedxagu

## 概要
青山学院大学のTEDxイベント「TEDxAGU」の公式ウェブサイトをメンテナンスするためのリポジトリ。tedxaguオーガナイゼーションのリポジトリを古橋研究室がフォークし、サイト保守・更新作業を担当していたと推察される。PHPで構築されたWordPress系サイトをGitHub Pages経由で管理する構成。

## 主な活動・成果
- TEDxAGUウェブサイト（tedxagu/www_tedxagu）のフォークを取得し、furuhashilab配下で保守管理
- GitHub Pagesによるサイト公開設定（`has_pages: true`）
- （Issuesなし：`has_issues: false`のため、具体的な作業記録は親リポジトリ側で管理）

## 使用技術・ツール
- PHP（主要言語）：WordPressベースのウェブサイト構築
- GitHub Pages：サイトホスティング
- Git / GitHub：バージョン管理・フォーク運用

## 得られた知見
イベント系ウェブサイトの保守管理において、本体リポジトリ（tedxagu組織）をforkして別組織（furuhashilab）でミラー管理する手法は、権限分離とバックアップを兼ねた運用として有効。`has_issues: false`の設定により、Issueは親リポジトリ側に集約され、フォーク側はコード管理専用に役割分担される設計パターンが確認できる。

## 未解決事項・課題
特になし（Issuesは無効化されており、作業記録は親リポジトリ側で管理）。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/www_tedxagu
- Issues: https://github.com/furuhashilab/www_tedxagu/issues

---
repo_name: "editor-layer-index"
repo_url: "https://github.com/furuhashilab/editor-layer-index"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-09-13"
repo_updated_at: "2020-09-13"
distilled_at: "2026-05-25"
language: null
homepage: "https://osmlab.github.io/editor-layer-index/"
tags:
  - "openstreetmap"
  - "imagery"
  - "tms"
confidence: "high"
---

# editor-layer-index

## 概要
OpenStreetMap（OSM）エディタ向けの統合レイヤーインデックス（osmlab/editor-layer-index）を古橋研究室がフォークしたリポジトリ。TMS・WMSなどの航空写真・背景地図レイヤー情報をJSONで一元管理するOSSプロジェクトへの貢献・カスタマイズを目的としていると推察される。親リポジトリは現在も活発に更新されているOSMエコシステムの重要なインフラ。

## 主な活動・成果
- osmlab/editor-layer-indexをforkし、furuhashilab配下で管理
- （Issuesは無効化・空のため、具体的な作業記録なし）
- フォーク後の独自変更内容は不明（サイズ差：親96KB→フォーク96KB、ほぼ同一）

## 使用技術・ツール
- JSON（親リポジトリの主要言語）：レイヤー定義ファイルの記述
- TMS（Tile Map Service）・WMS（Web Map Service）：地図タイル配信プロトコル
- OpenStreetMap エコシステム：iD・JOSM等のOSMエディタとの連携
- GitHub Pages：インデックスの公開

## 得られた知見
editor-layer-indexはOSMエディタが参照する背景航空写真・地図タイルのカタログであり、新たな地域の航空写真をOSMコミュニティへ提供する際はこのインデックスへのPull Requestが標準的な手順となる。古橋研究室がフォークを保持していることから、日本国内の独自タイルソース（国土地理院等）の追加・検証をローカルで試す用途が想定される。

## 未解決事項・課題
Issuesが無効化されており、フォーク後にどのような変更・貢献が行われたか（あるいは行われなかったか）が不明。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/editor-layer-index
- Issues: https://github.com/furuhashilab/editor-layer-index/issues
- 関連サイト: https://osmlab.github.io/editor-layer-index/

---
repo_name: "workdata4gatsby"
repo_url: "https://github.com/furuhashilab/workdata4gatsby"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-09-13"
repo_updated_at: "2020-09-13"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "tedx"
  - "gatsby"
  - "static-site"
confidence: "medium"
---

# workdata4gatsby

## 概要
TEDxAGUのウェブサイト構築に使用するGatsbyJS向けの作業データを管理するリポジトリ。tedxaguオーガナイゼーションの同名リポジトリ（tedxagu/workdata4gatsby）を古橋研究室がフォークしたもので、TEDxAGUサイトのコンテンツデータや静的サイト生成に必要なワークデータを格納していると推察される。MITライセンスで公開。

## 主な活動・成果
- tedxagu/workdata4gaussをforkし、furuhashilab配下で管理
- Issuesは無効化（`has_issues: false`）されており、作業記録は親リポジトリ側で管理
- フォーク後の独自変更はほぼなし（フォーク時点のサイズ92KB、親は127KB）

## 使用技術・ツール
- Gatsby.js：React ベースの静的サイトジェネレータ（リポジトリ名より推定）
- HTML（親リポジトリの主要言語）
- MIT License
- GitHub（バージョン管理・フォーク運用）

## 得られた知見
TEDxAGUのウェブサイト関連リポジトリ（www_tedxagu・workdata4gatsby）を古橋研究室がforkして並行管理している構成から、研究室がTEDxAGUの技術サポートを担う役割を持っていたことが読み取れる。Gatsbyのようなモダン静的サイトジェネレータとGitHubを組み合わせることで、イベントサイトのコンテンツ更新をコードとして管理するアプローチは、研究室活動やイベント系サイト全般に転用できる。

## 未解決事項・課題
特になし（Issuesは無効化されており、descriptionも空のため詳細な目的は不明）。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/workdata4gatsby
- Issues: https://github.com/furuhashilab/workdata4gatsby/issues

---
repo_name: "onlineclasses"
repo_url: "https://github.com/furuhashilab/onlineclasses"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-08-29"
repo_updated_at: "2020-08-31"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "online-education"
  - "remote-learning"
  - "covid-19"
confidence: "medium"
---

# onlineclasses

## 概要
古橋研究室のオンライン授業用リソースを管理するリポジトリ。2020年8月末に作成されており、新型コロナウイルス感染拡大に伴うオンライン授業移行期に対応する教材・情報共有を目的として整備されたと推察される。CC0-1.0ライセンス（パブリックドメイン相当）で公開されており、誰でも自由に利用・改変できる形式をとっている。

## 主な活動・成果
- オンライン授業向けリソースの整備（Issuesなし：詳細な作業記録は残されていない）
- CC0-1.0ライセンスによる完全オープンな教育コンテンツとして公開
- リポジトリサイズが10KBと小規模であり、テキスト系コンテンツ（README・リンク集等）が主体と推察

## 使用技術・ツール
- GitHub（コンテンツ管理・公開）
- Creative Commons Zero v1.0 Universal（CC0ライセンス）
- プログラミング言語：なし（language: null）

## 得られた知見
オンライン授業リソースをCC0でGitHub公開することで、他の教員・研究者が自由に転用・改変できる教育コモンズとして機能させるアプローチは、特に緊急時の知識共有モデルとして有効。CC0（著作権放棄）はCC BY等と異なり帰属表示すら不要なため、教育現場での素材流通コストを最小化できる。

## 未解決事項・課題
特になし（Issuesなし、コンテンツの詳細は不明）。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/onlineclasses
- Issues: https://github.com/furuhashilab/onlineclasses/issues

---
repo_name: "gatsby-starter-overflow"
repo_url: "https://github.com/furuhashilab/gatsby-starter-overflow"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-08-25"
repo_updated_at: "2020-09-07"
distilled_at: "2026-05-25"
language: null
homepage: "https://furuhashilab.github.io/gatsby-starter-overflow/"
tags:
  - "gatsby"
  - "static-site"
  - "starter-template"
confidence: "high"
---

# gatsby-starter-overflow

## 概要
HTML5 UPの「overflow」テーマをベースにしたGatsby.js V2スターターテンプレート（anubhavsrivastava/gatsby-starter-overflow）を古橋研究室がフォークしたリポジトリ。TEDxAGUサイト関連（workdata4gatsby・www_tedxagu）と同時期に作成されており、TEDxAGUまたは研究室サイト向けのGatsbyベースウェブサイト構築を試みた際のテンプレートとして活用されたと推察される。GitHub Pagesで公開済み。

## 主な活動・成果
- anubhavsrivastava/gatsby-starter-overflowをforkし、GitHub Pages（furuhashilab.github.io/gatsby-starter-overflow/）でデモ公開
- Issuesは無効化（`has_issues: false`）されており、具体的な作業記録なし
- フォーク後の独自変更はごくわずか（サイズ差：親5057KB→フォーク5097KB）

## 使用技術・ツール
- Gatsby.js V2：Reactベース静的サイトジェネレータ
- HTML5 UP overflow テーマ：デザインベーステンプレート
- SCSS（親リポジトリの主要言語）：スタイリング
- GitHub Pages：サイトホスティング

## 得られた知見
Gatsby.jsのスターターテンプレートをforkしてGitHub Pagesに公開するワークフローは、研究室やイベントの紹介サイトを最小コストで立ち上げる手法として有効。スターターテンプレートの選定→fork→GitHub Pages公開という3ステップで、デザイン済みのサイトを即座に稼働させられる。TEDxAGU関連の複数リポジトリ（www_tedxagu・workdata4gatsby・本リポジトリ）を組み合わせたサイト構築の試行が読み取れる。

## 未解決事項・課題
特になし（Issuesは無効化、独自カスタマイズの内容・範囲が不明）。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/gatsby-starter-overflow
- Issues: https://github.com/furuhashilab/gatsby-starter-overflow/issues
- 関連サイト: https://furuhashilab.github.io/gatsby-starter-overflow/

---
repo_name: "tsuda2020gis"
repo_url: "https://github.com/furuhashilab/tsuda2020gis"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-08-04"
repo_updated_at: "2020-08-16"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "gis"
  - "education"
  - "tsuda-university"
confidence: "high"
---

# tsuda2020gis

## 概要
津田塾大学での2020年度「地理情報システム（GIS）入門」授業を支援するリポジトリ。古橋研究室（furuhashilab）が他大学向けにGIS入門教育を提供した際の教材・リソース管理を目的として作成された。2020年8月の短期間に作成・更新されており、夏季集中講義や特別授業として実施されたと推察される。

## 主な活動・成果
- 津田塾大学2020年度GIS入門授業向けリソースの整備・公開
- （Issuesなし：詳細な作業記録は残されていない）
- リポジトリサイズ11KBと小規模であり、シラバス・リンク集・READMEなどテキスト系コンテンツが主体と推察

## 使用技術・ツール
- GIS（地理情報システム）：授業主題
- GitHub（教材管理・公開）
- プログラミング言語：なし（language: null）

## 得られた知見
GIS入門授業の教材をGitHubで管理・公開することで、受講生が授業外でもアクセスしやすい環境が整備できる。古橋研究室が自大学（青山学院大学）以外の大学（津田塾大学）向けにもGIS教育を提供していることは、地理情報教育のアウトリーチ活動として注目に値する。年度・大学名をリポジトリ名に含める命名規則（tsuda2020gis）は、複数大学・複数年度の授業管理を行う際の識別性を高める有効な手法。

## 未解決事項・課題
特になし（Issuesなし、コンテンツの詳細は不明）。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/tsuda2020gis
- Issues: https://github.com/furuhashilab/tsuda2020gis/issues

---
repo_name: "japanese-addresses"
repo_url: "https://github.com/furuhashilab/japanese-addresses"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-08-06"
repo_updated_at: "2020-08-06"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "open-data"
  - "japanese-address"
  - "geolonia"
confidence: "high"
---

# japanese-addresses

## 概要
全国の町丁目レベル（189,540件）の住所データをオープンデータとして提供するGeoloniaのリポジトリ（geolonia/japanese-addresses、スター数763）を古橋研究室がフォークしたもの。日本全国の住所データをCSV・JSON形式で利用可能なオープンデータセットで、地理情報システムや住所ジオコーディングの研究・開発に活用できる。MITライセンス。

## 主な活動・成果
- geolonia/japanese-addressesをforkし、furuhashilab配下で管理
- Issuesは無効化（`has_issues: false`）されており、独自の作業記録なし
- フォーク時点（2020年8月）のデータ件数：189,540件（現在の親リポジトリは277,191件に拡充）

## 使用技術・ツール
- JavaScript（親リポジトリの主要言語）：データ処理・変換スクリプト
- CSV・JSON：住所データフォーマット
- 国土交通省 位置参照情報ダウンロードサービス：データソース
- MIT License

## 得られた知見
日本全国の町丁目レベル住所データがMITライセンスのオープンデータとして入手できることは、地理情報研究・住所ジオコーディング・マッピング教育において非常に有用。フォーク時点（189,540件）から現在（277,191件）へのデータ拡充の速度からも、このデータセットが継続的にメンテナンスされている信頼性の高いリソースであることがわかる。

## 未解決事項・課題
特になし（Issuesは無効化、独自カスタマイズなし）。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/japanese-addresses
- Issues: https://github.com/furuhashilab/japanese-addresses/issues

---
repo_name: "website"
repo_url: "https://github.com/furuhashilab/website"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-05-08"
repo_updated_at: "2020-05-18"
distilled_at: "2026-05-25"
language: "JavaScript"
homepage: "https://furuhashilab.github.io/website/jp/"
tags:
  - "mapswipe"
  - "localization"
  - "github-pages"
confidence: "medium"
---

# website

## 概要
本リポジトリは、古橋研究室が MapSwipe の公式ウェブサイト（mapswipe/website-old）をフォークし、日本語話者向けにローカライズするために作成したテスト用サイトである。GitHub Pages を利用して日本語版ページを公開することを目的としており、元サイトの構造を維持しながら日本語対応を試みている。Issues の内容から、学生メンバーが実際に編集・検証作業を行っていたことが読み取れる。

## 主な活動・成果
- MapSwipe 公式サイトを fork し、日本語ローカライズ版として GitHub Pages で公開（`/jp/` パス）
- ナビゲーションタブ（about、get involved 等）の日本語訳作業を実施
- 日本語訳を適用した際に元サイト（本家）のタブにも影響が出るという翻訳スコープの問題を発見・Issue 化（#2）
- img ディレクトリ内の画像が表示されない不具合を発見・Issue 化（#4）

## 使用技術・ツール
- JavaScript（主要言語）
- GitHub Pages（静的サイトホスティング）
- Git / GitHub（バージョン管理・Issue トラッキング）
- HTML / CSS（MapSwipe ウェブサイトのベース構造）

## 得られた知見
- 既存サイトを fork してローカライズする際、翻訳対象のスコープ（ページ単位 vs サイト全体）を事前に設計しないと、元サイトの構造にも意図せず影響を及ぼすリスクがある。言語別ディレクトリ分離や i18n ライブラリの活用など、翻訳の独立性を担保する設計が重要である。
- 画像パスは fork 元と fork 先でルートが異なる場合があるため、静的アセットのパス解決を fork 直後に検証する習慣が有効である。

## 未解決事項・課題
- ナビゲーションタブの日本語訳が本家サイトにも影響する問題（Issue #2）が未解決のままクローズされていない
- img ディレクトリ内の画像が表示されない不具合（Issue #4）も未解決

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/website
- Issues: https://github.com/furuhashilab/website/issues
- 関連サイト: https://furuhashilab.github.io/website/jp/

---
repo_name: "sl"
repo_url: "https://github.com/furuhashilab/sl"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-06-30"
repo_updated_at: "2020-06-30"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "unix"
  - "cli"
  - "joke-program"
confidence: "high"
---

# sl

## 概要
`sl` は、Unix/Linux 環境でコマンドラインの誤タイプ（`ls` を `sl` と打ってしまうミス）を矯正するためのジョークプログラムである。`sl` と入力するとターミナル上に蒸気機関車のアスキーアートが走り抜けるアニメーションが表示され、ユーザーに誤タイプを気づかせる仕掛けになっている。古橋研究室は mtoyoda 氏によるオリジナルリポジトリ（GitHub で 3,000 以上のスターを持つ著名な OSS）を fork して保有しており、研究室メンバーへの Linux 入門・コマンドライン教育の文脈で活用されたと考えられる。

## 主な活動・成果
- mtoyoda/sl（著名な Unix ジョークコマンド）を研究室組織アカウントに fork
- Issues は無効化されており、独自の開発・改変の記録はない
- fork 後に独自のコミットは行われておらず、教育・参照目的での取り込みとみられる
- 研究室内から 4 件の fork が派生しており、学生個人が手元環境で試した形跡がある

## 使用技術・ツール
- C言語（元リポジトリの主要言語）
- ncurses（ターミナル上のアスキーアートアニメーション描画）
- Unix / Linux コマンドライン環境
- Git / GitHub（fork による配布・管理）

## 得られた知見
- コマンドラインの誤タイプ矯正という実用とユーモアを組み合わせたアプローチは、初学者への Linux 教育において導入のとっかかりとして有効である。著名な OSS を fork して研究室アカウントに置くことで、学生が `git clone` や fork の概念を体験的に学ぶ教材としても機能する。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/sl
- Issues: https://github.com/furuhashilab/sl/issues

---
repo_name: "Safecast"
repo_url: "https://github.com/furuhashilab/Safecast"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-04-09"
repo_updated_at: "2020-04-09"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "safecast"
  - "radiation"
  - "open-data"
confidence: "medium"
---

# Safecast

## 概要
本リポジトリは、古橋研究室が Safecast に関連する調査・研究活動を管理するために作成したものである。Safecast は東日本大震災後の放射線量データを市民が分散収集・公開するオープンデータプロジェクトであり、古橋研究室はこのプロジェクトと連携した研究・教育活動を行っている。リポジトリ自体は非常に小規模（3KB）で作成直後から更新が止まっており、メモや資料の管理を目的とした初期段階のリポジトリとみられる。

## 主な活動・成果
- Safecast プロジェクトに関連する資料・情報をまとめるリポジトリを新規作成
- Issues・コメントの記録はなく、公開活動の記録は残っていない
- 作成から約半日でプッシュが止まっており、試験的な立ち上げにとどまった可能性が高い

## 使用技術・ツール
- Git / GitHub（リポジトリ管理）
- Safecast API・オープンデータ（関連プロジェクト）

## 得られた知見
- Safecast のような市民科学型オープンデータプロジェクトは、研究室が地域・社会課題と接続する際の有力な連携先となる。放射線量データのような時空間データを扱う研究では、データ収集の仕組みと可視化・解析パイプラインを切り分けて設計することが重要である。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/Safecast
- Issues: https://github.com/furuhashilab/Safecast/issues

---
repo_name: "gsclocalguide"
repo_url: "https://github.com/furuhashilab/gsclocalguide"
genre: "other"
genre_label: "その他"
repo_created_at: "2018-07-10"
repo_updated_at: "2020-04-07"
distilled_at: "2026-05-25"
language: "HTML"
homepage: "http://gsclocalguide.furuhashilab.com"
tags:
  - "localwiki"
  - "local-guide"
  - "crowdsourcing"
confidence: "high"
---

# gsclocalguide

## 概要
本リポジトリは、古橋研究室が運営する GSC（Global Sensing Consortium または学内活動）のローカルガイドプロジェクトを管理するものである。学生が首都圏各地のおすすめ飲食店・カフェを実地調査し、LocalWiki（`ja.localwiki.org/agu`）にポイントデータと詳細情報を登録・集約する市民参加型の地域情報収集活動である。GitHub Pages でガイドサイトを公開しており、2018年から継続的に運用されている。

## 主な活動・成果
- 学生が淵野辺・町田・横浜・渋谷・新宿など首都圏50地区以上を対象に飲食店の実地調査を実施
- 調査結果を LocalWiki（`ja.localwiki.org/agu`）に個別ページとして登録し、位置情報（緯度・経度）も付与
- 重複調査を管理するためのページ命名規則（「店名+年度+季節+調査者名」）を策定・運用
- Issue #2 にて LocalWiki へのページ新規作成・地図ポイント登録手順をマニュアルとして整備
- Issue #1 にてサイトのブラッシュアップ（データ更新・目的別使い分け）を課題として提起

## 使用技術・ツール
- HTML（主要言語）
- LocalWiki（地域情報 Wiki プラットフォーム、`ja.localwiki.org`）
- GitHub Pages（静的サイトホスティング）
- Git / GitHub（バージョン管理・Issue による作業管理）

## 得られた知見
- 複数人が同一対象を調査する際のページ命名規則（店名＋年度＋季節＋調査者名）を事前に設計することで、LocalWiki 上の重複や混乱を防ぐことができる。学生参加型のフィールド調査では、データ登録の標準化・マニュアル整備が品質担保の鍵となる。また、GitHub Issues を調査票・マニュアル置き場として活用することで、非エンジニアの学生でも参照しやすい運用が実現できる。

## 未解決事項・課題
- Issue #1「GSC Local Guide ブラッシュアップ」（データ更新・目的別使い分け）が未解決のままクローズされていない
- Issue #2「LocalWiki ソースコード」も未クローズ

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/gsclocalguide
- Issues: https://github.com/furuhashilab/gsclocalguide/issues
- 関連サイト: http://gsclocalguide.furuhashilab.com

---
repo_name: "ventilator"
repo_url: "https://github.com/furuhashilab/ventilator"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-03-29"
repo_updated_at: "2020-03-29"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "open-source-hardware"
  - "covid-19"
  - "papr"
confidence: "high"
---

# ventilator

## 概要
本リポジトリは、COVID-19 パンデミック初期（2020年3月）に医療機器不足への対応として世界的に注目された低コスト・オープンソース人工呼吸器（または PAPR：電動ファン付き呼吸用保護具）の設計リポジトリ jcl5m1/ventilator を古橋研究室が fork したものである。fork 元は GitHub で 1,600 以上のスターを獲得した注目度の高いプロジェクトであり、研究室がオープンソースハードウェアの動向を追跡・参照する目的で取り込んだとみられる。

## 主な活動・成果
- jcl5m1/ventilator（低コスト人工呼吸器・PAPR 設計）を研究室アカウントに fork
- Issues は無効化されており、研究室独自の改変や実装活動の記録はない
- fork 日時（2020年3月29日）はコロナ禍の医療機器不足が深刻化していた時期と一致しており、緊急時のオープンソースハードウェア活動への関心の表れとみられる
- fork 元は Jupyter Notebook を用いた設計シミュレーションや回路・部品リストを含む包括的なドキュメントで構成されている

## 使用技術・ツール
- Jupyter Notebook（fork 元の主要言語、設計シミュレーション・ドキュメント）
- オープンソースハードウェア設計（回路図・部品リスト）
- PAPR / 人工呼吸器の機械設計
- Git / GitHub（fork による情報収集・管理）

## 得られた知見
- 緊急・災害時においてオープンソースコミュニティが医療機器設計情報を GitHub で迅速に共有・改良する動きは、研究機関が人道支援や危機対応に貢献できる新しい形態である。Jupyter Notebook を設計ドキュメントとして活用することで、シミュレーションと説明文を一体化した再現性の高い技術共有が可能になる。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/ventilator
- Issues: https://github.com/furuhashilab/ventilator/issues

---
repo_name: "postal-code-api"
repo_url: "https://github.com/furuhashilab/postal-code-api"
genre: "other"
genre_label: "その他"
repo_created_at: "2020-06-01"
repo_updated_at: "2020-06-01"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "postal-code"
  - "japan-address"
  - "open-api"
confidence: "high"
---

# postal-code-api

## 概要
本リポジトリは、日本の郵便番号から住所情報を取得できる Postal Code API（madefor/postal-code-api）を古橋研究室が fork したものである。fork 元は GitHub で 450 以上のスターを持つ実績あるオープン API 実装であり、郵便番号と住所データを JSON 形式で静的に配信する仕組みを提供している。研究室での地図・GIS 関連プロジェクトにおいて、住所ジオコーディングの前処理や位置情報付与の補助ツールとして参照・活用する目的で取り込んだとみられる。

## 主な活動・成果
- madefor/postal-code-api を研究室アカウントに fork
- Issues は無効化されており、研究室独自の改変・活動の記録はない
- fork 元は 2016年から継続メンテナンスされており、日本の郵便番号データを静的 JSON として GitHub Pages で配信する設計が特徴的

## 使用技術・ツール
- JavaScript（fork 元の主要言語）
- 静的 JSON API（郵便番号→住所の変換データ）
- GitHub Pages（API データのホスティング）
- 日本郵便の郵便番号データ（データソース）
- Git / GitHub（fork による管理）

## 得られた知見
- 郵便番号と住所の変換データを静的 JSON として GitHub Pages で配信する設計は、サーバーレスで維持コストゼロの API 提供手法として有効である。地図・GIS アプリケーションで住所入力の補完や位置情報付与を行う際、外部有料サービスに依存せず自己ホスト可能なオープンデータ活用の好例である。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/postal-code-api
- Issues: https://github.com/furuhashilab/postal-code-api/issues



---
geomedia4gsc_grareco

概要

本リポジトリは「空間情報特殊講義（関さん担当）」のために作られた公開リポジトリである。青山学院大学地球社会共生学部（gsc-aoyama）の授業用リポジトリ geomedia4gsc を古橋研究室（furuhashilab）がフォークしたものであり、講義資料や学習コンテンツの共有・管理を目的としている。フォーク元は2017年に作成され、本フォークは2019年に派生した。

主な活動・成果

- 青山学院大学の空間情報特殊講義向けに、フォーク元リポジトリ（gsc-aoyama/geomedia4gsc）を古橋研究室組織アカウント配下に複製・管理
- Issues機能は本フォークでは無効化されており、議論・作業はフォーク元または別チャネルで行われていたと推定される
- 最終コミットは2020年1月であり、講義期間に対応した一時的な運用リポジトリとして機能したと考えられる

使用技術・ツール

- GitHub（リポジトリ管理・フォーク運用）
- Git（バージョン管理）
- 主要言語：なし（languageフィールドがnull。テキスト・資料系コンテンツが中心と推定）

得られた知見

- 授業用リポジトリをフォークして組織アカウント配下で管理することで、元リポジトリへの影響なく講義運営側が独自に資料を管理・配布できる。この「フォーク＋組織アカウント運用」パターンは、教育機関での GitHub 活用において再現性の高い手法である。
- Issuesを無効化したフォークリポジトリでは、議論の追跡が難しくなるため、授業の質問・議論窓口を別途（Slack、Google Classroom等）明示しておく必要がある。

未解決事項・課題

- Issuesが無効化されているため、授業内での議論・質疑応答の記録が本リポジトリ上に残っていない。フォーク元（gsc-aoyama/geomedia4gsc）には8件のオープンIssueが存在しており、そちらに活動が集約されている可能性がある。

参考リンク

- リポジトリ: https://github.com/furuhashilab/geomedia4gsc_grareco
- Issues: https://github.com/furuhashilab/geomedia4gsc_grareco/issues
- フォーク元リポジトリ: https://github.com/gsc-aoyama/geomedia4gsc



---


---
repo_name: "README"
repo_url: "https://github.com/furuhashilab/README"
genre: "other"
genre_label: "その他"
repo_created_at: "2017-09-12"
repo_updated_at: "2026-05-21"
distilled_at: "2026-05-25"
language: null
homepage: "http://furuhashilab.com/"
tags:
  - "furuhashilab"
  - "opensourcemapping"
  - "geospatial-education"
confidence: "high"
---

# README

## 概要
古橋研究室（青山学院大学地球社会共生学部）の学生向け総合ガイドリポジトリ。研究室に興味のある学生・所属学生が最初に読むべき公式ルール・ノウハウ・イベント情報を一元管理する場として2017年に作成された。「一億総伊能化社会の実現」をビジョンに掲げ、地図・位置情報・OSM（OpenStreetMap）・ドローン・生成AIなど幅広い技術領域を横断する実践的教育活動の基盤となっている。

## 主な活動・成果
- 毎年度のオンラインハッカソン（2020〜2025-2026年度）を研究室内イベントとして定期開催。チームごと5分LT形式での成果発表、Zoomライブストリーミング、公式ブログへのグラレコ付き報告が必須とされている
- 生成AI利用ガイドライン v1.2.0 を策定・運用中。使用AIのバージョン・日付の明記、ハルシネーション3アウト制、AI生成画像へのアイコン付与などを義務化。ChatGPT・Gemini・Grok・Copilot等を用いてガイドライン自体もアップデートしている
- 「古橋研究室スタンダード v0.41」として学生が習得すべき共通スキル（GitHub、Markdown、Creative Commons、フィールドワークアプリ、位置情報ゲーム基礎等）を体系化
- 卒論/ゼミ論ルールをGitHub上で管理し、IMRaD型構成・CC BY 4.0ライセンス・GitHub Pages公開を標準化
- 留学フィールドスタディ課題としてStrava・Mapillary・ストーリーテリング地図ツール（Mapbox Storytelling、Re:Earth、Cesium ION等）を活用した成果物提出を義務付け
- 国際会議参加ルール・ゼミ内サークルルール・合宿装備規定・データ/機材管理ルール・SNSリテラシー講座などをIssue上で継続的に整備
- 朝日新聞取材向け広報コンテンツ（OSMウクライナ支援マッピング活動）や国際人道支援マパソン（International Humanitarian Mapathon）への参加記録も管理

## 使用技術・ツール
- 地図・位置情報: OpenStreetMap、Mapillary、Strava、Organic Maps、Google Earth Web、Mapbox Storytelling、Re:Earth、PLATEAU VIEW、Cesium ION、Esri StoryMaps、GeoJSON.io
- ドローン: DJI Fly、PIX4DcapturePro、Dronelink
- 位置情報ゲーム: Ingress Prime、IITC-Mobile、Pokémon GO
- 生成AI: ChatGPT、Gemini、Grok、GitHub Copilot、Microsoft Copilot、Claude、Midjourney、DeepSeek（ローカル運用）
- コミュニケーション: Slack、Medium（公式ブログ）、Facebook、Zoom、Instagram、LinkedIn
- 開発・管理: GitHub（Issues / Projects / Pages / Actions / Copilot）、Glide（PWAアプリ）、Google Spreadsheet
- デザイン・グラレコ: プロッキー、マイルドライナー、A3用紙
- ライセンス: CC BY 4.0、CC0、MIT、Apache、GPL v3

## 得られた知見
- **GitHubのIssueをWiki代わりに使うことで、ルール・ノウハウ・イベント記録を一元管理しバージョン管理できる。** 教育機関のゼミ運営においてもOSSの開発文化（Issues・Projects・Pages）を導入することで、透明性・継続性・検索性が大幅に向上する。
- 生成AI利用において「使用したAIの種類・バージョン・日付を必ず明記する」という運用ルールは、学術誠実性の担保と再現性確保のモデルケースとして他の教育機関・組織に転用できる。
- ICS（インシデント・コマンド・システム）の監督限界ルール（1サークル6名以内）を学生サークル運営に適用することで、責任範囲の明確化とスケーラブルな組織運営が実現できる。
- フィールドワーク成果をStrava・Mapillary・ストーリーテリング地図として公開し、Mediumブログに報告する一連のワークフローは、市民参加型GIS教育の実践モデルとして応用可能。

## 未解決事項・課題
- 位置情報ゲームの必須レベル基準（Pokémon GO の必要レベル）の更新議論（Issue #32）が未クローズのまま放置されている
- PWAアプリ（Glide）の学生成果物可視化・連絡先表示・ニュース投稿ルールなど複数の改善タスクが未完了（Issue #23）
- 「失敗と自分の判断での行動の仕方」についてのまとめが着手されていない（Issue #9）
- 全26件のIssueがオープン状態であり、完了・アーカイブの運用基準が明示されていない

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/README
- Issues: https://github.com/furuhashilab/README/issues
- 関連サイト: http://furuhashilab.com/

---
repo_name: "geoten"
repo_url: "https://github.com/furuhashilab/geoten"
genre: "other"
genre_label: "その他"
repo_created_at: "2026-05-12"
repo_updated_at: "2026-05-12"
distilled_at: "2026-05-25"
language: null
homepage: null
tags:
  - "geoten"
  - "furuhashilab"
  - "exhibition"
confidence: "medium"
---

# geoten

## 概要
古橋研究室が主催・参加する「ジオ展」（地理・位置情報をテーマにした展示イベント）の振り返りおよび情報共有を目的とした公開リポジトリ。2026年5月に開設されたばかりの新しいリポジトリで、ジオ展2026の成果・反省・引き継ぎ事項をIssueのコメントで参加者が各自記録する運用が行われている。ライセンスはCC0-1.0（パブリックドメイン）。

## 主な活動・成果
- ジオ展2026の振り返りIssue（#1）に21件のコメントが集積されており、参加メンバーが良かった点・反省点・引き継ぎ事項を各自記録
- ジオガチャ（位置情報をテーマにしたガチャ企画）を展示内で実施し、合計112回（11,200円分）が回された
- 振り返りIssueは2026-05-12〜05-14の間に活発に更新され、短期集中型の記録運用が行われた

## 使用技術・ツール
- GitHub Issues（振り返り・情報共有の場として活用）
- ジオガチャ（位置情報をテーマにした物理ガチャ企画）

## 得られた知見
- 展示イベント終了直後にGitHubのIssueを振り返り用の共有ノートとして開設し、参加者全員が1コメント以上を義務付ける運用は、短期間で多角的な振り返り情報を集約する手法として効果的。他のイベント・フィールドワーク後の情報整理にも転用できる。
- ジオガチャのような位置情報をテーマにした体験型コンテンツは来場者エンゲージメントの指標（回数・売上）として定量化しやすく、次回改善の基準になる。

## 未解決事項・課題
- Issue #1が引き続きオープン状態であり、振り返りの総括・クローズが行われていない
- topics（タグ）が未設定のため、リポジトリの発見性が低い

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/geoten
- Issues: https://github.com/furuhashilab/geoten/issues
---
repo_name: "PlacenameKaraoke"
repo_url: "https://github.com/furuhashilab/PlacenameKaraoke"
genre: "other"
genre_label: "その他"
repo_created_at: "2021-03-02"
repo_updated_at: "2026-05-10"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "placename"
  - "karaoke"
  - "toponymy"
confidence: "high"
---

# PlacenameKaraoke

## 概要
「地名縛りカラオケルール」を定義・整理するためのリポジトリ。歌詞中に地名を含む楽曲のみを選曲対象とするカラオケのハウスルールを、古橋研究室がGitHub上でオープンにドキュメント化したプロジェクトである。地名と楽曲の関係性を研究・遊戯両面から探求することを目的としており、NLPや地理情報の観点からも参照・発展が期待されている。

## 主な活動・成果
- カラオケルール用のビジュアル素材（画像）の収集・整理（Issue #1、Flickr CC BY 2.0素材を活用）
- 「鉄道唱歌」「女一人（デューク・エイセス）」「いーあるふぁんくらぶ（みきとP feat. GUMI）」など、地名を含む楽曲の草の根的なリストアップ（Issue #2）
- NLP分野の学術文献「乾(2023) 位置属性を有しない事物に対する地理的特定性の分析」をSpeakerDeckで参照・共有し、学術的背景の整備を開始（Issue #3）

## 使用技術・ツール
- GitHub Issues（ルール・事例の収集・議論の場として活用）
- Flickr（CC BY 2.0ライセンス画像の素材活用）
- SpeakerDeck（学術発表スライドの参照）
- プログラミング言語：なし（ドキュメント主体のリポジトリ）

## 得られた知見
- GitHubのIssuesは、コード管理のみならず、ルール策定・事例収集・参考文献管理など、人文・社会系の知識整理ツールとしても有効に活用できる。
- 地名を含む楽曲の収集は、民俗的・草の根的な情報収集と学術的アプローチ（NLP・地理情報学）を組み合わせることで、双方向に深めることができる。
- CC BY等のオープンライセンス素材をGitHub上で参照・共有することで、コンテンツの権利処理を透明化しながらプロジェクトを進めることができる。

## 未解決事項・課題
- Issue #1（画像素材整理）、Issue #2（草の根楽曲リスト）、Issue #3（参考文献整備）の3件がいずれもオープンのまま残っており、引き続き事例・文献の収集が継続課題となっている。
- 楽曲リストの体系的な整理・分類基準の策定には至っていない。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/PlacenameKaraoke
- Issues: https://github.com/furuhashilab/PlacenameKaraoke/issues
---
repo_name: "geogacha2026"
repo_url: "https://github.com/furuhashilab/geogacha2026"
genre: "other"
genre_label: "その他"
repo_created_at: "2026-04-23"
repo_updated_at: "2026-04-26"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "geogacha"
  - "geo-exhibition"
  - "sticker"
confidence: "low"
---

# geogacha2026

## 概要
古橋研究室が2026年に実施した「ジオガチャ」企画に関連するリポジトリ。地理・地図をテーマにしたイベント向けのガチャ形式コンテンツの管理・運営を目的として作成された。GitHubテンプレートリポジトリとして設定されており、類似企画への再利用が想定されている。

## 主な活動・成果
- ジオガチャ2026企画のリポジトリ立ち上げ・初期構築
- テンプレートリポジトリとして設定し、将来の類似イベントへの転用を想定した構成

## 使用技術・ツール
- GitHub（テンプレートリポジトリ機能を活用）
- プログラミング言語：なし（企画・管理主体のリポジトリ）

## 得られた知見
- GitHubのテンプレートリポジトリ機能を活用することで、年次イベントや繰り返し開催される企画の管理構成を標準化・再利用しやすくなる。

## 未解決事項・課題
- Issuesが1件オープンのまま（詳細は未確認）。descriptionも未設定であり、リポジトリの目的・概要の明文化が課題。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/geogacha2026
- Issues: https://github.com/furuhashilab/geogacha2026/issues
---
repo_name: "-SNS-"
repo_url: "https://github.com/furuhashilab/-SNS-"
genre: "other"
genre_label: "その他"
repo_created_at: "2026-04-21"
repo_updated_at: "2026-04-22"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "sns"
  - "social-media"
  - "furuhashilab"
confidence: "low"
---

# -SNS-

## 概要
古橋研究室によるSNS関連の活動・情報を管理するためのリポジトリ。description・topicsともに未設定であり、リポジトリ名「-SNS-」からSNS運用や情報発信に関する管理を目的としていると推測される。作成から更新まで約1日と非常に短期間であり、立ち上げ直後の段階にある。

## 主な活動・成果
- リポジトリの初期構築のみ確認。Issuesは0件でコンテンツの蓄積は確認できない。

## 使用技術・ツール
- GitHub（リポジトリ管理）
- プログラミング言語：なし

## 得られた知見
- 情報が極めて少なく、知見の抽出は困難。SNS運用ガイドラインや投稿管理をGitHubで一元管理する試みである可能性がある。

## 未解決事項・課題
- description・topics・Issuesがすべて未設定・空であり、リポジトリの目的・内容が不明瞭。今後のコンテンツ整備が必要。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/-SNS-
- Issues: https://github.com/furuhashilab/-SNS-/issues
---
repo_name: "www_furuhashiab_com"
repo_url: "https://github.com/furuhashilab/www_furuhashiab_com"
genre: "other"
genre_label: "その他"
repo_created_at: "2015-05-25"
repo_updated_at: "2021-11-01"
distilled_at: "2026-05-26"
language: "HTML"
homepage: "http://furuhashilab.com"
tags:
  - "furuhashilab"
  - "laboratory-website"
  - "spatial-information"
confidence: "high"
---

# www_furuhashiab_com

## 概要
青山学院大学 地球社会共生学部 古橋研究室の公式ウェブサイトを管理するリポジトリ。GitHub Pagesを利用してHTMLで構築・公開されており、研究室の活動紹介・情報発信の基盤となっている。2015年に開設され、長期にわたって継続的に運用されている。

## 主な活動・成果
- 研究室公式サイト（http://furuhashilab.com）のGitHub Pages運用
- Issue #1にて古橋ゼミの紹介文・セミナーガイド（2016年版）を整備・共有
  - 研究テーマ「参加型空間情報と社会貢献」および「一億総伊能化社会」構想を文書化
  - 3・4年次の達成目標（空間情報の把握・可視化→空間分析・フィールドワーク）を明文化
  - 応募条件（国際機関イベント参加必須、ノートPC所有推奨）・選考方法を整理
  - Diversity・Accessibility・Sustainabilityの3軸を評価基準として定義

## 使用技術・ツール
- HTML（サイト構築）
- GitHub Pages（静的サイトホスティング）
- GitHub Issues（ドキュメント管理・情報共有）

## 得られた知見
- 研究室のウェブサイトをGitHub Pagesで管理することで、学生も含めたオープンな共同編集・バージョン管理が可能になる。
- 研究室の理念（DAS：Diversity・Accessibility・Sustainability）を評価軸として明文化することで、学生の活動指針を一貫して運用できる。

## 未解決事項・課題
- Issue #1「古橋ゼミ 紹介文」が2017年以降オープンのまま残っており、内容の更新・クローズが未対応。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/www_furuhashiab_com
- Issues: https://github.com/furuhashilab/www_furuhashiab_com/issues
- 関連サイト: http://furuhashilab.com
---
repo_name: "geocaching4agu"
repo_url: "https://github.com/furuhashilab/geocaching4agu"
genre: "other"
genre_label: "その他"
repo_created_at: "2024-07-01"
repo_updated_at: "2026-01-29"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "geocaching"
  - "aoyama-gakuin-university"
  - "geospatial-data"
confidence: "medium"
---

# geocaching4agu

## 概要
青山学院大学（AGU）におけるジオキャッシングのメンテナンスを目的として作成されたリポジトリである。ジオキャッシングとは、GPSを使って実在するキャッシュ（隠し場所）を探索するアウトドア活動であり、本リポジトリはキャンパス内外のキャッシュ管理に必要な各種データを一元管理するために運用されている。古橋研究室が主体となって維持・更新しており、2024年7月に作成後も継続的に活動が行われている。

## 主な活動・成果
- 青山学院大学のジオキャッシング関連データの収集・整備
- キャッシュのメンテナンスに必要な各種地理空間データの管理
- リポジトリの継続的な更新（最終更新：2026年1月）
- 研究室メンバー7名がリポジトリを購読・監視

## 使用技術・ツール
- GitHub（データ管理・バージョン管理）
- ジオキャッシング（GPS位置情報を活用したアウトドアアクティビティ）
- 地理空間データファイル（GeoJSON等、キャッシュ位置情報の記録に使用と推定）
- プログラミング言語：なし（データリポジトリ）

## 得られた知見
- 大学キャンパスを舞台にしたジオキャッシングは、地理空間情報の教育・体験学習として活用できる。GitHubをデータ管理基盤として使うことで、複数メンバーによるキャッシュ位置情報のバージョン管理と更新履歴の追跡が容易になる。
- 研究室単位でジオキャッシングを運営する際は、メンテナンス用データを専用リポジトリで一元管理することで、担当者交代時の引き継ぎコストを低減できる。

## 未解決事項・課題
- Issues情報が提供されていないため、具体的な残課題は不明。topicsタグが未設定であり、リポジトリの検索可能性向上のためタグ付けが望ましい。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/geocaching4agu
- Issues: https://github.com/furuhashilab/geocaching4agu/issues
---
repo_name: ".github"
repo_url: "https://github.com/furuhashilab/.github"
genre: "other"
genre_label: "その他"
repo_created_at: "2023-02-21"
repo_updated_at: "2026-01-23"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "github-profile"
  - "organization"
  - "furuhashilab"
confidence: "high"
---

# .github

## 概要
古橋研究室（furuhashilab）のGitHub Organizationプロフィールページを管理するための特殊リポジトリである。GitHubでは `.github` という名称のリポジトリに `profile/README.md` を置くことで、Organization のトップページにプロフィール情報を表示できる。本リポジトリはその仕組みを利用して研究室の公開プロフィールを整備・維持することを目的としている。ライセンスはCC0-1.0（パブリックドメイン相当）が適用されている。

## 主な活動・成果
- furuhashilab Organization のGitHubプロフィールページの作成・維持
- プロフィールコンテンツの継続的な更新（最終更新：2026年1月）
- CC0-1.0ライセンスによるコンテンツの公開

## 使用技術・ツール
- GitHub Organization Profile（`.github` リポジトリの `profile/README.md` 機能）
- Markdown（プロフィール記述）
- プログラミング言語：なし（設定・コンテンツリポジトリ）

## 得られた知見
- GitHub Organizationにおいて `.github` リポジトリを作成し `profile/README.md` を置くだけで、Organization トップページにカスタムプロフィールを表示できる。研究室や団体の活動紹介・リンク集として活用でき、メンバーへの情報共有やOSSコミュニティへの発信に有効である。
- CC0ライセンスを適用することで、プロフィールコンテンツを誰でも自由に再利用・改変できる状態にでき、オープンサイエンス・オープン教育の姿勢を示す手段にもなる。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/.github
- Issues: https://github.com/furuhashilab/.github/issues
---
repo_name: "MtBUKO3D4capsule"
repo_url: "https://github.com/furuhashilab/MtBUKO3D4capsule"
genre: "other"
genre_label: "その他"
repo_created_at: "2026-01-13"
repo_updated_at: "2026-01-20"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "3d-printing"
  - "geocaching"
  - "mt-buko"
confidence: "medium"
---

# MtBUKO3D4capsule

## 概要
埼玉県秩父市に位置する武甲山（Mt. BUKO）を題材にした3Dプリント用型データを管理するリポジトリである。「ジオガチャ」（ジオキャッシングと組み合わせたガチャポン形式のアクティビティ）用カプセルとして使用する武甲山の立体模型の型データを収録している。古橋研究室が展開するジオキャッシング関連活動の一環として、フィジカルな体験要素を取り入れたコンテンツ制作を目的として2026年1月に作成された。ライセンスはCC0-1.0が適用されており、データの自由な再利用が可能である。

## 主な活動・成果
- 武甲山の3D形状データ（型）の作成・公開
- ジオガチャ用カプセルとして使用できる3Dプリント向けデータの整備
- CC0-1.0ライセンスによるデータのオープン公開
- リポジトリサイズ約98MBの大容量3Dデータを管理

## 使用技術・ツール
- 3Dモデリング（地形データから武甲山の立体形状を生成）
- 3Dプリンティング（カプセル型の物理出力を想定）
- GitHub（3Dデータのバージョン管理・公開）
- プログラミング言語：なし（3Dデータリポジトリ）

## 得られた知見
- 実在する山岳地形を3D化してカプセルトイ（ガチャ）型に落とし込むことで、ジオキャッシングに物理的なコレクション要素を付加できる。地形データと3Dプリンティングを組み合わせることで、地域の自然・地理情報を教育的かつ体験的に伝えるグッズ制作が可能になる。
- GitHubはテキストコードだけでなく大容量の3Dデータ（STL/OBJなど）の管理・公開にも活用でき、CC0ライセンスと組み合わせることで誰でも再印刷・改変できるオープンな型データ共有が実現する。

## 未解決事項・課題
特になし

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/MtBUKO3D4capsule
- Issues: https://github.com/furuhashilab/MtBUKO3D4capsule/issues
---
repo_name: "InformationSociety2025AGU"
repo_url: "https://github.com/furuhashilab/InformationSociety2025AGU"
genre: "other"
genre_label: "その他"
repo_created_at: "2025-11-27"
repo_updated_at: "2025-12-18"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "education"
  - "open-data"
  - "geojson"
confidence: "high"
---

# InformationSociety2025AGU

## 概要
青山学院大学・古橋研究室による「社会と情報 2025」授業の課題提出用リポジトリ。情報社会論に関する複数の課題（ライセンス・著作権・オープンデータ・位置情報）を GitHub Issues を通じて収集・管理している。LocalWiki がサーバ不調となった際の代替提出先としても機能しており、GitHub の Issue/Comment 機能を教育目的に活用した実践的な事例となっている。

## 主な活動・成果
- **Issue #1（ソフトウェアライセンス概念図）**: オープンソース・プロプライエタリ・パブリックドメインなどソフトウェアライセンスの関係を図示する課題。学生48件のコメントが寄せられた。
- **Issue #2（正しい引用の概念図）**: 「引用」「剽窃」「盗用」「盗作」「オマージュ」「パロディ」の違いを図にまとめる課題。36件のコメントが集まった。
- **Issue #5（公共データ利用規約）**: 「公共データ利用規約（第1.0版）」または「政府標準利用規約（第2.0版）」を採用しているウェブサイト・データの調査課題。39件の回答が投稿された。
- **Issue #6（LocalWiki代替提出先）**: LocalWiki サーバ不調を受け、GitHub Issue をオススメ飲食店情報の代替提出先に設定。Markdown 記法と GeoJSON Embed を組み合わせた投稿形式を採用し、31件が投稿された。
- **Issue #7（課題提出例）**: 町田駅前マクドナルドを例に、店舗名・写真・GeoJSON座標・オススメ理由・ライセンス明記という提出フォーマットのサンプルが示された。
- 全提出物に CC BY 4.0 / ODbL 1.0 ライセンスの明記を義務付け、オープンデータの実践を授業内で徹底。

## 使用技術・ツール
- **GitHub Issues / Comments**: 課題提出・集約プラットフォームとして活用
- **Markdown**: 課題記述・学生投稿のフォーマット
- **GeoJSON Embed（GitHub レンダリング）**: 位置情報をIssue内で地図表示
- **Google Classroom**: 提出URLの管理（Permalink方式）
- **LocalWiki**: 当初の提出先（サーバ不調により代替運用）
- **CC BY 4.0 / ODbL 1.0**: 投稿データのライセンス管理
- language: null（プログラミング言語なし）

## 得られた知見
- GitHub Issues は LMS（学習管理システム）の代替・補完として十分機能する。LocalWiki のような外部サービスが障害を起こした場合でも、GeoJSON Embed や画像アップロードなど GitHub 標準機能だけで地図付き情報収集が可能。
- 学生の成果物にオープンライセンス（CC BY / ODbL）を付与することで、授業活動そのものがオープンデータ生産につながる設計が実現できる。
- Permalink を提出URLとして使う方式は、提出タイムスタンプの改ざん防止・追跡が容易で、教育現場における提出管理に応用できる。

## 未解決事項・課題
- Issue #1〜#7 がすべてオープン（未クローズ）のまま。課題の最終評価・採点後にクローズする運用フローが明示されていない。
- LocalWiki サーバ障害への恒久的な対策（代替プラットフォームの選定など）は未決定。

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/InformationSociety2025AGU
- Issues: https://github.com/furuhashilab/InformationSociety2025AGU/issues
  ---
repo_name: "TheJapaneseHouseOfCouncillorsElection2025"
repo_url: "https://github.com/furuhashilab/TheJapaneseHouseOfCouncillorsElection2025"
genre: "other"
genre_label: "その他"
repo_created_at: "2025-07-16"
repo_updated_at: "2025-07-22"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "選挙"
  - "GeoJSON"
  - "オープンデータ"
confidence: "high"
---

# TheJapaneseHouseOfCouncillorsElection2025

## 概要
2025年日本参議院選挙における選挙ポスター掲示板のマッピングデータをアーカイブするリポジトリである。市民ボランティアプロジェクト「チームみらい」が収集したポスター掲示板の位置情報をGeoJSON形式に変換・保存し、選挙関連地理空間データのオープンな二次利用を可能にすることを目的としている。stargazers数4という比較的高い注目度からも、社会的関心の高さがうかがえる。

## 主な活動・成果
- チームみらいボランティアが構築した選挙ポスター掲示板マッピングサイトのデータをGeoJSON形式に変換・アーカイブ
- Issue #1：ポスター掲示板マップのスクリーンショットを記録・保存
- Issue #2：外部コントリビューターからのライセンス要請に対応し、元データのライセンス（GPL-3.0）を遵守する形でAGPL-3.0をリポジトリに適用
- Issue #3：選挙最終日後にマッピングサイトが閉鎖されたため最終版データの取得に失敗。データ提供元（チームみらい）に公開方法を相談中

## 使用技術・ツール
- GeoJSON（地理空間データ形式）
- GitHub Issues（データ収集・ライセンス議論の管理）
- team-mirai-volunteer/action-board（元データソース）
- ライセンス：AGPL-3.0（GPL-3.0継承による適用）
- プログラミング言語：なし（language: null）

## 得られた知見
- 選挙・イベントなど期間限定のオープンデータは、公開期間終了後に予告なくサイトが閉鎖されることがある。データアーカイブは活動期間中にリアルタイムで取得しておくことが重要で、「終了後に取得しよう」では手遅れになるリスクがある。
- 他プロジェクトのオープンデータを利用する際はライセンスの伝播（GPL系のコピーレフト）を事前に確認し、自リポジトリのライセンス選定に反映させる必要がある。外部コントリビューターからの指摘で発覚するケースもあるため、データ取得時点での確認が望ましい。

## 未解決事項・課題
- 最終版ポスター掲示板データが未取得のまま（Issue #3）。チームみらい側の公開方針決定待ち
- Issue #2のライセンス変更対応がOpenのままであり、AGPL-3.0適用の最終確認が必要

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/TheJapaneseHouseOfCouncillorsElection2025
- Issues: https://github.com/furuhashilab/TheJapaneseHouseOfCouncillorsElection2025/issues
---
repo_name: "GeoExhibition2025"
repo_url: "https://github.com/furuhashilab/GeoExhibition2025"
genre: "other"
genre_label: "その他"
repo_created_at: "2025-06-24"
repo_updated_at: "2025-07-16"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "geoten"
  - "furuhashilab"
  - "geo-exhibition"
confidence: "high"
---

# GeoExhibition2025

## 概要
古橋研究室（furuhashilab）が2025年7月に開催した地理系展示イベント「ジオ展2025」の準備・運営・振り返りを管理するためのリポジトリ。ブース出展に伴うポスター制作・備品調達・シフト管理・費用精算・当日対応など、イベント全体のタスクをGitHub Issuesで一元的に追跡している。昨年（2024年）は学生参加が2名のみだったが、開催時期を4月から7月に変更したことでスケジュール調整が容易になり、今年は多数のゼミ生が参加して盛況となった。

## 主な活動・成果
- ポスター（研究室紹介・ジオガチャ用）を合計250枚配布。当日昼には150枚が配り切れたため100枚を追加印刷し対応した
- ジオガチャ（カプセルトイ）をブースに設置し、景品（メガネ拭き・トートバッグ）を完売に近い形で提供。売れ残りは4個のみ
- メガネ拭き160枚（@51円）、トートバッグ30枚（@1,215円）、ガチャカプセル100個（@25円）、Canonインクカートリッジなど費用精算をIssueでリスト化・管理
- 古橋先生のメッセージ動画をプレゼンに組み込み、来場者への訴求に活用（インスタライブも実施）
- 学生有志が振り返りメモをIssueに投稿し、良かった点・反省点を次年度へ引き継ぐ形で記録

## 使用技術・ツール
- GitHub Issues（タスク管理・振り返り記録・費用精算ドキュメント）
- Canva / 印刷ツール（ポスターデザイン・制作、明示的な言及はないが担当者割り当てから推定）
- Canon インクジェットプリンター（BCI-350/351系カートリッジ）による現地印刷
- YouTube / インスタライブ（プレゼン動画・配信）
- テザリング（会場WiFi不安定時の代替接続手段として当日活用）
- プログラミング言語：なし（language: null）

## 得られた知見
- **開催時期の変更が参加率に直結する**：4月→7月への変更でゼミ生の参加が大幅増加。スケジュール共有も早めに行うことでシフト作成がスムーズになった
- **印刷物は来場者数の1.5〜2倍を想定して用意する**：今回150枚→250枚に増やした事例から、次回は250〜300枚が目安。当日追加印刷できる体制（ブース外に機動力あるメンバー配置）も重要
- **発表スライドへの動画は埋め込み形式を推奨**：会場WiFiが脆弱な場合、YouTube URLではなくスライドに直接動画を埋め込むことで当日トラブルを回避できる
- **シフトは最低限の骨格だけ決め、あとは自由参加にするほうが機動的**：厳密なシフト管理は人の偏りや他ブース見学機会の損失を招く。ブース常駐は2〜3名を基本とし、先輩をサポート役として配置するとよい
- **名刺・名刺代わりの配布物は来場前に準備する**：懇親会や企業担当者との交流機会で名刺がないと機会損失になる。研究室共通の名刺または代替配布物（ポスターとは別）を用意すべき

## 未解決事項・課題
- 費用精算（Issue #10）がまだクローズされておらず、ガーメントプリンタインク等の残量確認も未完了
- ポスター作製（Issue #5）・備品搬入（Issue #4）・プレゼン準備（Issue #1）・先生ビデオ依頼（Issue #6）がreopenedのまま残存しており、次年度向けの引き継ぎ文書としての整理が必要
- 3年生が主体的にイベントを牽引できるよう、能力・意識向上の取り組みが継続課題として挙げられている
- 古橋研究室の名刺作成がまだ実現していない（Issue #17）
- ジオガチャ景品デザインのユニーク性向上（等高線・地図デザインが他ブースと被りがちな点の改善）

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/GeoExhibition2025
- Issues: https://github.com/furuhashilab/GeoExhibition2025/issues
---
repo_name: "geogacha"
repo_url: "https://github.com/furuhashilab/geogacha"
genre: "other"
genre_label: "その他"
repo_created_at: "2023-04-18"
repo_updated_at: "2025-07-16"
distilled_at: "2026-05-26"
language: null
homepage: null
tags:
  - "geogacha"
  - "geoten"
  - "furuhashilab"
confidence: "high"
---

# geogacha

## 概要
古橋研究室（青山学院大学）が地図・地理系の展示イベント「ジオ展」で実施する参加型展示企画「ジオガチャ」の公開リポジトリである。ガチャガチャ機を使って来場者にメガネクリーナーなどのオリジナルグッズを景品として提供する企画の準備・運営・振り返りをGitHub Issuesで管理している。2023年に開設され、ジオ展2025（Geoten2025）の準備・事後フィードバックが中心的な活動内容となっている。

## 主な活動・成果
- ジオ展2025において、メガネクリーナー・トートバッグ・白地図などを景品としたジオガチャを実施し、昨年比で参加ゼミ生が大幅増加、ブースが盛況となった
- 「古橋先生へのメッセージコーナー」を新設し、来場者から好評を得た
- ガーメントプリンターを用いてメガネクリーナーやトートバッグにオリジナルデザインを印刷。2人1組の役割分担（セット担当・PC操作担当）で効率化を図った
- ポスター・チラシ・ガチャカプセル内説明書など複数の制作物をデザイン班が分担制作した
- イベント後、各班・各メンバーが個別にIssueを立てて事後フィードバックを実施。搬入、景品パッキング、デザイン、白地図制作など班ごとの課題を記録した
- ジオガチャと直接関係のないジオ展全般のフィードバックはGeoExhibition2025リポジトリへの移設運用ルールを整備した

## 使用技術・ツール
- GitHub Issues（タスク管理・振り返り記録）
- ガーメントプリンター（布素材へのダイレクト印刷）
- ポスター印刷機（ゼミ室設置、ジオ展2025では不具合発生）
- iPad・フリーフォント（ポスター・チラシデザイン）
- ペーパーカッター（カプセル内説明書の断裁、来年導入検討）
- 白地図（展示物として来場者が書き込む参加型コンテンツ）
- CC0-1.0ライセンス

## 得られた知見
- ガーメントプリンターは操作を属人化させず、全員がマニュアルを参照できる体制と事前練習時間の確保が量産効率の鍵となる。一度うまくいったデザイン位置設定を保存しておくことで量産がスムーズになる。
- 大型備品（ガチャガチャ本体）の搬入は通勤ラッシュ時間帯の電車を避け、会場近くのメンバーが搬入・遠方メンバーが搬出を担当するなど、役割を往復で分けることで負担を分散できる。
- GitHub Issuesをイベント事後フィードバックツールとして活用することで、班をまたいだ知見の蓄積と翌年への引き継ぎが容易になる。Issueタイトルには内容が一目でわかる記述が必須。
- 参加型展示（ガチャ、メッセージコーナー）は来場者の満足度が高く、ブース集客に有効。景品の説明・価格・内容はポスターに明示することで口頭説明への依存を減らせる。

## 未解決事項・課題
- 景品（メガネクリーナー）の定番化 vs 新規景品導入の方向性が来年に向けて検討中（Issue #30）
- トートバッグのガーメントプリント時のセンタリングずれ問題の原因究明と対策（Issue #22）
- ゼミ室のポスター印刷機の不具合（黄・ピンクインクランプ点灯）が未解消（Issue #7）
- 白地図班における作業分担の曖昧さ・受動的進行・コミュニケーション不足の改善策が課題として残存（Issue #17, #25）
- 学生名刺・ゼミオリジナルTシャツなどのアイデンティティツールの準備（Issue #23, #14）
- ペーパーカッターの研究室導入検討（Issue #19）

## 参考リンク
- リポジトリ: https://github.com/furuhashilab/geogacha
- Issues: https://github.com/furuhashilab/geogacha/issues
