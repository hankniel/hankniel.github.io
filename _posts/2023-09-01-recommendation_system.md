---
layout: post
title:  "Anime Recommendation System"
info: "Personal Project"
tech: "Python"
badges: 
  - "https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"
  - "https://img.shields.io/badge/PySpark-FCC624?style=for-the-badge&logo=apachespark&logoColor=#E35A16"
  - "https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"
type: Personal
permalink: /projects/recommendation_system
---

## Summary

This Jupyter notebook develops a collaborative filtering recommender system using the Alternating Least Squares (ALS) algorithm implemented in PySpark. The project focuses on recommending anime to users based on their historical ratings. It leverages a comprehensive dataset from Kaggle that includes user ratings for various anime. The goal is to enhance user engagement by suggesting animes that are likely to be of interest, leveraging recommender system technology that has become essential in many online services like Netflix and Amazon.

The notebook is structured into several key sections:

- **Context and Data Source**: Introduction to the importance of recommender systems and specifics about the dataset used.
- **Collaborative Filtering**: Explanation and implementation of the ALS algorithm for making recommendations.
- **Data Preparation**: Importing and cleaning data to ensure it is suitable for the model, including checks for missing values and correct data formats.
- **Model Implementation**: Building and tuning the ALS model using Spark.
- **Evaluation**: Assessing the performance of the model using appropriate metrics.

![Project Image](/images/recommendation.png)

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](/notebooks/Recommendation%20System.html)

## Techniques

The analysis employs various data processing and machine learning techniques:

- **Data Import and Cleaning**: Data is imported using PySpark, and initial checks for cleanliness are performed, ensuring no missing values and correct data types.
- **Exploratory Data Analysis (EDA)**: Before building the model, the data's structure is analyzed, including checks for sparsity which is typical in recommendation system datasets.
- **Collaborative Filtering with ALS**: Utilizing the ALS algorithm from Spark MLlib to predict user preferences based on past interactions.
- **Model Evaluation**: Using regression metrics to evaluate the accuracy of the recommendations provided by the model.

This project is implemented using Python and PySpark, showcasing the use of big data technologies for scalable machine learning applications.
