# Pattern Recognition - Income Classification Project

This repository contains our Pattern Recognition team project for predicting whether a person's annual income exceeds $50K using demographic and work-related attributes.

## Project Overview

The task is a binary classification problem.  
The dataset includes numerical and categorical variables such as age, education, occupation, working hours, capital gain/loss, marital status, and native country.

## My Contribution

- Data exploration
- Data preprocessing
- Feature engineering
- Threshold optimization
- Report drafting

## Models Used

- Logistic Regression
- Random Forest
- XGBoost

Among the tested models, XGBoost showed the most balanced performance and was selected as the final model.

## Main Techniques

- Missing value imputation
- Label encoding
- Standard scaling
- Feature engineering
- Hyperparameter tuning with Optuna
- Threshold optimization

## Final Result

After hyperparameter tuning and threshold optimization, the final model achieved a CV score of 0.8299.
