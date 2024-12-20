# Pneumonia Detection from Chest X-Rays

## Overview
This project focuses on detecting pneumonia from chest X-ray images using deep learning techniques. The model performs both **segmentation** (detecting pneumonia-affected areas) and **classification** (indicating whether pneumonia is present). The dataset used is the [RSNA Pneumonia Processed Dataset on Kaggle](https://www.kaggle.com/datasets/iamtapendu/rsna-pneumonia-processed-dataset) from Kaggle.

## Dataset
- **Features**: Chest X-ray images and patient metadata (age, sex).
- **Target**: 
  - **Segmentation Mask**: Identifies pneumonia-affected areas.
  - **Binary Target**: Indicates pneumonia presence (1) or healthy (0).

## Approach
- **Model**: Multi-input, multi-output U-Net architecture with residual blocks for segmentation, late fusion for combining image and numerical data inputs.
- **Loss Function**: Custom weighted loss function to address class imbalance in the classification task.
- **Metrics**: Evaluation using **accuracy**, **precision**, **recall**, **AUROC** for classification, and **IoU** for segmentation.

## Results
- **IoU**: 0.7077
- **Accuracy**: 0.9315
- **Recall**: 0.8949

The model demonstrates strong performance in both segmentation and classification tasks.

