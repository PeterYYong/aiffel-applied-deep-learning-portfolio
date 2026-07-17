# Project Evidence Matrix

This matrix controls what may be claimed in a CV, application, or public portfolio. It is intentionally conservative.

| Unit | Evidence-supported description | Contribution boundary | Portfolio use |
|---|---|---|---|
| Ex01-A | Manual diabetes linear-regression model, MSE gradient, and learning-rate comparison | Individual coursework; unit-level named review | Foundation |
| Ex01-B | Bike-demand regression with datetime features and leakage-column removal | Coursework; notebook-specific authorship not separated | Foundation |
| Ex02 | KAKR house-price preprocessing, stacking, LightGBM, and search | Adapted LMS/Kaggle baseline; exact individual delta unclear | Foundation |
| Ex03 | Transformation-aware facial-landmark sticker placement | Individual coursework with named review | Selected |
| Ex04 | DeepLab-based masks, background blur, and multi-object experiments | Pretrained model/course scaffold; replacement incomplete | Selected |
| Ex05 | Mecab preprocessing and LSTM/Conv1D/GlobalMaxPooling comparisons | Individual coursework with named review | Selected |
| Ex06 | Attention seq2seq abstractive and Summa extractive summarization | Executed course scaffold; coder/reviewer record absent | Supporting |
| Ex07 | SentencePiece encoder-decoder Transformer with padding-aware loss | Individual coursework with named review | Selected |
| GD01 | ResNet-34/50 versus PlainNet-34/50 ablation | Individual coursework with named review | Featured training evidence |
| GD02 | Standard augmentation versus CutMix/MixUp on Stanford Dogs | Training work; some experiments distributed among peers | Selected |
| GD03 | CAM/Grad-CAM localization and IoU inspection | Core work complete; guided extensions incomplete | Featured training evidence |
| GD04 | Keras-OCR detection and CRNN/CTC recognition | Training workflow; final weight use and quality incomplete | Supporting |
| GD05 | WIDER FACE TFRecords, priors, SSD detection, and sticker overlay | Individual coursework with named review | Selected |
| GD06 | KITTI RetinaNet/FPN/focal-loss GO/STOP prototype | Course prototype; no safety validation | Selected |
| GD07-A | KITTI road segmentation with U-Net/U-Net++ and Dice/IoU | Coursework with peer review | Featured training evidence |
| GD07-B | Exploratory U-Net lung-segmentation extension | Exploratory training only; no clinical claim | Supporting |
| GD08 | MPII Stacked Hourglass versus SimpleBaseline comparison | Coursework with peer review; weak/overfit results retained | Selected |
| Quest01 | Decoder-only Transformer exercise on Cornell Movie Dialogs | Training artifact; prompt conditioning is defective | Supporting |
| Quest02 | Small-sample chest-X-ray U-Net encoder comparison | Training artifact; individual/team contribution unverified | Selected after provenance clarification |

## Claim levels

- **Featured training evidence:** strong implementation or experimental-design evidence, still described as education rather than independent research.
- **Selected:** technically relevant evidence with documentation, reproducibility, or result limitations.
- **Supporting/Foundation:** breadth evidence that should not lead a research application.

## Prohibited claims

- Clinically validated medical model
- CT segmentation experience based on the Quest02 chest-X-ray project
- Completed external or multicenter validation through AIFFEL
- Sole authorship where the repository does not establish it
- Production or safety-critical readiness
- Performance values that have not been independently re-run and verified
