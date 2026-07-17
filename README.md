# AIFFEL Applied Deep Learning Portfolio

> **Category:** Structured training portfolio  
> **Program:** AIFFEL Research Program, October 2024–April 2025  
> **Scope:** Machine learning, computer vision, natural language processing, and deep learning experiments

This repository documents the breadth of models, experiments, debugging, and peer review completed during the AIFFEL Research Program. It is presented as **training evidence**, not as peer-reviewed research or a clinically validated system.

AIFFEL Research 과정에서 수행한 머신러닝·딥러닝 실험을 주제별로 정리한 포트폴리오입니다. 과정 제공 baseline, 개인 구현, 팀 작업 및 peer review를 구분하며, 검증되지 않은 성능이나 임상적 효용을 주장하지 않습니다.

## Why this portfolio

My background combines CT systems engineering and quantitative chest-CT research. I used the AIFFEL program to strengthen practical implementation across data science, computer vision, segmentation, explainability, detection, sequence modeling, and Transformer architectures. These projects support—but do not replace—my clinical-imaging research record.

## Curriculum navigation

| Area | Representative work | Original course units |
|---|---|---|
| [Machine Learning and Data Science](portfolio/01-ml-and-data-science/) | Regression, preprocessing, baseline comparison | Exploration Ex01–Ex02 |
| [Computer Vision Fundamentals](portfolio/02-computer-vision-fundamentals/) | Facial landmarks, segmentation, masks, image transformation | Exploration Ex03–Ex04 |
| [Natural Language Processing](portfolio/03-natural-language-processing/) | Sentiment classification, summarization, Transformer chatbot | Exploration Ex05–Ex07 |
| [Deep Computer Vision](portfolio/04-deep-computer-vision/) | ResNet ablation, augmentation, Grad-CAM, SSD, U-Net/U-Net++, pose estimation | GoingDeeper GD01–GD09 |
| [Generative Language Modeling](portfolio/05-generative-language-modeling/) | Subword tokenization and GPT-style dialogue modeling | MainQuest Quest01 |
| [Team and Capstone Projects](portfolio/06-team-and-capstone-projects/) | Limited-data lung-image segmentation and MINI AIFFELTHON | MainQuest Quest02; external team repository |

## Selected evidence

- **Experimental comparison:** ResNet-50 versus PlainNet-50 ablation, with loss/accuracy interpretation and discussion of skip connections.
- **Augmentation:** normalization, conventional augmentation, CutMix, and MixUp experiments with model save/reload workflows.
- **Explainability and localization:** CAM/Grad-CAM feature maps, bounding-box correction, and IoU-based inspection.
- **Detection and segmentation:** TFRecord/prior-box preparation, SSD face detection, U-Net/U-Net++ implementation, and an exploratory lung-segmentation extension.
- **Natural language processing:** Korean text preprocessing, LSTM/Conv1D sentiment models, sequence-to-sequence attention, subword tokenization, and Transformer-based dialogue modeling.
- **Research habits:** modularization, checkpointing, failure analysis, documented debugging, and peer code review.

## Evidence and authorship boundaries

- `Exploration/`, `GoingDeeper/`, and `MainQuest/` preserve the original course structure and history.
- A completed notebook or repository presence does not by itself establish sole authorship.
- Each featured project should identify the course context, provided baseline, individual changes, peer reviewer, data source, and limitations.
- Team projects remain explicitly labeled as team work.
- Empty templates and units whose contents have not been verified are not counted as completed projects.

See:

- [Curriculum map](docs/curriculum-map.md)
- [Project evidence matrix](docs/project-evidence-matrix.md)
- [Project README template](docs/project-readme-template.md)
- [Repository provenance](docs/repository-provenance.md)

## Relevance to medical-imaging research

The strongest transferable skills are segmentation, explainability, controlled data splitting, error analysis, and reproducible experiment documentation. Applying these methods to clinical research still requires appropriate IRB/data governance, acquisition-aware quality control, leakage-safe validation, and independent clinical evaluation.

## Data and privacy

No patient-level clinical data should be committed to this repository. Course datasets remain subject to their original licenses and terms. Large datasets, checkpoints, API keys, local paths, and confidential material must remain outside version control.
