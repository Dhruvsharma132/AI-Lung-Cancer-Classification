# 🫁 Lung Cancer Detection using DenseNet121

A Deep Learning-based Computer Vision system for automated lung cancer classification using histopathology images.

This project leverages Transfer Learning with DenseNet121 and Explainable AI techniques to classify lung tissue images into multiple cancer categories.

---

## Project Overview

Early detection of lung cancer significantly improves patient outcomes.

This project uses a pre-trained DenseNet121 model combined with transfer learning and advanced image augmentation techniques to classify lung histopathology images into:

- Lung Adenocarcinoma (lung_aca)
- Lung Squamous Cell Carcinoma (lung_scc)
- Normal Lung Tissue (lung_n)

---

## Key Features

✅ DenseNet121 Transfer Learning

✅ Medical Image Classification

✅ Data Augmentation

✅ Early Stopping

✅ Learning Rate Scheduling

✅ Model Checkpointing

✅ Class Weight Balancing

✅ Explainable AI using Grad-CAM

✅ TensorFlow/Keras Implementation

---

## Model Architecture

Input Image (224×224×3)
↓
DenseNet121 (ImageNet Weights)
↓
Global Average Pooling
↓
Dense Layer (512)
↓
Dropout (0.5)
↓
Dense Layer (256)
↓
Dropout (0.3)
↓
Softmax Classification

---

## Tech Stack

### Deep Learning

- TensorFlow
- Keras
- DenseNet121

### Data Science

- NumPy
- Pandas
- Scikit-Learn

### Visualization

- Matplotlib
- Seaborn

### Explainability

- Grad-CAM

---

## Dataset Structure

```text
dataset/
├── train/
│   ├── lung_aca/
│   ├── lung_n/
│   └── lung_scc/
│
├── val/
│   ├── lung_aca/
│   ├── lung_n/
│   └── lung_scc/
│
└── test/
    ├── lung_aca/
    ├── lung_n/
    └── lung_scc/
```
Training Features
Data Augmentation
Rotation
Zoom
Horizontal Flip
Width Shift
Height Shift
Optimization
Adam Optimizer
EarlyStopping
ReduceLROnPlateau
ModelCheckpoint
Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
Explainable AI

Grad-CAM visualizations are generated to highlight image regions contributing most to model predictions, improving transparency for healthcare applications.

Future Improvements
Vision Transformers (ViT)
Swin Transformer
Ensemble Learning
Multi-modal Medical AI
Clinical Deployment via Streamlit
Results

The DenseNet121 architecture achieved strong classification performance on lung cancer histopathology images while maintaining interpretability through Grad-CAM visualizations.

Author

Dhruv Sharma

AI/ML Engineer

GitHub: https://github.com/Dhruvsharma132

LinkedIn: https://linkedin.com/in/dhruv-sharma
