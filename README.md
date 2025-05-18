# 🧠 Breast Cancer Classification with Neural Networks

A clean, minimal implementation of a fully-connected neural network to classify breast cancer tumors as **malignant** or **benign**, using the popular Breast Cancer Wisconsin dataset.

---

## 📌 Project Objective

The goal is to develop a neural network model that can accurately predict the likelihood of a tumor being malignant or benign, based on medical diagnostic features. The project emphasizes interpretability and performance using classic machine learning techniques.

---

## 🔬 Dataset Overview

- **Source:** `sklearn.datasets.load_breast_cancer()`
- **Samples:** 569
- **Features:** 30 numerical predictors (e.g., radius, texture, area)
- **Target classes:** 
  - `0` = Malignant
  - `1` = Benign

---

## 🏗️ Model Architecture

| Layer         | Description              |
|---------------|--------------------------|
| Input         | 30 neurons (1 per feature) |
| Dense 1       | 16 neurons + ReLU        |
| Dense 2       | 8 neurons + ReLU         |
| Output        | 1 neuron + Sigmoid       |

- **Loss function:** Binary Crossentropy  
- **Optimizer:** Adam  
- **Metric:** Accuracy  

---

## 📈 Results

- **Training Accuracy:** ~99%
- **Test Accuracy:** ~98%
- **Loss convergence:** Smooth with minimal overfitting

> 💡 Confusion matrix and classification report confirm strong generalization.

---

## 🧪 Reproducibility

Clone and run:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
