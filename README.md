# Customer Churn Prediction

A machine learning project that predicts whether a telecom customer is likely to churn based on customer demographics, services, contract details, and billing information.

## 🚀 Live Demo

[Try the Customer Churn Prediction App](https://customer-churn-prediction-debagnik.streamlit.app/)

## 📌 Project Overview

Customer churn is an important business problem for subscription-based companies. The goal of this project is to analyze customer data and build machine learning models that can identify customers who are likely to leave.

This project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, model evaluation, model explainability, and deployment through a Streamlit web application.

## 🎯 Problem Statement

The objective is to predict whether a customer will churn based on factors such as:

* Customer demographics
* Tenure
* Contract type
* Internet and phone services
* Payment method
* Monthly charges
* Total charges
* Other subscribed services

The prediction can help businesses identify customers who may be at higher risk of leaving and support data-driven customer retention strategies.

## 📊 Dataset

This project uses the **Telco Customer Churn** dataset.

The dataset contains information about:

* Customer demographics
* Account information
* Services
* Contract details
* Billing information
* Churn status

The dataset contains 7,043 customer records and 21 columns in its original form.

### Dataset Source

The original dataset can be accessed here:

[📊 Telco Customer Churn Dataset — Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)

The dataset file used in this project is:

`WA_Fn-UseC_-Telco-Customer-Churn.csv`

The target variable is:

* `Churn = Yes` → Customer churned
* `Churn = No` → Customer did not churn

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Joblib
* SHAP
* Streamlit
* Jupyter Notebook
* Git & GitHub

## 🤖 Machine Learning Models

The project uses three classification models:

### Logistic Regression

A linear classification model used as a baseline model for predicting customer churn.

### Random Forest

An ensemble learning model that combines multiple decision trees for classification.

### XGBoost

A gradient boosting algorithm used to build a classification model for churn prediction.

## 📈 Model Evaluation

The models are evaluated using classification metrics including:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix

Recall is particularly important in churn prediction because identifying customers who are actually likely to churn can help businesses take preventive action.

## 🔎 Model Explainability

SHAP is used for model explainability to understand which features contribute to model predictions.

This helps connect machine learning predictions with understandable business insights.

## 🖥️ Streamlit Application

The project includes an interactive Streamlit application that allows users to enter customer information and obtain a churn prediction.

### 🚀 Live Demo

[Open the Customer Churn Prediction App](https://customer-churn-prediction-debagnik.streamlit.app/)

## 📁 Project Structure

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
```

## ⚙️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/debagnikdey0804-bot/customer-churn-prediction.git
```

### 2. Navigate to the project directory

```bash
cd customer-churn-prediction
```

### 3. Install the required dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
streamlit run app.py
```

The application will then open in your browser.

## 🔄 Project Workflow

```text
Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Preparation
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Explainability
      ↓
Model Saving
      ↓
Streamlit Application
      ↓
Deployment on Streamlit Community Cloud
```

## 🎯 Project Goal

The goal of this project is to combine data analysis, machine learning, and deployment to build a practical customer churn prediction solution that can support data-driven customer retention strategies.
