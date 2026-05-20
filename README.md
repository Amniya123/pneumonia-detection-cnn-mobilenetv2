# Pneumonia Detection from Chest X-ray Images Using CNN and MobileNetV2

This project applies deep learning to solve a real-world binary image classification problem: detecting pneumonia from chest X-ray images.

## Problem Description

The aim of this project is to classify chest X-ray images into two categories:

- NORMAL
- PNEUMONIA

This is a binary image classification task using deep learning models.

## Dataset

The dataset used in this project is the Chest X-ray Pneumonia dataset from Kaggle. The dataset contains chest X-ray images divided into training, validation, and testing folders.

The original classes are:

- NORMAL
- PNEUMONIA

## Models Used

Two deep learning models were implemented:

1. Custom Convolutional Neural Network (CNN)
2. MobileNetV2 Transfer Learning Model

## Evaluation Metrics

The models were evaluated using the following classification metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Final Results

| Model | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Custom CNN | 0.8253 | 0.7909 | 0.9795 | 0.8751 |
| MobileNetV2 | 0.7981 | 0.7640 | 0.9795 | 0.8584 |

## Conclusion

The Custom CNN achieved slightly better test performance than MobileNetV2 in this experiment. Both models achieved high recall, which is important in medical image classification because detecting pneumonia cases is highly significant.

## How to Run

1. Open the notebook in Google Colab.
2. Upload the Kaggle API file.
3. Download the dataset from Kaggle.
4. Run the notebook cells in order.
5. Review the training outputs, classification reports, confusion matrices, and final comparison table.
