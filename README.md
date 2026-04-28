# 🤖 AI/ML Internship Tasks - Data Science Projects

## 👨‍💻 Overview
This repository contains 3 Machine Learning tasks completed
as part of my AI/ML Internship program.

---

## 📁 Task 1: Exploring and Visualizing Iris Dataset

### 📌 Objective
Explore and visualize the Iris dataset to understand
data trends, distributions and feature relationships.

### 📦 Dataset
- **Name:** Iris Dataset
- **Source:** Seaborn built-in library
- **Rows:** 150 | **Columns:** 5
- **Target:** Species (Setosa, Versicolor, Virginica)

### 🤖 Models Applied
- No model (Exploratory Data Analysis only)

### 🔍 Key Findings
- Setosa is clearly separable from other species
- Petal length & width are strongly correlated
- Virginica has the largest feature values overall

---

## 📁 Task 2: Stock Price Prediction (Apple - AAPL)

### 📌 Objective
Predict the next day's closing stock price using
historical market data and regression models.

### 📦 Dataset
- **Source:** Yahoo Finance via yfinance library
- **Stock:** Apple Inc. (AAPL)
- **Period:** 2020 - 2024
- **Features:** Open, High, Low, Volume
- **Target:** Next Day Close Price

### 🤖 Models Applied
- Linear Regression
- Random Forest Regressor

### 🔍 Key Findings
- Random Forest outperformed Linear Regression
- Open & High prices were strongest predictors
- Model successfully captures short-term price trends

---

## 📁 Task 3: Heart Disease Prediction

### 📌 Objective
Predict whether a person is at risk of heart disease
based on health data using classification models.

### 📦 Dataset
- **Name:** Heart Disease UCI Dataset
- **Source:** Kaggle
- **Features:** Age, Sex, Chest Pain, Blood Pressure,
  Cholesterol, Max Heart Rate etc.
- **Target:** 0 = No Disease | 1 = Disease

### 🤖 Models Applied
- Logistic Regression
- Decision Tree Classifier

### 🔍 Key Findings
- Logistic Regression achieved higher ROC-AUC score
- Chest pain type & max heart rate were top predictors
- ROC curve confirmed strong classification performance

---

## 🛠️ Libraries Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, yfinance

## 📊 Skills Demonstrated
- Data Loading, Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Regression & Classification Modeling
- Model Evaluation (MAE, R², Accuracy, ROC-AUC)
- Data Visualization & Feature Importance Analysis
