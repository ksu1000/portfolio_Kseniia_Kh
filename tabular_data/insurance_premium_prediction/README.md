# Insurance Premium Prediction

## Overview
This project was developed as part of the Kaggle competition ["Playground Series - Season 4, Episode 12"](https://www.kaggle.com/competitions/playground-series-s4e12/overview). The goal is to predict insurance premiums based on customer attributes, including income, health score, and other numerical and categorical features. This challenge requires building a robust regression model that minimizes the Root Mean Squared Logarithmic Error (RMSLE).

## Highlights
- **Model**: LGBMRegressor (LightGBM)
- **Optimization**: Hyperparameter tuning with Optuna
- **Performance**: Ranked 196 out of 895 participants at the time of submission.
- **Focus Areas**: Tabular data handling, feature engineering, and model evaluation.

## Dataset
The dataset includes:
- **Numerical Features**: Income, health score, age, etc.
- **Categorical Features**: Region, occupation, etc.
- **Target**: Insurance premium amount (log-transformed).

For details, refer to the [Kaggle competition page](https://www.kaggle.com/competitions/playground-series-s4e12/overview).

## Key Steps
### 1. Data Preprocessing
- Handled missing values and categorical encoding.
- Applied log transformation to the target variable for improved model performance.

### 2. Hyperparameter Tuning
- Used Optuna for efficient search of optimal parameters for LightGBM.
- Limited trials due to computational constraints but achieved stable results.

### 3. Model Evaluation
- RMSLE was used as the primary evaluation metric.
- Final results demonstrated minimal overfitting and strong generalization.

### 4. Submission
- Predictions were submitted to Kaggle, achieving a competitive rank of 196 out of 895.

## Results
- **Train RMSLE**: 1.038
- **Validation RMSLE**: 1.047
- **Leaderboard Position**: 196/895
