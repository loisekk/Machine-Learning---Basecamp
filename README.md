# 🏕️ Machine Learning Basecamp

> A complete, beginner-friendly Machine Learning series — from raw data to advanced models. Every concept is backed by theory, real-world intuition, and hands-on projects.

---

## 📚 Series Overview

| Part | Topic | Status |
|------|-------|--------|
| [Part 1 — Foundations](#part-1--ml-foundations) | EDA, Data Cleaning, Feature Engineering | ✅ Done |
| [Part 2 — Regression](#part-2--regression) | Linear Regression, Cost Function, Gradient Descent | ✅ Done |
| [Part 3 — Classification](#part-3--classification) | Logistic Regression, KNN, SVM, Decision Trees, Naive Bayes | ✅ Done |
| [Part 4 — Advanced ML](#part-4--advanced-ml) | Ensemble Methods, Clustering, PCA, XGBoost | ✅ Done |

---

## Part 1 — ML Foundations

> *"Most critical and often ignored steps in ML — but they make or break your model's success."*

### What You'll Learn
- How to define a problem clearly
- Where and how to collect quality data
- Exploratory Data Analysis (EDA) — the right way
- Data Cleaning & Preprocessing techniques
- Feature Selection — choosing what matters
- Feature Engineering — boosting model performance

### 🔬 Projects

#### Project 1 — Heart Disease Analysis
Performed full EDA on a clinical heart disease dataset. Key work includes:
- Handled zero-value anomalies in `Cholesterol` and `RestingBP` via mean imputation
- Visualized distributions (histplots, violin plots) and relationships (heatmaps, countplots)
- Applied One-Hot Encoding for categorical features
- Scaled numerical features using `StandardScaler` — model-ready output

**Dataset:** `heart.csv` | **Notebook:** [`Heart_Dataframe.ipynb`](./Heart_Dataframe.ipynb)

#### Project 2 — Insurance Charges Analysis
End-to-end preprocessing pipeline on an insurance dataset. Key work includes:
- Applied Label Encoding for binary columns (`sex`, `smoker`)
- Applied One-Hot Encoding for the `region` column
- Engineered a new `bmi_category` feature (Underweight / Normal / Overweight / Obese)
- Used **Pearson Correlation** and **Chi-Square tests** for statistical feature selection
- Final feature set selected for predicting insurance `charges`

**Dataset:** `insurance.csv` | **Notebook:** [`Insurance_Dataframe.ipynb`](./Insurance_Dataframe.ipynb)

---

## Part 2 — Regression

### What You'll Learn
- What is Regression and where it's used
- Linear Regression — concept and intuition
- Cost Function and Gradient Descent (light intro)
- Scikit-learn implementation of Linear Regression
- Model Evaluation: MSE, RMSE, R² Score
- Train-Test Split — why it matters
- Overfitting vs Underfitting with visuals

### 🔬 Project — House Price Prediction
Predicting house prices using Linear Regression on real-world data.

**Resources:**
- 📓 [Kaggle Notebook](https://www.kaggle.com/code/akarshvyas/notebook9fdd2dc0b8)
- 💻 [Colab Notebook](https://colab.research.google.com/drive/1QlZkG9BSj_JHeqcjidEuVj-gTmwxLvBi?usp=sharing)

---

## Part 3 — Classification

### What You'll Learn
- What is Classification and where it's used
- Logistic Regression — binary classification
- K-Nearest Neighbors (KNN) — classifying by similarity
- Decision Trees — learning decisions step by step
- Naive Bayes — probabilistic and powerful
- Support Vector Machine (SVM) — drawing the best boundary
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

### 🔬 Project — Titanic Survival Classification
Classifying survival outcomes using real Titanic data with multiple algorithms.

**Resources:**
- 💻 [Colab Notebook](https://colab.research.google.com/drive/1iIujBR7WcySa15Z3JLdVRKcHT7YO-q9X?usp=sharing)
- 🐙 [GitHub Code](https://github.com/AkarshVyas/Machine-Learning-Part-3)

---

## Part 4 — Advanced ML

### What You'll Learn
- Model Tuning — why it matters
- Cross-Validation — testing models the right way
- Hyperparameter Tuning — Grid Search CV, Randomized Search CV
- Ensemble Learning — Bagging, Boosting, Stacking
- Random Forest, AdaBoost, Gradient Boosting, XGBoost
- Unsupervised Learning — K-Means, DBSCAN
- Dimensionality Reduction — PCA + Curse of Dimensionality

### 🔬 Projects
- K-Means Clustering on real data
- DBSCAN — complex cluster shapes
- PCA visualizations

**Resources:**
- 🐙 [GitHub Code](https://github.com/AkarshVyas/Machine_learning_part4)

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific-013243?logo=numpy)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4c72b0)

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/machine-learning-basecamp.git
cd machine-learning-basecamp
pip install -r requirements.txt
```

Open any notebook in Jupyter or Google Colab and follow along with the series.

---

## 👨‍💻 Instructor

**Akarsh Vyas** — Building this series to make Machine Learning practical and accessible for everyone.

> 💡 *Suggestion: Create your own structured notes as you go through each part. Writing concepts in your own words is the fastest way to truly understand them.*

---

## ⭐ Support

If this repo helped you, give it a star — it means a lot and helps others find it too!
