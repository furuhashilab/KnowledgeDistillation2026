# KnowledgeDistillation2026furuhashilab

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Institution](https://img.shields.io/badge/Institution-Aoyama_Gakuin_University-blue)](https://www.aoyama.ac.jp/)
[![Lab](https://img.shields.io/badge/Lab-Furuhashi_Lab-green)](https://github.com/furuhashilab)

---

## English

### Overview

This repository contains a two-stage knowledge distillation dataset of **Furuhashi Lab** (Aoyama Gakuin University, College of Global Studies and Collaboration), directed by **Prof. Taichi Furuhashi** (@mapconcierge).

The dataset is structured as Markdown files suitable for use as **LLM fine-tuning data**, RAG knowledge bases, or general reference on the lab's research, education, and activities in geospatial technology, OpenStreetMap, humanitarian mapping, drone surveys, 3D modeling, and more.

> **Mission — "Billions Inō-zation" (一億総伊能化)**
> Like Ino Tadataka, the Edo-period surveyor who mapped all of Japan on foot, we aim for a world where everyone can freely create and use maps with cutting-edge technology.

### Two-Stage Distillation Process

```
Stage 1 (Human)        →   Stage 2 (AI)
─────────────────────────────────────────────────────────
Students read lab's      Claude Code CLI (claude-sonnet-4-6)
public content           re-integrates and restructures
(Medium, GitHub,         all Stage-1 files into a unified
YouTube) and write       knowledge system with YAML metadata
.md files                and Q&A training pairs
         ↓                           ↓
1st_Kndowledge...2026/      2nd_KnowledgeDistillation_byClaudeCodeCLI/
(~45 .md files)              (15 .md files, ~3,700 lines)
```

### Repository Structure

```
KnowledgeDistillation2026/
├── README.md                                        # This file
├── LICENSE.txt                                      # CC0 1.0 Universal
├── 1st_KndowledgeDistillation_madebyStudents2026/   # Stage 1: student-authored files
│   ├── OurBlogs_onMedium/
│   ├── AboutHOTTaskingManager/
│   ├── GitHub_Knowledge/
│   ├── Paast_thesis_papers/
│   └── YouTubeContents/
└── 2nd_KnowledgeDistillation_byClaudeCodeCLI/       # Stage 2: AI-integrated dataset
    ├── 00_dataset_index.md
    ├── 01_lab_profile.md
    ├── 02_openstreetmap_knowledge.md
    ├── ...
    ├── 14_qa_training_dataset.md
    └── CV_Taichi_FURUHASHI2026.md
```

### Dataset Files (Stage 2)

| # | File | Contents |
|---|------|----------|
| 00 | `00_dataset_index.md` | Master index, metadata, lab basic info |
| 01 | `01_lab_profile.md` | Lab overview, mission, professor CV, awards, projects |
| 02 | `02_openstreetmap_knowledge.md` | OSM knowledge, tools, tagging, contribution workflow |
| 03 | `03_humanitarian_mapping.md` | Humanitarian mapping, crisis response, HOT activities |
| 04 | `04_hot_tasking_manager_guide.md` | HOT Tasking Manager step-by-step operation guide |
| 05 | `05_gis_and_geospatial_tools.md` | GIS tools ecosystem: QGIS, Mapbox, overpass, etc. |
| 06 | `06_drone_and_aerial_survey.md` | Drone operations, aerial survey, ODM workflow, DRONEBIRD |
| 07 | `07_3d_modeling_and_plateau.md` | 3D modeling, Project PLATEAU, Blender, CityGML |
| 08 | `08_research_themes_and_thesis.md` | 124 thesis analysis, research archetypes, lineages |
| 09 | `09_events_hackathons_conferences.md` | SotM, FOSS4G, hackathons, annual lab schedule |
| 10 | `10_youtube_media_content.md` | YouTube catalog, V&F（Video & Film）部 production workflow |
| 11 | `11_github_open_data_practices.md` | GitHub conventions, repository catalog, licensing |
| 12 | `12_student_circles_activities.md` | Student circles: YouthMappers AGU部, V&F（Video & Film）部, Drone部, YOKOZE部, etc. |
| 13 | `13_terminology_glossary.md` | Glossary of key terms and concepts |
| 14 | `14_qa_training_dataset.md` | 39 Q&A pairs in instruction-response format (JSONL-ready) |

### Data Quality

| Item | Value |
|------|-------|
| Coverage | 1975–2026 (primarily 2015–2026) |
| Primary sources | Medium blog posts, YouTube, GitHub repositories, graduation theses |
| Language | Japanese (partial English) |
| Estimated source articles | 300+ (Medium: 100+, YouTube: 50+, GitHub: 100+, Theses: 124) |
| Validation | Stage-1 distillation by students; Stage-2 integration by Claude Code CLI |

### License

**CC0 1.0 Universal** — This dataset is released into the public domain. You may use, modify, and redistribute it for any purpose, including commercial use, without restriction.

### About the Lab

- **Lab**: Furuhashi Lab, College of Global Studies and Collaboration, Aoyama Gakuin University
- **Director**: Prof. Taichi Furuhashi (@mapconcierge)
- **Location**: Sagamihara Campus B720, Fuchinobe 5-10-1, Chūo-ku, Sagamihara, Kanagawa, Japan
- **Founded**: April 1, 2015
- **Medium**: https://medium.com/furuhashilab
- **GitHub Org**: https://github.com/furuhashilab

---

## 日本語

### 概要

本リポジトリは、青山学院大学地球社会共生学部 **古橋研究室**（古橋大地 教授 / @mapconcierge）の知識蒸留データセットです。

地理空間技術・OpenStreetMap・人道支援マッピング・ドローン測量・3Dモデリング等に関する研究室の知識体系を、**LLMファインチューニングデータ**、RAGナレッジベース、または一般リファレンスとして利用可能なMarkdown形式で提供します。

> **ミッション — 「一億総伊能化」**
> 江戸時代の測量家・伊能忠敬が日本全土を歩いて測量したように、最先端技術を用いることで世界中の誰もが自由に地図を作れ、活用できる社会を目指す。

### 二段階蒸留プロセス

```
一次蒸留（人間）        →   二次蒸留（AI）
─────────────────────────────────────────────────────────────
学生チームが研究室の          Claude Code CLI（claude-sonnet-4-6）が
公式コンテンツ               全.mdファイルを統合・再構造化し、
（Medium・GitHub・           YAMLメタデータとQ&A学習ペアを備えた
YouTube）を.mdファイルに     統一知識体系を生成
言語化・記録
         ↓                           ↓
1st_Kndowledge...2026/      2nd_KnowledgeDistillation_byClaudeCodeCLI/
（約45ファイル）               （15ファイル・約3,700行）
```

### リポジトリ構成

```
KnowledgeDistillation2026/
├── README.md                                        # 本ファイル
├── LICENSE.txt                                      # CC0 1.0 Universal
├── 1st_KndowledgeDistillation_madebyStudents2026/   # 一次蒸留：学生制作ファイル
│   ├── OurBlogs_onMedium/
│   ├── AboutHOTTaskingManager/
│   ├── GitHub_Knowledge/
│   ├── Paast_thesis_papers/
│   └── YouTubeContents/
└── 2nd_KnowledgeDistillation_byClaudeCodeCLI/       # 二次蒸留：AI統合データセット
    ├── 00_dataset_index.md
    ├── 01_lab_profile.md
    ├── 02_openstreetmap_knowledge.md
    ├── ...
    ├── 14_qa_training_dataset.md
    └── CV_Taichi_FURUHASHI2026.md
```

### データセットファイル一覧（二次蒸留）

| # | ファイル名 | 内容 |
|---|----------|------|
| 00 | `00_dataset_index.md` | インデックス・メタデータ・研究室基本情報 |
| 01 | `01_lab_profile.md` | 研究室概要・ミッション・教授CV・受賞歴・プロジェクト |
| 02 | `02_openstreetmap_knowledge.md` | OSM知識・ツール・タギング・コントリビューション |
| 03 | `03_humanitarian_mapping.md` | 人道支援マッピング・危機対応・HOT活動 |
| 04 | `04_hot_tasking_manager_guide.md` | HOT Tasking Manager 操作ガイド |
| 05 | `05_gis_and_geospatial_tools.md` | GISツール全体像：QGIS・Mapbox・Overpass等 |
| 06 | `06_drone_and_aerial_survey.md` | ドローン運用・空撮測量・ODMワークフロー・DRONEBIRD |
| 07 | `07_3d_modeling_and_plateau.md` | 3Dモデリング・Project PLATEAU・Blender・CityGML |
| 08 | `08_research_themes_and_thesis.md` | 卒業論文124件分析・研究アーキタイプ・研究系譜 |
| 09 | `09_events_hackathons_conferences.md` | SotM・FOSS4G・ハッカソン・研究室年次スケジュール |
| 10 | `10_youtube_media_content.md` | YouTubeカタログ・V&F（Video & Film）部 映像制作ワークフロー |
| 11 | `11_github_open_data_practices.md` | GitHub運用規則・リポジトリカタログ・ライセンス慣行 |
| 12 | `12_student_circles_activities.md` | 学生サークル活動：YouthMappers AGU部・V&F（Video & Film）部・Drone部・YOKOZE部等 |
| 13 | `13_terminology_glossary.md` | 主要用語集・Glossary |
| 14 | `14_qa_training_dataset.md` | Q&A形式39問（instruction-response形式・JSONL変換可） |

### データ品質

| 項目 | 値 |
|------|-----|
| カバー期間 | 1975年〜2026年（主に2015〜2026年） |
| 一次ソース | Mediumブログ・YouTube・GitHubリポジトリ・卒業論文 |
| 言語 | 日本語（一部英語混在） |
| 推定ソース記事数 | 300件以上（Medium: 100件以上 / YouTube: 50件以上 / GitHub: 100件以上 / 論文: 124件） |
| 検証状態 | 学生による一次蒸留済み・Claude Code CLIによる統合再構成 |

### ライセンス

**CC0 1.0 Universal** — 本データセットはパブリックドメインとして公開しています。商用利用を含む、あらゆる目的での利用・改変・再配布が制限なく可能です。

### 研究室について

- **研究室**: 青山学院大学 地球社会共生学部 古橋研究室
- **主宰**: 古橋 大地 教授（ふるはし たいち / @mapconcierge）
- **所在地**: 〒252-5258 神奈川県相模原市中央区淵野辺5-10-1 青山学院大学 相模原キャンパス B720
- **設立**: 2015年4月1日
- **Medium**: https://medium.com/furuhashilab
- **GitHub**: https://github.com/furuhashilab
