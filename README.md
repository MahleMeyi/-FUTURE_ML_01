# FUTURE_ML_01
# Sales Forecasting ML Project

## Overview
This project focuses on predicting future sales using historical e-commerce data. 
A machine learning model is built to identify patterns, trends, and dependencies in sales over time.

## Features
- Data cleaning and preprocessing  
- Time-based feature engineering (year, month, day, weekday)  
- Lag features to capture past sales behavior  
- Rolling averages to identify trends  
- Machine learning model for forecasting  
- Visualization of actual vs predicted sales

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib

## Model Approach
The dataset was transformed into a time-series format by aggregating daily sales.  
Additional features such as lag values and rolling averages were introduced to improve prediction accuracy.  
A Random Forest Regression model was then trained to forecast future sales.

## Results
The model was able to capture general sales trends and provide reasonable forecasts.  
Evaluation was performed using Mean Absolute Error (MAE).

## Sales Forecast Visualization
<img width="1510" height="694" alt="Screenshot 2026-04-20 234456" src="https://github.com/user-attachments/assets/73c21104-f044-4b39-b684-0ab0c4f2c75d" />
