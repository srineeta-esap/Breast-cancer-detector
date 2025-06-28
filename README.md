# Breast Cancer Detector

A machine learning project to classify breast cancer tumors as malignant or benign using the Wisconsin Breast Cancer dataset and the K-Nearest Neighbors (KNN) algorithm.

## 💡 Overview
This model uses 30 numerical features from digitized biopsies to predict the diagnosis (Malignant or Benign). The model is optimized using 10-fold cross-validation.

## 🔧 Tech Stack
- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Sklearn (KNeighborsClassifier, train_test_split, cross_val_score)

## 🎯 Model Performance
- Test Accuracy: ~96%
- Optimal k: 13 (found via cross-validation)

## 📈 Visualizations
- Feature comparison plots (`radius_mean`, `texture_mean`, etc.)
- Misclassification error vs. k

## 📁 Dataset
- Source: [Kaggle – Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

---


