Key steps in the modeling workflow:

Data Preprocessing: Handle missing values, encode categorical variables using pd.get_dummies, and scale numeric features.

Modeling: Apply Linear Regression, Ridge, and Lasso on the preprocessed dataset.

Evaluation: Calculate MSE and RMSE on a validation set. Predictions can be transformed back to the original SalePrice scale using exponentiation.

Submission: Generate Kaggle-ready predictions for the test dataset.

Features / Highlights

Fully dummy-encoded categorical variables for model compatibility

Scaled numeric features for linear models

Log-transform of target (SalePrice) to stabilize variance

Ridge and Lasso regression for regularization and better generalization

Validation metrics in both log-space and original dollar scale
