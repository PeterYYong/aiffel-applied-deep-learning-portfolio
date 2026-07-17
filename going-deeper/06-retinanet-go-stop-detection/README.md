# RetinaNet GO/STOP Driving-Assistance Object Detection

- **Curriculum:** AIFFEL Research Program / GoingDeeper / GD06
- **Category:** Training project
- **Notebook:** [`retinanet-go-stop-object-detection.ipynb`](retinanet-go-stop-object-detection.ipynb)

## Overview

This coursework notebook builds a prototype GO/STOP decision system from KITTI road-scene images. It trains a RetinaNet-style object detector and applies simple rules to recommend stopping when a person is detected or when a detected vehicle exceeds a defined bounding-box size.

## Verified scope

- Inspected and preprocessed the KITTI object-detection dataset.
- Implemented anchor generation, label encoding, data augmentation, and box transformations.
- Built a feature pyramid, RetinaNet detection heads, focal classification loss, and bounding-box regression loss.
- Trained and reloaded model checkpoints and inspected the training history.
- Decoded detections with non-maximum suppression and implemented the GO/STOP decision logic.
- Examined predicted classes, confidence scores, and bounding-box dimensions as decision evidence.

## Limitations

- Training was limited, and the notebook reflection identifies an earlier checkpoint as better than later epochs.
- Bounding-box visualization for the final evaluation images remained incomplete.
- No independently verified detection or safety-performance metric is reported.
- This is a course prototype and must not be used for real-world driving decisions.
