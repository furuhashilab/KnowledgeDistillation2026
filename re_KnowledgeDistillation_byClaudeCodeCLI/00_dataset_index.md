---
title: "古橋研究室 知識蒸留データセット インデックス"
dataset_version: "2.0"
created_by: "Claude Code CLI (claude-sonnet-4-6)"
created_date: "2026-06-06"
source: "madebyStudents/ フォルダ内の全.mdファイル（学生制作）"
language: "ja"
license: "CC BY 4.0"
institution: "青山学院大学 地球社会共生学部 古橋研究室"
tags: ["furuhashi-lab", "openstreetmap", "humanitarian-mapping", "GIS", "drone", "PLATEAU", "knowledge-distillation"]
---

# 古橋研究室 知識蒸留データセット（2026年版）

## データセット概要

本データセットは、青山学院大学地球社会共生学部古橋研究室（古橋大輔教授）の公式コンテンツを基に、
学生チームが行った一次知識蒸留作業を再統合・再構造化したものです。
LLM（大規模言語モデル）の学習データとして利用可能な形式で、
古橋研究室の研究・教育・活動に関する包括的な知識体系を提供します。

### 生成方法
- **一次蒸留**: 各学生チームがブログ（Medium）、GitHub、YouTubeコンテンツを.mdファイルに言語化
- **二次蒸留**: Claude Code CLI（claude-sonnet-4-6）が全.mdファイルを統合・再構造化
- **統合対象**: madebyStudents/フォルダ内の全.mdファイル（約45ファイル、複数カテゴリ）

---

## データセット構成

| ファイル番号 | ファイル名 | 内容 | 主要タグ |
|---|---|---|---|
| 00 | `00_dataset_index.md` | 本インデックスファイル | metadata, index |
| 01 | `01_lab_profile.md` | 研究室概要・ミッション・組織構造 | profile, mission, organization |
| 02 | `02_openstreetmap_knowledge.md` | OSM知識・ツール・技術 | OSM, mapping, tools |
| 03 | `03_humanitarian_mapping.md` | 人道支援マッピング・危機対応 | humanitarian, crisis, HOT |
| 04 | `04_hot_tasking_manager_guide.md` | HOT Tasking Manager 操作ガイド | HOT-TM, procedures, validation |
| 05 | `05_gis_and_geospatial_tools.md` | GIS・地理空間ツール全体像 | GIS, QGIS, Mapbox, tools |
| 06 | `06_drone_and_aerial_survey.md` | ドローン活動・空撮測量 | drone, UAV, aerial, ODM |
| 07 | `07_3d_modeling_and_plateau.md` | 3Dモデリング・PLATEAU活用 | 3D, PLATEAU, Blender, CityGML |
| 08 | `08_research_themes_and_thesis.md` | 研究テーマ・卒論パターン分析 | research, thesis, academic |
| 09 | `09_events_hackathons_conferences.md` | イベント・ハッカソン・学会 | events, hackathon, SotM, FOSS4G |
| 10 | `10_youtube_media_content.md` | YouTube・映像制作コンテンツ | YouTube, video, media |
| 11 | `11_github_open_data_practices.md` | GitHub運用・オープンデータ慣行 | GitHub, open-data, practices |
| 12 | `12_student_circles_activities.md` | 学生サークル・活動内容 | students, circles, YouthMappers |
| 13 | `13_terminology_glossary.md` | 用語集・glossary | glossary, terminology |
| 14 | `14_qa_training_dataset.md` | Q&A形式LLM学習用データセット | QA, training, LLM |

---

## 研究室基本情報

- **正式名称**: 青山学院大学 地球社会共生学部 古橋研究室
- **英語名称**: Furuhashi Lab, College of Global Studies, Aoyama Gakuin University (AGU)
- **主宰**: 古橋大輔（ふるはし だいすけ）教授
- **所在地**: 東京都渋谷区神宮前4-4-25 青山学院大学
- **設立**: 1990年代後半〜2000年代
- **ラボキャッチフレーズ**: 「一億総伊能化」「1億総伊能家」
- **Medium公開URL**: https://medium.com/furuhashilab
- **GitHub Organization**: https://github.com/furuhashilab

## 核心的ミッション

> "一億総伊能化" — 江戸時代の測量家・伊能忠敬のように、日本の一億人すべてが地図を作れる社会を目指す。

- 地理空間情報技術の民主化
- オープンデータと市民科学の推進
- 人道支援・災害対応マッピング
- 地球規模の課題への地理情報技術による貢献

---

## データ品質メタデータ

| 項目 | 値 |
|---|---|
| カバー期間 | 1999年〜2026年（主に2018〜2026年） |
| 一次ソース数 | Mediumブログ記事、YouTubeコンテンツ、GitHubリポジトリ、卒業論文 |
| 言語 | 日本語（一部英語混在） |
| 推定ソース記事数 | 300件以上（Medium: 100件以上、YouTube: 50件以上、GitHub: 100件以上、論文: 124件） |
| 検証状態 | 学生による一次蒸留済み、Claude Code CLIによる統合・再構成 |
