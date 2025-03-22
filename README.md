# Classic Machine Learning Algorithms from Scratch

This repository contains educational implementations of foundational machine learning algorithms using only NumPy. It includes the Perceptron algorithm and Support Vector Machine (SVM) training via the SMO (Sequential Minimal Optimization) method.

---

## 📁 Notebooks

### 1. `perceptron.ipynb`
Implements the classic Perceptron algorithm with Pocket modification for binary classification.

- Learns a linear hyperplane to separate two classes
- Updates weights iteratively based on misclassified samples
- Pocket algorithm stores the best weights found during training

### 2. `svm.ipynb`
Implements the SMO algorithm for SVM training from scratch, supporting both linear and RBF kernels.

- One-vs-Rest multi-class classification using Iris dataset
- Hyperparameter tuning for C and gamma
- Detailed evaluation using accuracy, confusion matrix, and sensitivity

---

## 🚀 Technologies Used
- Python
- NumPy
- Matplotlib
- scikit-learn (only for dataset loading and evaluation)
- tqdm (for progress bars)

---

## 🎯 Goal
To deepen understanding of how fundamental ML algorithms work under the hood — without relying on machine learning libraries like scikit-learn or TensorFlow.

---

## 👤 Author
Ido  
GitHub: [@Ido11118](https://github.com/Ido11118)

