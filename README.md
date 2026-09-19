# Customer Churn Prediction

A machine learning project that predicts whether a telecom customer is likely to churn based on customer demographics, services, contract details, and billing information.

## Project Overview

Customer churn is an important business problem for subscription-based companies. The goal of this project is to analyze customer data and build machine learning models that can identify customers who are likely to leave.

The project includes data preprocessing, exploratory analysis, machine learning model training, evaluation, and a Streamlit web application for making predictions.

## Dataset

The project uses the Telco Customer Churn dataset.

The dataset contains information about:
- Customer demographics
- Tenure
- Contract type
- Internet and phone services
- Payment methods
- Monthly charges
- Total charges
- Churn status

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Streamlit
- Jupyter Notebook

## Machine Learning Models

The project uses the following classification models:

- Logistic Regression
- Random Forest
- XGBoost

The models are evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Project Structure

```text
customer-churn-prediction/
│
├── app.py
├── churn-2.0-clean.ipynb
├── requirements.txt
├── logistic_model.pkl
├── rf_model.pkl
├── xgb_model.pkl
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
└── .gitignore