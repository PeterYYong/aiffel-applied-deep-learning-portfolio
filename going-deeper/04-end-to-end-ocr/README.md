# End-to-End OCR: Text Detection and CRNN-CTC Recognition

- **Curriculum:** AIFFEL Research Program / GoingDeeper / GD04
- **Category:** Training project
- **Notebook:** [`end-to-end-ocr-crnn-ctc.ipynb`](end-to-end-ocr-crnn-ctc.ipynb)

## Overview

This coursework notebook explores an end-to-end optical character recognition pipeline. It combines Keras-OCR text-region detection with recognition experiments on MJ text data stored in LMDB format, and it implements a custom CRNN recognizer trained with CTC loss.

## Verified scope

- Loaded MJ training, validation, and test data from LMDB files.
- Detected, cropped, annotated, and recognized text regions with Keras-OCR.
- Encoded character labels and prepared batches with a custom dataset sequence.
- Built CRNN and CTC-loss training and inference workflows.
- Added checkpoint, training-history, decoding, and text-similarity evaluation utilities.

## Limitations

- The notebook reports inconsistent weight loading and weak recognition results.
- Additional training and model refinement were not completed within the course schedule.
- No final performance metric has been independently re-run or verified.
- The notebook uses course-environment paths and is not a production OCR system.
