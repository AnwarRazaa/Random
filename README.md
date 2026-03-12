# 📊 Linear & Logistic Regression with PyTorch
### Deep Learning Assignment 02 — Spring 2025 | ITU Lahore | MS Data Science

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

---

## 🎯 Project Overview

Implementation of Linear Regression and Logistic Regression from scratch 
using PyTorch, applied to two classic real-world datasets. This project 
demonstrates both traditional ML and deep learning approaches to fundamental 
regression and classification problems.

---

## 📁 Repository Structure
```
Linear-Logistic-Regression-PyTorch/
│
├── task1_linear_regression.py         # Linear Regression — California Housing
├── task2_logistic_regression.py       # Logistic Regression — Titanic
│
├── Task-1 Dataset (California Housing)/
│   ├── california_housing_train.csv
│   └── california_housing_test.csv
│
├── Task-2 Dataset (Titanic)/
│   ├── train.csv
│   ├── test.csv
│   └── gender_submission.csv
│
├── saved_models/
│   ├── linear_model.pkl
│   └── logistic_model.pkl
│
├── results/
│   ├── task1/                         # Linear regression plots
│   └── task2/                         # Logistic regression plots
│
├── Report.pdf                         # Full assignment report
└── DL_Spring_2025_Assignment_02.pdf   # Assignment brief
```

---

## 🔬 Task 1 — Linear Regression

**Dataset:** California Housing Dataset
**Goal:** Predict median house values across California districts

### Key Steps:
- Exploratory data analysis and feature preprocessing
- Linear Regression implementation with PyTorch
- Hyperparameter experiments (learning rate, epochs, batch size)
- Evaluation: MSE, RMSE, R² Score
- Visualization of predictions vs actual values and residuals
```bash
# Single run
python task1_linear_regression.py

# Run all experiments
python task1_linear_regression.py --run_experiments
```

---

## 🔬 Task 2 — Logistic Regression

**Dataset:** Titanic Survival Dataset
**Goal:** Predict passenger survival probability

### Key Steps:
- Data cleaning and missing value imputation
- Feature engineering (Age, Sex, Pclass, Embarked)
- Logistic Regression with PyTorch
- Evaluation: Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Confusion matrix and ROC curve visualization
```bash
# Single run
python task2_logistic_regression.py

# Run all experiments
python task2_logistic_regression.py --run_experiments
```

---

## 📈 Key Concepts Demonstrated

- Linear vs Logistic Regression fundamentals
- PyTorch tensor operations and autograd
- Gradient descent optimization
- Model persistence with pickle
- Hyperparameter tuning experiments
- Comprehensive result logging and visualization

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Core language |
| PyTorch | Deep learning framework |
| Scikit-learn | Preprocessing & evaluation |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Matplotlib | Visualization |

---

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/AnwarRazaa/Linear-Logistic-Regression-PyTorch.git
cd Linear-Logistic-Regression-PyTorch

# Install dependencies
pip install numpy pandas matplotlib scikit-learn
pip install torch --index-url https://download.pytorch.org/whl/cpu
```

---

## 📦 Output

- Trained models saved in `saved_models/`
- Plots and results saved in `results/task1/` and `results/task2/`
- Each experiment saves plots in a separate subfolder

---

## 👤 Author

**Muhammad Anwar Raza**
MS Data Science — Information Technology University (ITU), Lahore
Roll No: MSDS25002

[![GitHub](https://img.shields.io/badge/GitHub-AnwarRazaa-black.svg)](https://github.com/AnwarRazaa)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Muhammad%20Anwar%20Raza-blue.svg)](https://www.linkedin.com/in/muhammad-anwar-raza1/)

---

*Deep Learning — Spring 2025 | Information Technology University, Lahore*
