# Invoice Payment Delay Prediction Using Machine Learning

## Project Overview

This project focuses on predicting invoice payment delays using Machine Learning classification techniques.

The main objective is to identify whether an invoice payment will be delayed or not based on invoice-related features.

## Dataset

The dataset contains invoice transaction details such as:

- Business information
- Invoice amount
- Currency
- Document type
- Payment terms

Total Records: 48,839

Target Variable:
- paid_late_flag

0 = On-time Payment  
1 = Late Payment

## Data Preprocessing

The following preprocessing steps were performed:

- Data cleaning
- Feature selection
- Removal of data leakage columns
- Numerical feature scaling using StandardScaler
- Categorical feature encoding using OneHotEncoder

## Machine Learning Models

Models used:

1. Logistic Regression
2. Random Forest Classifier

## Model Performance

| Model | Accuracy | F1 Score | ROC-AUC |
|---|---|---|---|
| Logistic Regression | 89.03% | 92.72% | 0.937 |
| Random Forest | 86.58% | 91.57% | 0.932 |

## Final Model

Logistic Regression was selected as the final model because it achieved better overall performance.

## Tools & Technologies

- Python
- Pandas
- Scikit-learn
- Google Colab
- Machine Learning
