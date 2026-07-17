# AIFFEL Applied Deep Learning Portfolio

> **Category:** Structured training portfolio
> **Program:** AIFFEL Research Program, October 2024–April 2025
> **Scope:** Machine learning, computer vision, natural language processing, and deep learning experiments

This repository presents evidence from the AIFFEL Research Program as a topic-based technical portfolio. Descriptive paths replace opaque course-only names, while the original track and unit identifiers remain documented in the [notebook and provenance index](docs/notebook-index.md).

AIFFEL Research 과정에서 수행한 머신러닝·딥러닝 실습을 실제 과제명 중심으로 재구성한 포트폴리오입니다. 교육용 baseline, 개인 구현, peer review, 미완료 항목을 구분하며 임상 검증이나 독립 연구성과로 과장하지 않습니다.

## Portfolio map

| Area | Evidence represented | Course units |
|---|---|---|
| [Machine Learning and Data Science](portfolio/01-ml-and-data-science/) | Linear regression, feature engineering, ensemble regression | Exploration Ex01–Ex02 |
| [Computer Vision Fundamentals](portfolio/02-computer-vision-fundamentals/) | Facial landmarks, semantic segmentation, image compositing | Exploration Ex03–Ex04 |
| [Natural Language Processing](portfolio/03-natural-language-processing/) | Sentiment classification, summarization, Transformer dialogue modeling | Exploration Ex05–Ex07 |
| [Deep Computer Vision](portfolio/04-deep-computer-vision/) | ResNet ablation, augmentation, explainability, OCR, detection, segmentation, pose estimation | GoingDeeper GD01–GD08 |
| [Generative Language Modeling](portfolio/05-generative-language-modeling/) | Decoder-only Transformer exercise on movie dialogue | MainQuest Quest01 |
| [Capstone and Collaborative Work](portfolio/06-capstone-and-collaborative-work/) | Limited-data chest-X-ray segmentation and a separate team project | MainQuest Quest02; external team repository |

## Evidence-backed highlights

- **Controlled comparisons:** ResNet versus PlainNet, standard augmentation versus CutMix/MixUp, and segmentation encoder comparisons.
- **Medical-image-adjacent training:** limited-data lung-mask segmentation on chest X-rays. This is not a CT project and has no external clinical validation.
- **Explainability and localization:** CAM/Grad-CAM feature maps, bounding-box correction, and IoU inspection.
- **Detection and segmentation:** SSD face detection, RetinaNet road-scene detection, U-Net/U-Net++ road segmentation, and exploratory lung segmentation.
- **Language modeling:** Korean sentiment models, abstractive/extractive summarization, SentencePiece Transformer dialogue modeling, and a GPT-style decoder exercise.
- **Research habits:** data splitting, checkpointing, ablation, error analysis, documented limitations, and peer code review.

## How to read this repository

- `exploration/`, `going-deeper/`, and `main-quest/` contain the renamed course artifacts.
- `portfolio/` provides a researcher-facing navigation layer by technical area.
- [Notebook index](docs/notebook-index.md) maps every old path to its new evidence-based path.
- [Curriculum map](docs/curriculum-map.md) summarizes the implemented topics and limitations.
- [Project evidence matrix](docs/project-evidence-matrix.md) controls what can be claimed externally.
- [Repository provenance](docs/repository-provenance.md) records authorship and archive boundaries.

## Evidence and authorship boundaries

- A completed notebook demonstrates training activity; it does not by itself establish sole authorship, independent research, or clinical validity.
- Course baselines, pretrained models, team work, and named peer review are identified where the repository provides evidence.
- Empty notebook scaffolds and exact misplaced duplicates were removed from the curated tree; their history remains recoverable in Git.
- Stored metrics are notebook-recorded results unless explicitly reproduced and independently verified.

## Relevance to medical-imaging research

The strongest transferable skills are segmentation, explainability, controlled data splitting, model comparison, and failure analysis. Applying them to clinical imaging still requires IRB and data-governance controls, acquisition-aware quality checks, leakage-safe validation, external evaluation, and clinically meaningful endpoints.

## Data and privacy

No patient-level clinical data should be committed to this repository. Course datasets remain subject to their original licenses and terms. Large datasets, checkpoints, API keys, local paths, and confidential material must remain outside version control.
