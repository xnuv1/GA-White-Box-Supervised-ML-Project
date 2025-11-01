# Credit Score Classification  

----------------------------------------------------------------------------------------

## Problem Statement:
Predict a customer’s credit score category (Good, Standard, or Poor) using machine learning classification models to help financial institutions make better lending and risk-assessment decisions.

----------------------------------------------------------------------------------------

## Dataset

Source: [Credit Score Classification Dataset](https://www.kaggle.com/datasets/parisrohan/credit-score-classification)

----------------------------------------------------------------------------------------

## Data Cleaning

- Removed duplicates and handled missing values.
- Converted text-based values into clean numeric data.
- Standardized and normalized key categorical columns.
- Trimmed outliers for numeric features such as Annual_Income, Outstanding_Debt, and Total_EMI_per_month.

----------------------------------------------------------------------------------------

## EDA

- Visualized the distribution of Credit Score categories.
- Visualized the Annual Income vs Credit Score.
-  Visualized the History Age Distribution
- Plotted Correlation Heatmap (Pearson) and Mutual Information Scores to identify top predictive features.

----------------------------------------------------------------------------------------

## Modeling

Two classification models were developed and compared:

### 1. Logistic Regression
- **Version 1:** Baseline with numeric features (Age, Outstanding_Debt, Num_of_Delayed_Payment, Credit_Utilization_Ratio).
- **Version 2:** Added income, payment behaviour, and credit history.

### 2. K-Nearest Neighbors (KNN) Classifier
- **Version 1:** Baseline numeric-only features.
- **Version 2:** Added engineered features, used StandardScaler, SMOTE, and GridSearchCV for tuning.

----------------------------------------------------------------------------------------
