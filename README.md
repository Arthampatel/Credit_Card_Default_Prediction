# Credit_Card_Default_Prediction

## Project Overview

This project aims to predict whether a customer will default on their credit card payment in the next billing cycle using supervised classification models. The performance of the models will be evaluated using the Area Under the Receiver Operating Characteristic Curve (AUC-ROC).

## Background

Credit card defaulting poses a significant risk to financial institutions, leading to considerable financial losses. Predicting defaults helps banks and financial institutions manage credit risk more effectively and make informed decisions regarding credit issuance and debt recovery strategies.

## Objective

Develop a supervised classification model to predict the likelihood of a customer defaulting on their credit card payment. The model's performance will be primarily evaluated using the AUC-ROC metric.

## Data Description

The dataset contains historical information on customers' credit card usage and payment behavior. Key attributes include:

- **Customer ID:** Unique identifier for each customer
- **Credit Limit:** Maximum credit limit for the customer
- **Balance:** Outstanding balance on the credit card
- **Payment History:** Record of payments made by the customer
- **Transactions:** Details of purchases and cash advances
- **Delinquencies:** Record of overdue payments and their durations
- **Income:** Customer's annual income
- **Age:** Age of the customer
- **Employment Status:** Employment information of the customer
- **Other Relevant Demographic and Financial Variables**

The target variable is:
- **Default:** 1 if the customer defaulted on the payment, 0 otherwise.

## Problem Scope

1. **Data Preprocessing:** Clean and preprocess the data, handle missing values, outliers, and perform feature engineering.
2. **Exploratory Data Analysis (EDA):** Understand the distribution of variables and identify potential predictors.
3. **Feature Selection:** Select relevant features for predicting credit card defaults.
4. **Model Development:** Develop and compare various supervised classification models (e.g., Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, Neural Networks).
5. **Model Evaluation:** Evaluate the models using AUC-ROC and other metrics like Precision, Recall, F1-Score, and Confusion Matrix.
6. **Hyperparameter Tuning:** Optimize model hyperparameters for improved performance.
7. **Model Deployment:** Prepare the final model for deployment to handle real-time data.

## Expected Outcome

A robust predictive model that accurately identifies customers at risk of defaulting on their credit card payments. The model will provide actionable insights for financial institutions to improve credit risk management, reduce default rates, and enhance profitability.

## Repository Structure

- `data/`: Contains the dataset and any data preprocessing scripts
- `notebooks/`: Jupyter notebooks for data exploration, analysis, and model development
- `src/`: Source code for data processing, feature engineering, and model building
- `models/`: Saved models and related files
- `results/`: Evaluation results and model performance metrics
- `README.md`: Project overview and documentation

## Getting Started
https://colab.research.google.com/drive/1SVBwxc1IMnKhj1rRLm78eOs1k7YAniiX?usp=sharing

## Conclusion
By leveraging machine learning techniques and historical credit card usage data, this project aims to deliver a reliable solution for predicting credit card defaults. This will enable financial institutions to make informed decisions, minimize credit risk, and optimize their credit issuance strategies.
