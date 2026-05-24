# Brain Tumor Classification

A machine learning and deep learning project that classifies brain MRI scans into four categories:

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

This project compares classical ML models with a CNN-based deep learning model to evaluate which approach performs better for medical image classification.

---

# Problem Statement

Brain tumors are life-threatening if not detected early, and accurate diagnosis is essential for effective treatment. MRI imaging provides detailed insights, but analyzing these images manually is time-consuming and requires expert radiologists.

This project explores how Artificial Intelligence can assist in automating brain tumor classification using machine learning and deep learning techniques.

---

# Project Objectives

- Build a complete MRI image classification pipeline
- Compare classical Machine Learning models with Deep Learning
- Analyze strengths and weaknesses of each approach
- Evaluate performance using standard classification metrics
- Explore the effectiveness of transfer learning in medical imaging

---

# Models Used

## Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest

## Deep Learning Model
- MobileNetV2 (Transfer Learning)

---

# Dataset

The project uses the Kaggle Brain Tumor MRI dataset containing:

- 3,264 MRI images
- 4 tumor classes
- Predefined training and testing sets

## Class Encoding

| Label | Class |
|---|---|
| 0 | Meningioma |
| 1 | Glioma |
| 2 | Pituitary Tumor |
| 3 | No Tumor |

---

# Results

| Model | Accuracy |
|---|---|
| Random Forest | 69.79% |
| Decision Tree | 72.33% |
| Logistic Regression | 74.36% |
| MobileNetV2 | **83.50%** |

The deep learning model achieved the best performance because CNNs can learn image features such as shapes, textures, and edges directly from MRI scans.

---

# Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---
