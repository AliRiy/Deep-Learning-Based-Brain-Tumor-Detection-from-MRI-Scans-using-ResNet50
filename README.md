# Deep Learning Based Brain Tumor Detection from MRI Scans using ResNet50
A deep learning project for automatic brain tumor detection from MRI scans using Transfer Learning with ResNet50. This project demonstrates a complete deep learning workflow including data preprocessing, augmentation, model training, fine-tuning, evaluation, and prediction visualization.

# Project Overview
* Brain tumors are life-threatening conditions that require accurate diagnosis from MRI scans. Manual analysis by radiologists can be time-consuming and prone to human error.
* This project uses Convolutional Neural Networks (CNNs) with transfer learning to automatically classify MRI images.
* The model is built using ResNet50 pretrained on ImageNet, which helps extract powerful image features.

# Dataset
* Dataset used:
    - Br35H2 Brain MRI Dataset (https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection)
* Total images: 3000
* Classes:
    - tumor
    - no_tumor

# Dataset Split

| Dataset | Percentage | Images |
| --- | --- | --- |
| Train | 80% | 2400 |
| Validation | 10% | 300 |
| Test | 10% | 300 |

# Technologies Used
* Python
* TensorFlow / Keras
* NumPy
* OpenCV
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
