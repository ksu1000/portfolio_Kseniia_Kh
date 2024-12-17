# Vegetable Image Classification

## Overview
This project is focused on classifying vegetable images using deep learning techniques. The dataset, available on Kaggle, consists of images of 15 different types of vegetables. The goal is to develop a robust model that can accurately classify these vegetable images into their respective categories. This is a multi-class classification problem.

## Dataset
- **Source**: Kaggle - [Vegetable Image Dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset)
- **Features**: The dataset contains images in `.jpg` format of 15 different vegetable types.
- **Target**: Labels representing the vegetable type (15 classes).

## Approach
- **Data Loading**: ImageDataGenerator is used to load and preprocess the 15,000 images in batches, optimizing computational efficiency.
- **Data Augmentation**: Techniques like rotation, horizontal flips, zooming, shearing, and shifting are applied to enhance dataset diversity and prevent overfitting.
- **Model**: The MobileNetV2 model
  - **Transfer Learning**: A MobileNetV2 model pretrained on ImageNet 
  - **Fine-tuning**: The last two layers are unfrozen for further training.
  - **Regularization**: Dropout and L2 regularization are used to avoid overfitting.
    
## Results
- **Accuracy**: 99.98%
- **AUROC**: 99.99%
- **Misclassifications**: Only 3 misclassifications out of 3,000 test images, demonstrating the model’s robustness.
