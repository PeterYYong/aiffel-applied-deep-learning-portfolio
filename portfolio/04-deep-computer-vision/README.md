# Deep Computer Vision

Architecture comparison, augmentation, explainability, OCR, detection, segmentation, and pose estimation from the AIFFEL GoingDeeper track.

- [ResNet/PlainNet Ablation](../../going-deeper/01-resnet-plainnet-ablation/): Cats-vs-dogs comparison across 34- and 50-layer residual and plain networks.
- [Stanford Dogs Augmentation](../../going-deeper/02-stanford-dogs-augmentation/): standard augmentation, CutMix, and MixUp comparison.
- [CAM/Grad-CAM Localization](../../going-deeper/03-cam-gradcam-localization/): activation maps, bounding boxes, and IoU inspection.
- [End-to-End OCR](../../going-deeper/04-end-to-end-ocr/): Keras-OCR detection and CRNN/CTC recognition; final recognition quality remained incomplete.
- [SSD Face Detection](../../going-deeper/05-ssd-face-detection/): WIDER FACE, priors, SSD, landmarks, and sticker overlay.
- [RetinaNet GO/STOP Detection](../../going-deeper/06-retinanet-go-stop-detection/): KITTI, FPN, focal loss, decoded detections, and rule-based decisions; not safety validated.
- [U-Net/U-Net++ Segmentation](../../going-deeper/07-unet-unetpp-segmentation/): KITTI road segmentation plus an exploratory lung-segmentation extension.
- [Human Pose Estimation](../../going-deeper/08-human-pose-estimation/): MPII Stacked Hourglass versus SimpleBaseline comparison with overfitting/weak-output limitations retained.

All items are training evidence. They do not establish clinical validation, deployment readiness, or sole authorship beyond the available course records.
