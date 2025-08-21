# Iris Flower Classification

A simple supervised machine learning classification project that predicts the species of an iris flower based on petal and sepal measurements.

---

## 📊 Dataset
- Source: https://www.kaggle.com/datasets/arshid/iris-flower-dataset
- Features: Petal length/width, Sepal length/width
- Target: Species (Setosa, Versicolor, Virginica)

---

## ⚙️ Modelling
- Cross-validated 5 models:
      | Model                   | CV Score | Training Time (s) |
      |--------------------------|----------|------------------|
      | Logistic Regression      | 0.932    | 1.09             |
      | Decision Tree Classifier | 0.961    | 0.67             |
      | Random Forest Classifier | 0.961    | 0.64             |
      | SGD Classifier           | 0.932    | 0.02             |
      | Support Vector Classifier| 0.922    | 0.01             |
- Selected Logistic Regression for hyperparameter tuning (grid search) for its balanced performance and better generalization compared to other models.

---

## 🏆 Results
- **Model**: Logistic Regression
- **Accuracy (test set)**: 0.96

---
