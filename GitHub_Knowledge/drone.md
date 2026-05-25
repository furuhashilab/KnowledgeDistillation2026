---
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

