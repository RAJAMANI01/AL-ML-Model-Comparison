# AL-ML-Model-Comparison

# 🏠 House Price Prediction using Model Comparison

## 📌 Project Overview

This project focuses on predicting house prices using Machine Learning techniques and comparing multiple regression models to identify the best-performing algorithm.

The project uses the California Housing Dataset and follows an industry-standard Machine Learning workflow including data preprocessing, feature scaling, model training, evaluation, and visualization.

## 🎯 Objectives

- Load and explore the California Housing Dataset
- Perform data preprocessing
- Apply Feature Scaling using StandardScaler
- Train multiple regression models
- Compare model performance using RMSE and R² Score
- Select the best-performing model
- Visualize Actual vs Predicted House Prices

## 📊 Dataset Information

**Dataset:** California Housing Dataset

### Features

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity

### Target Variable

- Median House Value

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the California Housing Dataset
2. Handled missing values in `total_bedrooms`
3. Converted categorical feature `ocean_proximity` using One-Hot Encoding
4. Separated features and target variable
5. Applied StandardScaler for feature scaling

## 🤖 Machine Learning Models Used

### 1. Linear Regression
A baseline regression model used for predicting house prices.

### 2. Ridge Regression
A regularized version of Linear Regression that helps reduce overfitting.

### 3. Decision Tree Regressor
A non-linear model capable of capturing complex relationships within the data.

## 📈 Model Evaluation Metrics

The models were evaluated using:

### RMSE (Root Mean Squared Error)

Measures prediction error.

Lower RMSE indicates better performance.

### R² Score

Measures how well the model explains the variation in house prices.

Higher R² Score indicates better performance.


## 📉 Visualization

An Actual vs Predicted House Prices scatter plot was generated to visually evaluate model performance.

A closer alignment of points to the reference line indicates better prediction accuracy.

## 🎓 Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Feature scaling using StandardScaler
- Model comparison and evaluation
- Regression performance metrics
- Machine Learning workflow implementation
- Visualization of prediction results

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost implementation
- Model deployment using Streamlit

## 👨‍💻 Author

RAJAMANI S
