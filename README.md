### Task 1: Linear Regression for Housing Prices

## Overview
This repository contains Python code for predicting house prices using linear regression. The dataset used includes various features such as living area, number of bedrooms, bathrooms, and total rooms.

## Code Highlights
- Data exploration and visualization using Seaborn and Matplotlib.
- Log transformation of the target variable (`SalePrice`) for better model performance.
- Testing feature normality using the Shapiro-Wilk test.
- Training a linear regression model on the original and log-transformed data.
- Evaluation of the model using Mean Squared Error, Root Mean Squared Error, and R2-squared.
- Visualization of model predictions compared to actual prices.

## Results
The linear regression model shows reasonable predictive performance. Predicted sale prices are transformed back from the logarithmic scale for interpretability.
