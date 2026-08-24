
# Customer Churn Prediction

A machine learning project to predict whether a customer is likely to churn using the **Telco Customer Churn (IBM) dataset**.

## Project Overview

Customer churn prediction helps businesses identify customers who are likely to leave their services. This project explores customer data, performs preprocessing and feature engineering, and compares multiple machine learning classification algorithms.

## Dataset

The project uses the **Telco Customer Churn (IBM)** dataset containing customer demographic, service, account, and billing information.

- Records: 7,043
- Features: 33

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

## Workflow

1. Data loading and exploration
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Handling missing values
5. Categorical feature encoding
6. Feature scaling
7. Stratified train-test split
8. Model training
9. Model comparison
10. Model evaluation
11. Saving the trained model using Joblib

## Machine Learning Models

The following classification algorithms were trained and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- XGBoost

## Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 80.13% |
| Random Forest | 79.49% |
| XGBoost | 78.28% |
| KNN | 76.37% |
| Decision Tree | 73.24% |

**Best Performing Model:** Logistic Regression

**Accuracy:** 80.13%

## Model Saving

The best-performing model and scaler were saved using **Joblib** for future predictions.

## Conclusion

Logistic Regression achieved the highest accuracy among the evaluated models and was selected as the best-performing model for this project.
