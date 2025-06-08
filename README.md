# Brain Tumor Detection and Localization

Deep learning-based system for brain tumor detection and segmentation from MRI scans using ResNet and ResUNet architectures.

## Overview
This project implements a two-stage approach for brain tumor analysis:
- **Classification**: ResNet-based model to detect tumor presence
- **Segmentation**: ResUNet for precise tumor localization and boundary delineation

## Dataset
- **Source**: [LGG MRI Segmentation Dataset](https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation)
- **Size**: ~4000 MRI scans with manual FLAIR abnormality segmentation masks
- **Origin**: The Cancer Imaging Archive (TCIA)

## Performance Metrics
- **Accuracy**: 98%
- **Precision**: 0.98
- **Recall**: 0.96
- **F1 Score**: 0.98

## Model Architecture
### ResNet (Classification)
- Deep CNN with residual connections
- Addresses vanishing gradient problem
- Multiple residual blocks with skip connections

### ResUNet (Segmentation)
- Hybrid of ResNet and U-Net architectures
- Encoder-decoder structure with skip connections
- Captures both contextual and spatial information

## Technologies
- PyTorch
- OpenCV
- NumPy, Pandas
- Matplotlib
- scikit-learn

## Results
![Brain Tumor Segmentation Results](https://github.com/user-attachments/assets/de83e7d2-a957-4183-8b16-c2daf25c4d47)

## Key Features
- Automated tumor detection from MRI scans
- Precise tumor boundary segmentation
- High accuracy suitable for clinical assistance
- Efficient preprocessing pipeline
