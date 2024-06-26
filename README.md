# Credit_Card_Default_Prediction

## Project Overview

This project aims to predict whether a customer will default on their credit card payment in the next billing cycle using supervised classification models. The performance of the models will be evaluated using the Area Under the Receiver Operating Characteristic Curve (AUC-ROC).

## Background

Credit card defaulting poses a significant risk to financial institutions, leading to considerable financial losses. Predicting defaults helps banks and financial institutions manage credit risk more effectively and make informed decisions regarding credit issuance and debt recovery strategies.

## Objective

Develop a supervised classification model to predict the likelihood of a customer defaulting on their credit card payment. The model's performance will be primarily evaluated using the AUC-ROC metric.

## Data Description

[DataSet.xls](https://github.com/user-attachments/files/15986659/DataSet.xls)

The dataset contains historical information on customers' credit card usage and payment behavior. Key attributes include:

• X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.

• X2: Gender (1 = male; 2 = female). • X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).

• X4: Marital status (1 = married; 2 = single; 3 = others).

• X5: Age (year).

• X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . .

• X 11= the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.

• X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.

• X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.

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
