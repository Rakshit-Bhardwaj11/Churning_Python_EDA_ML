# Overview

This project focuses on predicting customer churn using Machine Learning. It covers the complete pipeline from data preprocessing and exploratory data analysis (EDA) to feature engineering, model building, and evaluation.

The goal is to identify customers who are likely to leave (churn) and help businesses take proactive actions.

#  Project Structure
├── Churning EDA.ipynb                 # Exploratory Data Analysis
├── Churn_prediction_model.ipynb      # Model building & evaluation
├── tel_churn.csv                      # Dataset (custom/processed)
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Original dataset

# Key Steps in the Project

### 1. Data Understanding
Dataset: Telco Customer Churn
Features include:
Customer demographics
Account informatio
Services subscribed
Billing details
### 2. Exploratory Data Analysis (EDA)
Distribution analysis of categorical & numerical features
Churn vs Non-Churn comparisons
Correlation analysis
Visualization using:
Count plots
Histograms
Heatmaps
### 3. Feature Engineering
Handling missing values
Encoding categorical variables
Feature scaling (if required)
Removing irrelevant features
Balancing dataset (if applied)
### 4. Model Building

The following machine learning models were implemented and compared:

- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression
- AdaBoost Classifier

### 5. Model Evaluation

Models were evaluated using:

Accuracy
Precision
Recall
F1-score
Confusion Matrix

Comparison helps in selecting the best-performing model for churn prediction.

# Insights
Certain customer behaviors strongly influence churn
Contract type, tenure, and monthly charges play significant roles
Ensemble models (like Random Forest & AdaBoost) tend to perform better

# Tech Stack
Python 🐍
Pandas & NumPy
Matplotlib & Seaborn
Scikit-learn
