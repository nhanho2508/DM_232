# Rossman Store Sales Prediction

This project focuses on predicting the sales of Rossman stores using various data analysis and machine learning techniques. The dataset includes historical sales data, store information, and other relevant features.

## Project Overview

The primary objective of this project is to build a predictive model that can accurately forecast store sales. The main steps involved in the project are:

1. **Data Loading and Exploration**
2. **Data Preprocessing**
3. **Feature Engineering**
4. **Model Training and Evaluation**
5. **Model Tuning and Selection**

## Methodology

### 1. Data Loading and Exploration

- Imported necessary libraries for data manipulation, visualization, and modeling.
- Loaded the sales and store datasets.
- Explored the datasets to understand their structure, features, and missing values.

### 2. Data Preprocessing

- Handled missing values using appropriate strategies such as filling with median values.
- Performed feature scaling using StandardScaler and MinMaxScaler.
- Encoded categorical variables using category encoders.

### 3. Feature Engineering

- Created new features based on existing data to improve model performance.
- Analyzed the variance inflation factor (VIF) to check for multicollinearity.

### 4. Model Training and Evaluation

- Split the data into training and testing sets.
- Trained multiple regression models including Linear Regression, Ridge, Lasso, ElasticNet, Decision Tree Regressor, Random Forest Regressor, KNeighbors Regressor, and XGBoost.
- Evaluated model performance using metrics like R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE).

### 5. Model Tuning and Selection

- Used GridSearchCV and RandomizedSearchCV for hyperparameter tuning.
- Built a neural network model using Keras and evaluated its performance.
- Selected the best performing model based on evaluation metrics.




