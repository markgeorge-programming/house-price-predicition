# Project Description

This project focuses on predicting house prices using the Kaggle dataset “House Prices – Advanced Regression Techniques”. The goal is to build robust regression models that can accurately estimate sale prices from housing features.

# Key steps in the modeling workflow:

- Data Preprocessing: Handle missing values, encode categorical variables using pd.get_dummies, and scale numeric features.

- Modeling: Apply Linear Regression, Ridge, and Lasso on the preprocessed dataset.

- Evaluation: Calculate MSE and RMSE on a validation set. Predictions can be transformed back to the original SalePrice scale using exponentiation.

- Submission: Generate Kaggle-ready predictions for the test dataset.

# Features / Highlights

- Fully dummy-encoded categorical variables for model compatibility

- Scaled numeric features for linear models

- Log-transform of target (SalePrice) to stabilize variance

- Ridge and Lasso regression for regularization and better generalization

## Validation metrics in both log-space and original dollar scale

# Evaluation

- Model performance is measured using MSE/RMSE.

- Log-transformed target allows models to handle skewed SalePrice distribution.

- Ridge/Lasso regularization reduces overfitting, especially with high-dimensional dummy-encoded features.


Hyperparameter tuning for Ridge/Lasso (alpha optimization)

Try tree-based models (RandomForest, XGBoost) for better accuracy

Feature engineering for improved predictions
