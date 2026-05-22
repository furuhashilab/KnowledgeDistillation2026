# Source Quality Report v2

## 総記事数

- total_articles: 464
- full_text_reviewed: 462
- metadata_only: 2

## ラベル別の記事数

| label | total | full_text_reviewed | metadata_only |
| --- | ---: | ---: | ---: |
| education | 22 | 22 | 0 |
| event_report | 28 | 28 | 0 |
| fieldwork | 37 | 37 | 0 |
| foss4g_sotm | 5 | 5 | 0 |
| humanitarian_mapping | 20 | 20 | 0 |
| lab_overview | 45 | 45 | 0 |
| openstreetmap | 57 | 57 | 0 |
| other | 60 | 60 | 0 |
| qgis_gis_tools | 110 | 108 | 2 |
| student_project | 80 | 80 | 0 |

## metadata_only の記事一覧

- 【ドローン部】2022年度 第一回目ミーティング / 2022-04-26 / Taiyu Ozawa / https://medium.com/furuhashilab/ドローン部-第一回目ミーティング-3fcbb1061f65
- ドローン部週報➂ / 2020-04-29 / 古屋 百々葉 / https://medium.com/furuhashilab/ドローン部週報➂-19f2f4298245

## 本文未取得記事をNotebookLMで扱う際の注意点

- metadata_only 記事は本文詳細を含まないため、タイトル・著者・公開日・URL・タグ・既存概要の範囲を超える回答根拠にしない。
- full_text_reviewed 記事と比較するときは、品質区分を回答内で確認する。

## 今後の改善案

- metadata_only 記事は、本文を取得できた時点で `articles_fulltext/` を更新してから本生成処理を再実行する。
- `articles_fulltext/` の概要・重要ポイント・関連欄の品質確認を継続し、入力ソース側を先に修正する。
