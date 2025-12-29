# Waste-Classification-Senior-Project

## Project Overview
This senior project aims to accurately classify waste material images into several categories using deep learning (DL) models to support and enhance the field of automated waste sorting. 

## Datasets
Dataset for Training: https://www.kaggle.com/datasets/wasifmahmood01/custom-waste-classification-dataset

Dataset for Validation: https://www.kaggle.com/datasets/spellsharp/garbage-data/data

## Current Progress
- Dataset Loading & Inspection
- Data Cleaning (Detecting the presence of any corrupted images)
- Class Distribution Analysis
- Image Preprocessing and Augmentation
- Train/Test/Validation Split
- Computation of Class Weights
- Baseline CNN Experimentations (MobileNetV2 and MobileNetV3-Large)
  - MobileNetV2 Results:
    - Frozen Model Validation Accuracy:  62.50%
    - Frozen Model Macro F1-Score: 0.6820
    - Fine-Tuned Model Validation Accuracy: 71.36%
    - Fine-Tuned Model Macro F1-Score: 0.7809      
  - MobileNetV3-Large Results:
    - Frozen Model Validation Accuracy:  74.89%
    - Frozen Model Macro F1-Score: 0.8401
    - Fine-Tuned Model Validation Accuracy: 77.77%
    - Fine-Tuned Model Macro F1-Score: 0.8366      
