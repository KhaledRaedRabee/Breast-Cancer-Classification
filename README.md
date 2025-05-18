# Breast Cancer Classification Using Neural Networks

This project uses a simple feedforward neural network to classify breast cancer as malignant or benign based on medical features from the **Breast Cancer Wisconsin dataset**.

---

## 📌 Objective

Train a neural network model to predict whether a tumor is malignant or benign using supervised learning.

---

## 📊 Dataset

- **Source:** `sklearn.datasets.load_breast_cancer()`
- **Features:** 30 numeric features related to cell nuclei
- **Classes:** 2 (Malignant, Benign)

---

## 🔧 Model Architecture

- Input layer: 30 neurons
- Hidden layers: 2 layers with ReLU activations
- Output layer: 1 neuron with sigmoid (binary classification)
- Optimizer: Adam
- Loss: Binary Crossentropy

---

## 📈 Performance

The model achieves high accuracy (~98%) on the test set.

---

## 📦 Requirements

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
