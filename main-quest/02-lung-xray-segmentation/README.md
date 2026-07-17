# Limited-Data Lung X-Ray Segmentation

> **Category:** AIFFEL training project  
> **Curriculum unit:** AIFFEL Research Program / MainQuest / Quest02  
> **Artifact:** [`lung-xray-unet-encoder-comparison.ipynb`](lung-xray-unet-encoder-comparison.ipynb)

## Project scope

This notebook compares convolutional segmentation architectures for lung masks in frontal chest X-rays. It retrieves 539 paired CHNCXR images and masks from the external [`FlashChoi5657/Lung_segmentation`](https://github.com/FlashChoi5657/Lung_segmentation) repository, resizes them to 128 × 128 pixels, and uses 100 training, 49 validation, and 54 test images in the stored run.

The implemented comparison includes a U-Net trained from scratch, an ImageNet-pretrained VGG16 encoder with a U-Net-style decoder, and an ImageNet-pretrained ResNet50 encoder with a U-Net-style decoder. The workflow uses Dice loss, Dice coefficient, and pixel accuracy, with saved training and evaluation outputs.

## Verified status

- All 44 code cells in the stored notebook were executed without a recorded runtime error.
- The stored run reports a test Dice coefficient of approximately 0.950 for VGG16-U-Net; the plain U-Net and ResNet50-U-Net runs show near-failure test Dice values.
- These are notebook-recorded educational results and have not been independently reproduced.

## Limitations

- The inputs are **chest X-rays, not CT images**. This project must not be represented as CT segmentation experience.
- Dataset licensing, the original dataset citation, and redistribution terms are not documented in the notebook.
- Only 100 images are used for training, and there is no external, multicenter, or clinical validation.
- The code defines precision, recall, and IoU calculations, but verified output values for those metrics are not retained.
- The original README did not identify the coder or reviewer. Whether this was individual or team work, and the candidate's exact contribution, remain unverified.
- This is a training exercise and does not establish clinical performance or deployment readiness.
