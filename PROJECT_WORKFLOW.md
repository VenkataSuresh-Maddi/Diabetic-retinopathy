# Project Workflow

## AI-Based Diabetic Retinopathy Detection

### Workflow

APTOS 2019 Dataset  
↓  
Image Preprocessing  
↓  
SMOTE Class Balancing  
↓  
EfficientNet-B0 + DenseNet121  
↓  
Feature Fusion  
↓  
DR Severity Classification  
↓  
Grad-CAM Visualization

## Workflow Description

### 1. APTOS 2019 Dataset
Retinal fundus images are collected from the APTOS 2019 dataset and used as the input data.

### 2. Image Preprocessing
The retinal images are resized, normalized, and enhanced before model processing.

### 3. SMOTE Class Balancing
SMOTE is applied to address class imbalance in the dataset.

### 4. Feature Extraction
EfficientNet-B0 and DenseNet121 are used to extract important features from the retinal fundus images.

### 5. Feature Fusion
The features extracted from EfficientNet-B0 and DenseNet121 are combined to form a hybrid feature representation.

### 6. DR Severity Classification
The fused hybrid representation is used to classify diabetic retinopathy into different severity levels.

### 7. Grad-CAM Visualization
Grad-CAM is used to provide an explainable visual interpretation by highlighting important retinal regions related to the model prediction.

## Overall Flow

Fundus Images → Preprocessing → SMOTE → EfficientNet-B0 + DenseNet121 → Feature Fusion → Classification → Grad-CAM

## Project Output

The system provides automated diabetic retinopathy severity classification along with a visual explanation of the retinal regions considered important by the model.
