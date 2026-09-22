# Diabetic-retinopathy
# A Hybrid Deep Learning Approach With Explainable AI for Diabetic Retinopathy Classification

Department of Computer Science & Engineering (Artificial Intelligence & Machine Learning)

Vasireddy Venkatadri Institute of Technology (VVIT)

Major Project | Batch ID: AIML-C-14

Abstract
Diabetic Retinopathy (DR) is a primary cause of vision loss globally, but early detection can significantly prevent severe vision impairment. Traditional screening relies on manual evaluation by ophthalmologists, which is time-consuming and subject to inconsistency. Automated detection using Deep Learning on retinal fundus images offers scalable screening, yet many current approaches lack transparency (Explainable AI) and suffer from severe class imbalance across disease severity stages. This project proposes a robust and interpretable framework for multi-class Diabetic Retinopathy classification using deep learning, ensemble learning, and Explainable AI (XAI). Synthetic Minority Over-sampling Technique (SMOTE) is applied to handle dataset imbalance across severity grades (No DR, Mild, Moderate, Severe, Proliferative DR). Pre-trained architectures including ResNet18, EfficientNetB0, DenseNet121, and MobileNetV2 are trained and evaluated alongside hard/soft voting ensemble strategies. A custom feature-level hybrid architecture combining EfficientNetB0 and DenseNet121 is developed to capture complementary representations. Gradient-weighted Class Activation Mapping (Grad-CAM) with quantitative concentration scoring is integrated to highlight diagnostically relevant retinal regions, enhancing clinical trustworthiness. The system is built using Python, PyTorch, and OpenCV, with models trained on the APTOS 2019 dataset.

Detailed Plan of Action
The project workflow is divided into five phases.

Phase 1: Preprocessing & Class Balancing
Normalize and resize fundus images to 224x224. Apply Synthetic Minority Over-sampling Technique (SMOTE) on pixel representations to address severe class imbalance across the five DR severity grades.

Phase 2: Backbone Model Training
Train and fine-tune multiple pre-trained Convolutional Neural Networks (ResNet18, EfficientNetB0, DenseNet121, and MobileNetV2) for multi-class DR severity classification.

Phase 3: Hybrid & Ensemble Architecture
Combine EfficientNetB0 and DenseNet121 into a feature-level hybrid architecture. Implement hard and soft voting ensemble strategies across the base backbones to improve overall prediction accuracy.

Phase 4: Performance & Metrics Evaluation
Evaluate models using comprehensive metrics, including Accuracy, Precision, Recall, F1-Score, Confusion Matrices, and per-class ROC-AUC curves.

Phase 5: Explainable AI & Interpretability
Generate qualitative Grad-CAM heatmaps to visualize retinal lesions (e.g., microaneurysms, hemorrhages, exudates). Compute quantitative Grad-CAM concentration scores to measure spatial attention localization.

Data Preprocessing & SMOTE Class Balancing Multi-class CNN Backbone Training Hybrid Feature Fusion & Ensemble Learning Performance Evaluation & ROC-AUC Analysis Grad-CAM Visualizations & Quantitative Interpretabilitynical trustworthiness.
