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
