This project focuses on predicting loan default and estimating loss amount using LendingClub data. It includes two main tasks:

Probability of Default (PD): A classification task to predict whether a loan will default or not. We use logistic regression and apply techniques like oversampling, feature encoding, and threshold tuning to improve performance. Metrics such as ROC-AUC, F1 score, and confusion matrix are used for evaluation.

Loss Prediction for Defaulted Loans: A regression task to estimate the loss amount when a default happens. We apply models like Gamma regression, LightGBM, and XGBoost. The model is evaluated using RMSE, MAE, and R². We also check residual plots and error distribution to understand model behavior.

The project includes data cleaning, feature engineering, model evaluation, and interpretation. The goal is to support credit risk analysis and help build better lending decisions.
