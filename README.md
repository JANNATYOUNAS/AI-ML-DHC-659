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



#  Advanced Tasks

These advanced tasks demonstrate practical applications of **machine learning, deep learning, and large language models (LLMs)** across different domains. Each task is designed to strengthen skills in real-world scenarios such as support automation, multimodal learning, and production-ready pipelines.

---

### **Task 2: End-to-End ML Pipeline with Scikit-learn Pipeline API**

**Objective:**
Build a reusable and production-ready machine learning pipeline for predicting customer churn.

**Dataset:**
Telco Churn Dataset

**Instructions:**

* Implement preprocessing steps (scaling, encoding) using `Pipeline`
* Train models like Logistic Regression and Random Forest
* Use `GridSearchCV` for hyperparameter tuning
* Export the complete pipeline using `joblib`

**Skills Gained:**

* ML pipeline construction
* Hyperparameter tuning with GridSearch
* Model export and reusability
* Production-readiness practices

---

### **Task 3: Multimodal ML – Housing Price Prediction Using Images + Tabular Data**

**Objective:**
Predict housing prices using both structured data and house images.

**Dataset:**
Housing Sales Dataset + Custom/Public Image Dataset

**Instructions:**

* Use CNNs to extract features from images
* Combine extracted image features with tabular data
* Train a regression model on fused features
* Evaluate using **MAE** and **RMSE**

**Skills Gained:**

* Multimodal machine learning
* Convolutional Neural Networks (CNNs)
* Feature fusion (image + tabular)
* Regression modeling and evaluation

---

### **Task 5: Auto Tagging Support Tickets Using LLM**

**Objective:**
Automatically tag support tickets into categories using a large language model (LLM).

**Dataset:**
Free-text Support Ticket Dataset

**Instructions:**

* Use prompt engineering or fine-tuning with an LLM
* Compare zero-shot vs. fine-tuned performance
* Apply few-shot learning techniques for higher accuracy
* Output top 3 most probable tags per ticket

**Skills Gained:**

* Prompt engineering
* LLM-based text classification
* Zero-shot and few-shot learning
* Multi-class prediction and ranking

---


