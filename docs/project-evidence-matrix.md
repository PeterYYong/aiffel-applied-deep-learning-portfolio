# Project Evidence Matrix

This matrix controls what may be claimed in a CV, application, or public portfolio. It is intentionally conservative.

| Unit | Evidence-supported description | Contribution label | Portfolio use | Remaining action |
|---|---|---|---|---|
| Ex01 | Tabular regression exercises; preprocessing, train/test split, and error metrics | Individual coursework with peer review | Foundation | Add dataset/license and concise result summary |
| Ex02 | House-price prediction based substantially on provided baseline | Individual coursework / provided baseline | Archive or foundation | Document exactly what changed from baseline |
| Ex03 | Facial landmark placement and transformation-aware image processing | Individual coursework with peer review | Selected | Add reproducible run instructions |
| Ex04 | Object detection/segmentation, masks, background manipulation, and debugging | Individual coursework with peer review | Selected | Add data/model attribution |
| Ex05 | Korean sentiment preprocessing and LSTM/Conv1D/GlobalMaxPooling comparisons | Individual coursework with peer review | Selected | Verify final metrics before quoting them |
| Ex06 | Sequence-to-sequence summarization with attention | Coursework; README evidence incomplete | Supporting | Complete authorship and result summary |
| Ex07 | Subword tokenization and encoder–decoder Transformer chatbot | Individual coursework with peer review | Selected | Add dataset/license and environment |
| GD01 | ResNet-50 versus PlainNet-50 ablation and skip-connection interpretation | Individual coursework with peer review | Featured | Add exact reproducibility details |
| GD02 | Normalization, augmentation, CutMix/MixUp, and model persistence | Individual coursework with peer review | Featured | Summarize controlled comparison |
| GD03 | CAM/Grad-CAM visualization, localization correction, and IoU inspection | Individual coursework with peer review | Featured | Separate completed and exploratory extensions |
| GD04 | Unverified unit | Unverified | Exclude | Inspect notebook and replace template README |
| GD05 | TFRecord, prior boxes, SSD face detection, and score debugging | Individual coursework with peer review | Selected | Add model/data attribution |
| GD06 | Unverified unit | Unverified | Exclude | Inspect notebook and replace template README |
| GD07 | U-Net/U-Net++ implementation and exploratory lung-segmentation extension | Coursework with peer review | Featured after provenance correction | Correct coder-name typo; avoid clinical-performance claims |
| GD08 | SimpleBaseline pose estimation and direct ResNet-block implementation | Coursework with peer review | Selected after provenance correction | Correct coder-name typo and document dataset |
| GD09 | Unverified unit | Unverified | Exclude | Inspect notebook and replace template README |
| MainQuest 01 | Subword preprocessing and GPT-style decoder-only dialogue model | Coursework; README evidence incomplete | Selected after documentation | Add contribution, dataset, result, and limitations |
| MainQuest 02 | Limited-data lung-image segmentation and architecture comparison | Coursework; README evidence incomplete | Selected after documentation | Add contribution, split, metrics, and data provenance |
| MainQuest 03–05 | No verified completion evidence in current README files | Unverified | Exclude | Inspect notebook contents before naming or claiming completion |

## Claim levels

- **Featured:** code, result, authorship, and peer-review evidence are present; still describe it as training.
- **Selected:** useful technical evidence, but documentation or reproducibility needs improvement.
- **Supporting/Foundation:** demonstrates breadth but should not occupy a pinned-project slot.
- **Exclude:** do not describe as completed until evidence is added.

## Prohibited claims

- Clinically validated medical model
- Completed external or multicenter validation through AIFFEL
- Sole authorship of team or peer repositories
- Production MLOps system
- Performance values that have not been re-run and verified

