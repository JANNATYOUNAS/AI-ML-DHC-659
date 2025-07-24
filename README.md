# AI-ML-DHC-659


This repository contains completed tasks for the AI/ML Engineering Internship at DevelopersHub Corporation.

---

# Task 1: Exploring and Visualizing the Iris Dataset

**Objective**
Explore the Iris flower dataset to understand data distributions and relationships between features.
**Dataset Used**
  Iris Dataset (Kaggle)
**Skills Applied**
Data exploration using `pandas`
Summary statistics (`.describe()`, `.info()`)
Visualization using `matplotlib` and `seaborn`
**Visuals Created**
 Scatter plots to compare features
 Histograms to show distribution
Box plots to identify outliers
Pair plots to reveal class separability
 **Key Insights**
 Petal length and width are strong indicators of species
 Setosa is well-separated from other species

---

# Task 2: Stock Price Prediction (Short-Term)

**Objective**
Predict the next day's stock closing price using historical data.

**Dataset Used**
 Stock data fetched via `yfinance` (Apple – AAPL)
**Features:** Open, High, Low, Volume
**Target:** Close price
**Model Used**
 Linear Regression
 **Visuals Created**
 Actual vs. Predicted price line plot
**Key Insights**
 Simple linear regression gives a baseline estimation of next-day prices
 Real data fluctuations show room for more advanced models (e.g., LSTM, XGBoost)

---

# Task 3: Heart Disease Prediction

**Objective**
Build a classification model to predict heart disease risk based on health features.
 **Dataset Used**
  UCI Heart Disease Dataset (Kaggle)
**Target Column:** `num` (converted to binary target: 0 = No disease, 1 = Disease)
**Model Used**
 Logistic Regression
   StandardScaler used for feature scaling
   SimpleImputer used to handle missing values
   Categorical encoding using `factorize()`
**Visuals Created**
 Correlation heatmap
 Confusion matrix
 ROC curve with AUC
 Feature importance plot
**Key Results**
 **Accuracy:** ~85%
**Important features:** `cp`, `thalach`, `ca`, `oldpeak`

---


