# Real Estate Prediction in Python

## Project Overview
This project demonstrates an end-to-end machine learning workflow for predicting California housing prices using Python. It covers the complete data science pipeline, including data loading, exploratory data analysis, preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation.

## Features
- Loaded and explored the California Housing dataset using Pandas  
- Visualized feature distributions and correlations using Matplotlib and Seaborn  
- Handled missing values and transformed skewed numerical features  
- Applied one-hot encoding to categorical features such as `ocean_proximity`  
- Created new engineered features to improve predictive performance  
- Split data into training and testing sets for model validation  
- Built and evaluated a **Linear Regression** baseline model  
- Trained a **Random Forest Regressor** for improved accuracy  
- Performed **GridSearchCV** for hyperparameter tuning  

## Dataset
The project uses the California Housing dataset, which includes:

- Longitude and Latitude  
- Median House Age  
- Total Rooms  
- Total Bedrooms  
- Population  
- Households  
- Median Income  
- Ocean Proximity  

**Target Variable:** `median_house_value`

This is a supervised regression problem where the objective is to predict house prices based on housing and location features.

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

## Results
- **Linear Regression:** ~66.8% accuracy  
- **Random Forest Regressor:** ~81.3% accuracy  
- **Tuned Random Forest:** ~81.4% accuracy  

The Random Forest model significantly outperformed Linear Regression, showing the benefit of non-linear ensemble methods for this dataset.
