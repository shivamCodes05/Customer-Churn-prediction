# Customer-Churn-prediction
Project Analysis: Customer Churn Prediction

Project Overview

This project is a comprehensive Machine Learning pipeline designed to predict customer churn in the telecommunications sector. It utilizes the Telco Customer Churn dataset to identify at-risk customers, allowing businesses to proactively intervene.

The workflow spans the full data science lifecycle:

Exploratory Data Analysis (EDA): Deep dive into customer demographics and behaviors using Seaborn and Matplotlib to uncover patterns in tenure, charges, and contract types. Data Preprocessing: Robust handling of data integrity including Label Encoding for categorical variables and SMOTE (Synthetic Minority Oversampling Technique) to resolve class imbalance issues. Model Selection & Training: Comparative analysis of Decision Tree, Random Forest, and XGBoost classifiers, validated using 5-fold Cross-Validation to ensure generalizability. Random Forest was selected as the champion model. Deployment Readiness: The final model and data encoders are serialized using Pickle, enabling a modular Predictive System that accepts raw input data and outputs real-time churn probabilities.
