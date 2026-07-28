# Life Expectancy Prediction using Linear Regression

## Overview
This project predicts life expectancy using demographic, economic, and health-related indicators from the WHO Life Expectancy dataset. A Linear Regression model was developed to estimate life expectancy based on multiple socio-economic and healthcare factors.

## Dataset
- Source: WHO Life Expectancy Dataset
- Records: 2,938
- Features: 21
- Target Variable: Life Expectancy

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Project Workflow
- Data preprocessing and exploration
- Missing value imputation
- Label encoding of categorical variables
- Feature scaling using StandardScaler
- Train-test split (80:20)
- Linear Regression model training
- Model evaluation
- Regression coefficient analysis
- Visualization of Actual vs Predicted values and Residuals

## Model Performance

| Metric | Value |
|--------|--------|
| R² Score | **0.8259** |
| MAE | **2.0403** |
| RMSE | **3.0044** |

## Results
- Achieved an R² score of **0.8259**, explaining approximately **82.6%** of the variance in life expectancy.
- Obtained a Mean Absolute Error of **2.04 years**, indicating accurate predictions.
- Identified the influence of demographic, economic, and healthcare indicators through regression coefficients.
