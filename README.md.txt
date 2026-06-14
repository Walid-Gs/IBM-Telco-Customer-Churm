# 📞 IBM Telco Customer Churn Prediction

## Project Overview

Customer churn is one of the most important business challenges facing subscription-based companies.

This project develops Machine Learning and Deep Learning models capable of predicting customer churn and identifying the factors most strongly associated with customer attrition.

The goal is to help businesses proactively retain customers and reduce revenue loss.

---

# Business Problem

Acquiring new customers is significantly more expensive than retaining existing ones.

Telecommunication companies lose substantial revenue when customers leave their services.

This project aims to:

* Predict customer churn
* Identify churn drivers
* Improve customer retention strategies
* Support data-driven business decisions

---

# Dataset

IBM Telco Customer Churn Dataset

Features include:

* Customer Demographics
* Account Information
* Contract Details
* Internet Services
* Payment Methods
* Monthly Charges
* Total Charges

Target Variable:

* Churn Label

  * Yes
  * No

---

# Project Workflow

## 1. Business Understanding

Understanding the financial impact of customer churn and retention.

---

## 2. Data Cleaning

Performed:

* Missing Value Analysis
* Data Type Corrections
* Duplicate Checks
* Feature Validation

---

## 3. Exploratory Data Analysis

Analyzed:

* Churn Distribution
* Contract Type Effects
* Tenure Impact
* Monthly Charges
* Customer Segmentation

---

## Churn Distribution

<p align="center">
  <img src="images/class_distribution.PNG" width="800">
</p>

Key Finding:

Approximately 26% of customers churned, indicating moderate class imbalance.

---

## Contract Type Analysis

<p align="center">
  <img src="images/churn_by_contract.PNG" width="800">
</p>

Key Finding:

Month-to-month contracts showed significantly higher churn rates compared to long-term contracts.

---

## Tenure Analysis

<p align="center">
  <img src="images/churn_by_tenure.PNG" width="800">
</p>

Key Finding:

Customers with shorter tenure are substantially more likely to churn.

---

## Monthly Charges Analysis

<p align="center">
  <img src="images/churn_by_monthlycharge.PNG" width="800">
</p>

Key Finding:

Higher monthly charges are associated with increased churn risk.

---

# Feature Engineering

Applied:

* Label Encoding
* One-Hot Encoding
* Feature Scaling
* Train/Test Split

---

# Models Evaluated

### Logistic Regression

Strong baseline model with good interpretability.

---

### K-Nearest Neighbors

Distance-based classification approach.

---

### Support Vector Machine

Powerful classification model for complex decision boundaries.

---

### Tuned Support Vector Machine

Optimized through hyperparameter tuning.

---

### Decision Tree

Interpretable model with rule-based decision making.

---

### Random Forest

Ensemble approach reducing overfitting and improving generalization.

---

### Neural Network

Deep Learning architecture using TensorFlow/Keras.

Architecture:

* Dense Layers
* Dropout Regularization
* Binary Classification Output

<p align="center">
  <img src="images/nn_training.PNG" width="800">
</p>

---

# Model Evaluation

Metrics Used:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix


---

# Best Model Performance

<p align="center">
  <img src="images/best_model_evaluation.PNG" width="800">
</p>

---

# Key Findings

* Contract type is one of the strongest predictors of churn.
* Customers with month-to-month contracts are at highest risk.
* Short-tenure customers exhibit significantly higher churn rates.
* Higher monthly charges correlate with increased churn.
* Ensemble and Deep Learning models outperformed simpler algorithms.

---

# Business Recommendations

### Retention Programs

Target customers during their first months of service.

### Contract Incentives

Encourage migration from month-to-month contracts to annual plans.

### Pricing Strategy

Review pricing for high-risk customer segments.

### Early Warning System

Deploy churn prediction models to proactively identify at-risk customers.

---

# Skills Demonstrated

### Data Analysis

* EDA
* Statistical Analysis
* Data Cleaning

### Machine Learning

* Classification
* Model Evaluation
* Feature Engineering

### Deep Learning

* TensorFlow
* Keras
* Neural Networks

### Business Analytics

* Customer Retention Analysis
* Churn Prediction
* Decision Support

---

# Future Improvements

* XGBoost
* LightGBM
* SMOTE Balancing
* Hyperparameter Optimization
* Explainable AI (SHAP)
* Customer Risk Scoring System

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* TensorFlow
* Keras

---

# Author

Oualid GASMI

Data Analyst | Data Scientist | Machine Learning Enthusiast
