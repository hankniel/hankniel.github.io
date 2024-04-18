---
layout: post
title:  "RFM Segmentation & Churn Prediction"
info: "Personal Project"
tech: "Python"
badges: 
  - "https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"
  - "https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"
type: Personal
permalink: /portfolio/rfm_segmentation_and_churn_prediction
---

## Summary

This project involves a comprehensive analysis of transactional data from Pizza Hut Vietnam, spanning from 2021 to 2023. The data includes transaction date, sales amount, customer ID, customer gender, voucher status, and province. The goal of the project is to gain insights into customer behavior, identify sales trends, segment customers, predict churn rate and evaluate the effectiveness of various sales channels and strategies.

The project is divided into five main parts:

1. **Import Data, EDA and RFM Segmentation**: The data is imported, cleaned, and explored. The exploration includes checking for missing values, duplicates, and outliers. The data is then segmented using RFM (Recency, Frequency, Monetary) analysis.

2. **Churn and CLV Predict**: Models are built to predict customer churn and Customer Lifetime Value (CLV). These models help understand which customers are likely to churn and the potential value of each customer to the business.

3. **Final Model for CLV and Churn Probability**: The models from the previous step are finalized and applied to different customer segments.

4. **Additional Insights**: Additional insights are derived from the data, such as the retention rate and the number of new customers per month.

5. **Recommendations**: Based on the analysis, recommendations are made to improve business performance.

![Project Image](/images/rfm_cover.png)

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](/notebooks/rfm_segmentation_and_churn_prediction.html)

## Techniques

The analysis uses various data analysis and machine learning techniques:

- **Data Cleaning**: The data is cleaned by handling missing values and outliers. For example, negative sales amounts are corrected.

- **Exploratory Data Analysis (EDA)**: The data is explored using descriptive statistics and visualizations to understand the distribution of variables and the relationships between them.

- **RFM Segmentation**: RFM (Recency, Frequency, Monetary) segmentation is used to segment customers based on their transaction history.

- **Predictive Modeling**: BG/NBD - Gamma-Gamma Model and XGBoost Regressor are used to predict customer churn and Customer Lifetime Value (CLV).

- **Model Evaluation**: The models are evaluated using metrics such as mean absolute error, mean squared error, and ROC AUC score.

- **Grid Search**: Grid search is used to optimize the hyperparameters of the models.

The analysis is implemented using Python, with libraries such as pandas for data manipulation, matplotlib and seaborn for visualization, and scikit-learn and XGBoost for machine learning.
