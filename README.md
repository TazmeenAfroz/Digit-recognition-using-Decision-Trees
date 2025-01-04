# MNIST Digit Recognition Project

This project performs digit recognition on the MNIST dataset using **Decision Tree** and **Support Vector Machine (SVM)** models.

## Features
- **Dataset**: 42,000 samples of 28x28 pixel grayscale images of handwritten digits (0-9). Each sample is represented by 784 pixel intensity values.
- **Preprocessing**: Min-Max normalization and a 75%-25% train-test split.
- **Models**:
  - Decision Tree Classifier (max depth=15)
  - Support Vector Machine (SVM) with RBF kernel
- **Evaluation**: Accuracy, F1 score, and confusion matrix for model performance.
- **Visualizations**: 
  - Class distribution using bar and pie charts
  - Sample images from the dataset
  - Confusion matrices for model evaluation
  - Decision Tree structure visualization

## Requirements
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `plotly`
- `scikit-learn`
- `graphviz`
- `pydotplus`

## Instructions
1. Place the `mnist.csv` dataset in the project directory.
2. Optionally, test the trained models with a new dataset (`test.csv`).

---
