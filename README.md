<!-- Banner -->
<p align="center">
  <img src="https://dummyimage.com/1200x250/0a0a0a/00eaff&text=Machine+Learning+Projects+%7C+AbderrezzakMrch" alt="Machine Learning Banner">
</p>

<h1 align="center">🧠 MachineLearning-Projects</h1>

<p align="center">
A complete collection of hands-on Machine Learning implementations — from beginner to intermediate — built step-by-step while learning ML theory and practice.
</p>

---

## 🌟 Badges

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue">
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange">
  <img src="https://img.shields.io/badge/License-MIT-green">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen">
  <img src="https://img.shields.io/github/stars/AbderrezzakMrch/MachineLearning-Projects?style=social">
</p>

---

# 🧠 MachineLearning-Projects  
A complete collection of hands-on **Machine Learning implementations** — from beginner to intermediate — where each algorithm is coded **from scratch** and also tested using **scikit-learn**.

This repository represents my journey learning Machine Learning step-by-step and experimenting with real datasets, model evaluation, tuning, and visualization.

---

## 🚀 What’s Inside?

This repo contains **20+ well-organized ML projects**, covering:

### 🔧 Supervised Learning
- Linear Regression (Single & Multiple Variables)
- Gradient Descent
- Logistic Regression (Binary & Multiclass)
- Decision Trees
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes Classifier
- Random Forest
- L1 & L2 Regularization (Lasso, Ridge)

### 📊 Unsupervised Learning
- K-Means Clustering
- Principal Component Analysis (PCA)

### 🧪 Model Evaluation
- Train/Test Split
- K-Fold Cross Validation
- Confusion Matrix, Accuracy

### ⚙️ Optimization & Tuning
- Hyperparameter Tuning (GridSearchCV)
- One-Hot Encoding & Feature Engineering

### 🤖 Ensemble Learning
- Bagging (Bootstrap Aggregating)

Each project folder contains:
- Code implementation  
- Dataset or example  
- Plots & results  
- Step-by-step explanation  

---

## 📂 Repository Structure
```bash
MachineLearning-Projects/
│
├── 1-Linear Regression Single Variables/
├── 2-Linear Regression Multiple Variables/
├── 3-Gradient Descent and Cost Function/
├── 4-Save Model/
├── 5-Dummy Variables & One Hot Encoding/
├── 6-Train Test Split/
├── 7-Logistic Regression (Binary Classification)/
├── 8-Logistic Regression (Multiclass Classification)/
├── 9-Decision Tree/
├── 10-Support Vector Machine (SVM)/
├── 11-Random Forest/
├── 12-K Fold Cross Validation/
├── 13-K Means Clustering/
├── 14-Naive Bayes Classifier/
├── 16-Hyperparameter Tuning (GridSearchCV)/
├── 17-L1 and L2 Regularization/
├── 18-KNN Classification/
├── 19-PCA/
└── 20-Ensemble Learning - Bagging/
```
---

## 🛠️ Installation

### Clone the repository:

```bash
git clone https://github.com/AbderrezzakMrch/MachineLearning-Projects.git
cd MachineLearning-Projects
```

### Install dependencies:

```bash
pip install -r requirements.txt
```

 ### Recommended requirements.txt:
 
```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
```
---

## 📘 Example Syntax
### 📌 Linear Regression (scikit-learn)
```bash
from sklearn.linear_model import LinearRegression
import numpy as np

X = np.array([[1], [2], [3], [4]])
y = np.array([2, 4, 6, 8])

model = LinearRegression()
model.fit(X, y)

print("Prediction for 5 =", model.predict([[5]]))
```
### 📌 Logistic Regression
```bash
from sklearn.linear_model import LogisticRegression

clf = LogisticRegression()
clf.fit(X_train, y_train)

pred = clf.predict(X_test)
```
### 📌 K-Fold Cross Validation
```bash
from sklearn.model_selection import KFold, cross_val_score

kf = KFold(n_splits=5, shuffle=True, random_state=42)
scores = cross_val_score(model, X, y, cv=kf)

print("Average accuracy:", scores.mean())
```
### 📌 Hyperparameter Tuning (GridSearchCV)
```bash
from sklearn.model_selection import GridSearchCV
from sklearn.svm import SVC

params = {"C": [0.1, 1, 10], "kernel": ["linear", "rbf"]}

grid = GridSearchCV(SVC(), params, cv=5)
grid.fit(X_train, y_train)

print("Best parameters:", grid.best_params_)
```
---

## 🎯 Goals of this Repository

Learn ML algorithms from scratch + with libraries

Understand math and intuition behind ML

Practice on real datasets

Explore tuning, preprocessing, validation

Build a strong foundation for future AI projects

---

## 🏅 Status
```bash
✔️ All ML algorithms implemented
✔️ PCA + Feature Engineering added
✔️ Ensemble Learning added
✔️ Clean structured folders
✔️ Beginner-friendly explanations
```
---

## 📄 License
```bash
This project is licensed under the MIT License.
```
---

## ⭐ Support
```bash
If this repo helped you, consider giving it a ⭐ star — it motivates me to build more ML projects!
```
---

<p align="center"><b>Made with ❤️ by AbderrezzakMrch</b></p> ```
