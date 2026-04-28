# 🧠 Brain Tumor Classification Using Machine Learning Models

## 📌 Abstract

Brain tumors are a critical medical condition that require early and accurate diagnosis for effective treatment. This project presents a machine learning-based approach for classifying brain tumors using MRI images. The workflow includes data preprocessing, feature extraction, model training, and evaluation. Multiple machine learning algorithms are applied and compared to determine the most effective model. The results demonstrate that machine learning techniques can significantly assist in automated medical diagnosis.

---

## 📖 Introduction

Brain tumor detection is a challenging task due to the complexity of brain structures and variability in tumor characteristics. Magnetic Resonance Imaging (MRI) is widely used for diagnosis; however, manual analysis can be time-consuming and prone to human error.

This project aims to develop an automated classification system using machine learning models to improve diagnostic accuracy and efficiency.

---

## 🎯 Objectives

* Preprocess MRI images for analysis
* Extract meaningful features from image data
* Train multiple machine learning models
* Evaluate and compare model performance
* Identify the most accurate classification approach

---

## 🗂️ Dataset

https://drive.google.com/drive/folders/184h7_dNP2CVhRe2r8u11tawttPra7ezx?usp=sharing

The dataset consists of labeled MRI brain images categorized into:

* Tumor
* Non-Tumor *(or multiple tumor types, depending on dataset)*

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Resize images to a uniform size
* Convert images into numerical arrays
* Normalize pixel values
* Handle missing or corrupted data

---

### 2. Dataset Splitting

* Divide data into training and testing sets
* Typical ratio: **80% training / 20% testing**
* Ensure balanced class distribution

---

### 3. Feature Extraction

* Flatten image data into feature vectors
* Prepare input features (`X`) and labels (`y`)

---

### 4. Model Development

The following machine learning models are used:

* Support Vector Machine (SVM)
* Random Forest
* K-Nearest Neighbors (KNN)
* Logistic Regression

---

### 5. Model Training

* Train models using the training dataset
* Learn patterns between input features and labels

---

### 6. Prediction

* Apply trained models to testing data
* Generate predicted labels

---

### 7. Model Evaluation

Evaluate performance using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📊 Results

* **Random Forest** achieved the highest accuracy
* **SVM** showed strong and consistent performance
* **KNN** performed moderately depending on parameter tuning
* **Logistic Regression** provided baseline performance
<img width="1564" height="590" alt="image" src="https://github.com/user-attachments/assets/6dbe6d3f-4563-4215-a86a-b2cb50241d64" />
<img width="1564" height="590" alt="image" src="https://github.com/user-attachments/assets/c8ac219d-ec99-4f39-954f-a6164c5cbb0b" />
<img width="394" height="104" alt="image" src="https://github.com/user-attachments/assets/9347543d-383a-4e2f-8de4-f45cc4036996" />

👉 Ensemble methods like Random Forest showed better robustness and generalization.

---

## ✅ Conclusion

This project demonstrates that machine learning models can effectively classify brain tumors from MRI images. Among the evaluated models, **Random Forest** performed the best.

The system highlights the potential of AI in assisting medical professionals with faster and more accurate diagnoses.

---

## 🚀 Future Work

* Implement deep learning models (e.g., CNNs)
* Increase dataset size
* Apply data augmentation techniques
* Optimize model parameters

---
