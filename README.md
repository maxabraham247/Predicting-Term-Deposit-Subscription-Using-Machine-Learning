# Predicting-Term-Deposit-Subscription-Using-Machine-Learning
📊 Bank Marketing Campaign – Machine Learning Capstone (Module 3)
📌 Project Overview

This project is part of Capstone Project Module 3, focusing on applying machine learning classification to solve a real-world business problem in bank marketing.

The objective is to predict whether a customer will subscribe to a term deposit based on demographic, financial, and campaign-related information, enabling banks to optimize marketing efficiency and reduce operational costs.

🎯 Business Problem

Banks conduct marketing campaigns to promote term deposit products. However, contacting all customers leads to:

High marketing costs

Low conversion rates

Inefficient campaign strategies

❓ Problem Statement

How can banks identify customers who are most likely to subscribe to a term deposit so that marketing campaigns can be more targeted and cost-effective?

👥 Stakeholders

Bank Marketing Team

Business & Campaign Managers

📁 Dataset

Source: Bank Marketing Campaign dataset

Rows: 7,813 customers

Target Variable: deposit (Yes / No)

Features include:

Customer demographics (age, job)

Financial status (balance, loans)

Campaign details (contact method, month, previous outcomes)

🧠 Analytical Approach

Problem Type: Binary Classification

Models Implemented:

Logistic Regression

Random Forest Classifier

🧹 Data Cleaning & Feature Engineering

Removed duplicate records

Numerical features imputed using median values

Categorical features encoded using One-Hot Encoding

Feature scaling applied for Logistic Regression

Pipelines and ColumnTransformers used for clean and reproducible preprocessing

📈 Evaluation Metrics

Models were evaluated using:

Accuracy

Precision

Recall

F1-score

🔑 Metric Focus

Recall was prioritized due to business importance:

Missing a potential subscriber results in lost revenue

False positives are less costly than false negatives

🏆 Model Performance Summary
Model	Accuracy	Recall (Subscribed)
Logistic Regression	~70%	84%
Random Forest	~71%	77%
✅ Final Model Selected

Logistic Regression

Reasons:

Higher recall for subscribed customers

Better interpretability

Lower business risk

🔍 Post-Modeling Analysis

Confusion matrix analysis to assess prediction errors

Feature importance analysis using Logistic Regression coefficients

Identification of key drivers influencing customer subscription

False negative analysis to identify missed opportunities

💡 Business Impact

Improved campaign targeting

Reduced marketing costs

Increased conversion rates

Data-driven marketing decision-making

⚠️ Limitations

Dataset size is limited

Lack of customer income and digital behavior data

Model performance may degrade if customer behavior changes over time

🚀 Recommendations & Future Improvements

Adjust prediction thresholds based on business priorities

Retrain the model periodically with new data

Add more customer behavioral features

Test advanced models such as Gradient Boosting

Use SHAP values for deeper model interpretability

Integrate the model into a CRM system for real-time decision support

📂 Repository Structure
📁 bank-marketing-capstone
│── capstone_module3_bank_marketing.ipynb
│── Bank_Marketing_Capstone_Presentation_With_Charts.pptx
│── README.md

🛠️ Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

👤 Author

Max Abraham
Machine Learning
