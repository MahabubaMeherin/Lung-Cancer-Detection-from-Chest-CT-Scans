# 🫁 Lung Cancer Detection from Chest CT Scans

### Hybrid Deep Learning and Machine Learning Approach using ResNet50 Transfer Learning and SVM Classification

## 📌 Overview

This project presents a hybrid Deep Learning and Machine Learning framework for automated lung cancer detection from chest CT scan images.

The system utilizes ResNet50 Transfer Learning for deep feature extraction and Support Vector Machine (SVM) classification to identify different types of lung cancer from medical imaging data.

The project was initially developed as part of my undergraduate thesis research and was later improved by incorporating advanced training strategies, fine-tuning techniques, and more comprehensive evaluation methods.

## 🎯 Objectives

- Develop an automated lung cancer classification system
- Detect and classify multiple lung cancer types from CT scan images
- Explore the effectiveness of Transfer Learning in medical imaging
- Compare CNN-based classification with CNN feature extraction + SVM classification
- Evaluate model performance using multiple assessment metrics

## 🛠️ Tools & Technologies

- Python
- TensorFlow
- Keras
- ResNet50 (Transfer Learning)
- Support Vector Machine (SVM)
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Jupyter Notebook

## 🔬 Methodology

### Data Preprocessing

- Image resizing and normalization
- Dataset preparation and organization
- Class balancing using class weights

### Deep Feature Extraction

- ResNet50 pretrained on ImageNet
- Transfer Learning for CT scan feature extraction
- Fine-tuning of selected layers to improve domain adaptation

### Classification

- CNN-based classification using ResNet50
- SVM classification using deep features extracted from the CNN
- Comparative evaluation of both approaches

### Training Optimization

- Early Stopping
- Learning Rate Scheduling
- Model Checkpointing
- Performance Monitoring

## 📂 Dataset

Chest CT Scan Images Dataset

### Classes

- Adenocarcinoma
- Large Cell Carcinoma
- Squamous Cell Carcinoma
- Normal

Dataset Source:
https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images

## 📈 Model Performance

| Metric | Score |
|----------|----------|
| Test Accuracy | 85.4% |
| Precision | 86.9% |
| Recall | 85.4% |
| ROC-AUC | 96.7% |

## 📊 Key Features

- ResNet50 Transfer Learning
- Deep Feature Extraction
- SVM Classification
- CNN vs CNN+SVM Comparison
- ROC Curve Analysis
- Confusion Matrix Visualization
- Multi-Class Classification
- Fine-Tuning Strategy
- Comprehensive Performance Evaluation

## 📖 Project Evolution

This project was originally developed as my undergraduate thesis work. After gaining additional experience in Machine Learning and Deep Learning, I revisited the project and improved it by incorporating Transfer Learning, Fine-Tuning, Early Stopping, Learning Rate Scheduling, SVM-based feature classification, and more rigorous evaluation techniques.

The current repository reflects the enhanced version of the original research project.

## 🚀 Future Improvements

- Explainable AI using Grad-CAM
- Larger and more diverse medical datasets
- Vision Transformer (ViT) implementation
- Web-based deployment
- Clinical validation and testing

