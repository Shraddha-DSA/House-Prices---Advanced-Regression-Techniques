# House-Prices---Advanced-Regression-Techniques
# 🏡 House Prices Prediction – Kaggle Regression Challenge

This repository contains my solution to the [Kaggle House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/) competition. The goal is to predict the final price of each home in the test set using a range of regression techniques.

---

- **Problem**: Predict housing prices using tabular data (79 features)
- **Target**: SalePrice (log-transformed)
---
Model: Random Forest Regressor
Target: Log-transformed SalePrice
Evaluation Metric: RMSE (on log scale)
Preprocessing:

Dropped columns with excessive missing values (e.g., Alley, PoolQC, MiscFeature, etc.)

Categorical features label-encoded

Missing values filled with "missing" for categorical and 0 for numerical

Used same preprocessing for train and test sets

Log RMSE (CV): ~0.1527
