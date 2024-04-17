---
layout: post
title:  "Fraud Detection"
info: "Personal Project"
tech: "Python"
badges: 
  - "https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"
  - "https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"
type: Personal
permalink: /projects/fraud_detection
---

## Summary

This Jupyter notebook is a comprehensive analysis of a dataset provided by Pizza Hut Vietnam. The dataset contains transactional data from 2021 to 2023, including details such as transaction date, sales amount, customer ID, customer gender, voucher status, and province. The analysis aims to provide insights into customer behavior, sales trends, and the effectiveness of various sales channels and strategies.

The notebook is structured into five main sections:

1. **Import Data, EDA and RFM Segmentation**: The data is imported, cleaned, and explored. The exploration includes checking for missing values, duplicates, and outliers. The data is then segmented using RFM (Recency, Frequency, Monetary) analysis.

2. **Churn and CLV Predict**: Models are built to predict customer churn and Customer Lifetime Value (CLV). These models help understand which customers are likely to churn and the potential value of each customer to the business.

3. **Final Model for CLV and Churn Probability**: The models from the previous step are finalized and applied to different customer segments.

4. **Additional Insights**: Additional insights are derived from the data, such as the retention rate and the number of new customers per month.

5. **Recommendations**: Based on the analysis, recommendations are made to improve business performance.

![Project Image](/images/fraud_detection.jpg)

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](/notebooks/Fraud%20Detection.html)

## Techniques

The analysis uses various data analysis and machine learning techniques:

- **Data Cleaning**: The data is cleaned by handling missing values and outliers. For example, negative sales amounts are corrected.

- **Exploratory Data Analysis (EDA)**: The data is explored using descriptive statistics and visualizations to understand the distribution of variables and the relationships between them.

- **RFM Segmentation**: RFM (Recency, Frequency, Monetary) segmentation is used to segment customers based on their transaction history.

- **Predictive Modeling**: Logistic Regression, Decision Tree Classifier, and XGBoost Regressor models are used to predict customer churn and Customer Lifetime Value (CLV).

- **Model Evaluation**: The models are evaluated using metrics such as mean absolute error, mean squared error, and ROC AUC score.

- **Grid Search**: Grid search is used to optimize the hyperparameters of the models.

The analysis is implemented using Python, with libraries such as pandas for data manipulation, matplotlib and seaborn for visualization, and scikit-learn and XGBoost for machine learning.
