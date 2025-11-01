# GA-White-Box-Supervised-ML-Project

## Part 1: Video Game Sales 
## Part 2: Credit Score Classification  
-----------------------------------------------------------------------------------------------------
#Part 1:
# Video Game Sales 

----------------------------------------------------------------------------------------

## Proplem Statment:
Predict which video games will be successful in the global market using regression models to support better development and marketing decisions.

-----------------------------------------------------------------------------------------

## Dataset

Source: [Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)


-------------------------------------------------------------------------------------------------

## Data Cleaning

- Filled missing values (Year, Publisher).

- Converted data types (Year: object → int).

- Renamed regional sales columns.

- Checked for outliers and duplicates.

- Excluding Years after 2016 from the EDA and Modeling

----------------------------------------------------------------------------------------------------

## EDA

- Sales trends by year, genre, and region.

- Top publishers and platforms.

- Correlation between regional and global sales.


--------------------------------------------------------------------------------------------------

## Modeling

Two regression models were tested and compared:

### 1. Linear Regression

Version 1: Year only (baseline).

Version 2: Added all regional sales.



### 2. K-Nearest Neighbors (KNN) Regressor

Version 1: Year + North America Sales (k=5).

Version 2: Year + all regional sale columns with tuned pipeline (scaling + GridSearchCV).






----------------------------------------------------------------------------------------

# Part 2:

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
- Plotted Correlation Heatmap.

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
