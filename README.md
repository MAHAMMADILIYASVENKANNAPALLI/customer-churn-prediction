# Customer Churn Prediction

A machine learning project that predicts whether a customer is likely to churn based on customer demographics, services, contract information, tenure, and billing-related features.

## Project Overview

Customer churn is an important business problem for subscription-based companies. Identifying customers who are likely to leave can help businesses understand customer behavior and develop appropriate retention strategies.

In this project, customer data was explored, preprocessed, transformed, and used to train multiple classification models for predicting customer churn.

## Dataset

The dataset contains **7,043 customer records and 21 columns**.

The features include:

- Customer demographics
- Senior citizen status
- Partner and dependent information
- Tenure
- Phone and internet services
- Online security and backup services
- Device protection
- Technical support
- Streaming services
- Contract type
- Paperless billing
- Payment method
- Monthly charges
- Total charges

### Target Variable

`Churn`

The target contains two classes:

- `Yes` — Customer churned
- `No` — Customer did not churn

## Project Workflow

```text
Raw Customer Data
        ↓
Data Exploration
        ↓
Data Preprocessing
        ↓
Feature Selection
        ↓
Train/Test Split
        ↓
Categorical Feature Encoding
        ↓
Model Training
        ↓
Model Prediction
        ↓
Model Evaluation
