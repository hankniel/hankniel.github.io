---
layout: post
title:  "VPBank Technology Hackathon 2024"
info: "VPBank Hackathon"
tech: "Python"
badges: 
  - "https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"
  - "https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"
type: Work
permalink: /portfolio/vpbank_technology_hackathon
---

## Summary

Imagine receiving irrelevant marketing messages from your bank, offering services that don't resonate with your lifestyle. This project aims to break out of generic marketing methods by providing personalized experiences for VPBank customers.

Developed during the VPBank Technology Hackathon 2024, the Customer Lifetime Value Optimization project focuses on automating data processing and enhancing marketing strategies. By leveraging AWS services, the project integrates customer data collection, machine learning models, personalized product recommendations, sentiment analysis, and omnichannel marketing optimization.

### Key Objectives:
1. **Streamline Data Ingestion**: Design an ETL pipeline to integrate data from all VPBank sources.
2. **Empower Personalized Recommendations**: Develop algorithms to learn customer preferences and recommend suitable products.
3. **Optimize Omnichannel Marketing**: Implement a feedback loop to refine algorithms for the best engagement channels and times.
4. **Understand Customer Concerns**: Use sentiment analysis on feedback data to identify barriers to customer satisfaction.

### Project Phases:
1. **Data Collection and ETL Pipeline Development**: Customer data is collected and integrated using AWS services like S3, RDS, and Lambda. This includes extracting, transforming, and loading data into a centralized storage system.
2. **Machine Learning Models for Customer Segmentation and CLV Prediction**: Models developed in SageMaker segment customers based on behavior and predict Customer Lifetime Value (CLV), helping understand different customer segments.
3. **Personalized Product Recommendations**: Algorithms recommend products based on customer characteristics, integrating results into the client interface using a resilient API.
4. **Sentiment Analysis and Customer Feedback**: AWS Comprehend performs sentiment analysis on feedback from various channels to understand and improve customer experience.
5. **Omnichannel Marketing Optimization**: AWS Kinesis processes real-time data, while Amazon Pinpoint manages targeted marketing campaigns across multiple channels.
6. **Data Visualization and Insights**: AWS QuickSight creates dashboards to monitor customer interactions and campaign performance, optimizing marketing efforts.

<img src="/images/vpbank_hackathon.png" alt="Project Image" style="width: 100%; max-width: 1200px;">

## Techniques

The core of this project involves:

- **Data Collection and ETL Pipeline Development**: Utilizing AWS CloudFormation, S3, RDS, and Lambda to automate the extraction, transformation, and loading of customer data.
- **Machine Learning Models**: Implementing models in SageMaker for customer segmentation, CLV prediction, and personalized product recommendations.
- **API Integration**: Utilizing AWS Lambda and Bedrock to generate and deliver personalized email content.
- **Sentiment Analysis**: Employing AWS Comprehend for analyzing customer feedback to improve customer engagement strategies.
- **Omnichannel Optimization**: Using AWS Kinesis for real-time data processing and Amazon Pinpoint for multi-channel marketing campaigns.
- **Data Visualization**: Leveraging AWS QuickSight to create dashboards for monitoring and optimizing marketing efforts.

## Role and Responsibilities

As the lead developer, my responsibilities included:

- Designing and implementing the ETL pipeline using various AWS services.
- Developing and testing machine learning models in SageMaker for effective customer segmentation and product recommendations.
- Creating APIs with AWS Lambda and Bedrock for generating personalized marketing content.
- Integrating sentiment analysis using AWS Comprehend to derive actionable insights from customer feedback.
- Utilizing AWS Kinesis and Pinpoint to optimize omnichannel marketing strategies.
- Creating and managing data visualization dashboards with AWS QuickSight to monitor campaign performance.

## Outcome

The project successfully automated the customer data processing pipeline and deployed machine learning models for enhanced personalized marketing strategies. As a result, our team was recognized as a finalist in the VPBank Technology Hackathon 2024 competition.

Through this project, I gained extensive experience in integrating various AWS services to build a scalable and efficient customer lifetime value optimization system.
