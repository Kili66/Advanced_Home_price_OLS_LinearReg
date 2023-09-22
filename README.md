# Advanced_Home_price_OLS_LinearReg
* Advanced Methods for Home Price Prediction with all Pipelines
### The main aim of this project is to predict the house price based on various features 

#### Dataset to downloaded from the below link
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

## EDA:
* In Data Analysis we Analyzed the data to find out:
1. Missing Values
2. All The Numerical Variables
3. Distribution and visualization of the Numerical Variables
4. Visualize Categorical Variables and find the relationship betweeen the independant variable
5. Cardinality of Categorical Variables
6. Outliers
7. Relationship between independent and dependent feature(SalePrice)

## Feature Engineering
1. Imputation of missing values
2. Temporal variables
3. remove rare labels
4. Features scaling

## Features Selection
1. I used Lasso and SelectFromModel of sklearn and consider a alpha paramter as 0.005
## Model Building
1. Linear regression, model score is: 0.89
2. OLS: Ordinary Least Squares: 0.92

## Evaluation Metrics
1. The model performance for testing set
--------------------------------------
* MAE is 0.09414065471162783
* MSE is 0.0177655070285663
* R2 score is 0.8921299463175346

