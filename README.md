# Customer Churn Prediction Model

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction
Customer churn prediction is a crucial aspect for businesses to retain customers and improve profitability. This project aims to build a machine learning model to predict customer churn based on various features such as customer demographics, account information, and service usage patterns.

## Dataset
The dataset used in this project contains information on customer demographics, account details, and their service usage patterns. The dataset includes the following features:
- `customerID`: Unique identifier for the customer
- `gender`: Gender of the customer
- `SeniorCitizen`: Whether the customer is a senior citizen (1: Yes, 0: No)
- `Partner`: Whether the customer has a partner (Yes, No)
- `Dependents`: Whether the customer has dependents (Yes, No)
- `tenure`: Number of months the customer has stayed with the company
- `PhoneService`: Whether the customer has a phone service (Yes, No)
- `MultipleLines`: Whether the customer has multiple lines (Yes, No, No phone service)
- `InternetService`: Customer’s internet service provider (DSL, Fiber optic, No)
- `OnlineSecurity`: Whether the customer has online security (Yes, No, No internet service)
- `OnlineBackup`: Whether the customer has online backup (Yes, No, No internet service)
- `DeviceProtection`: Whether the customer has device protection (Yes, No, No internet service)
- `TechSupport`: Whether the customer has tech support (Yes, No, No internet service)
- `StreamingTV`: Whether the customer has streaming TV (Yes, No, No internet service)
- `StreamingMovies`: Whether the customer has streaming movies (Yes, No, No internet service)
- `Contract`: The contract term of the customer (Month-to-month, One year, Two year)
- `PaperlessBilling`: Whether the customer has paperless billing (Yes, No)
- `PaymentMethod`: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- `MonthlyCharges`: The amount charged to the customer monthly
- `TotalCharges`: The total amount charged to the customer
- `Churn`: Whether the customer churned (Yes or No)

## Features
- **Exploratory Data Analysis (EDA)**: Understanding the data, handling missing values, and visualizing relationships.
- **Data Preprocessing**: Encoding categorical features, scaling numerical features, and splitting the data into training and testing sets.
- **Model Building**: Using machine learning algorithms like Logistic Regression, Decision Trees, Random Forest, and XGBoost to build the churn prediction model.
- **Model Evaluation**: Evaluating the models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/collowhiz/customer-churn-prediction.git
   cd customer-churn-prediction
