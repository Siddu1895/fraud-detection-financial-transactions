# fraud-detection-financial-transactions

##Project Title

Financial Fraud Detection using Machine Learning

##Overview

This project builds a machine learning system to detect fraudulent financial transactions using the Synthetic Financial Datasets For Fraud Detection dataset.

The dataset simulates real-world mobile money transactions, allowing analysis of fraud patterns and development of predictive models.

##Problem Statement

Financial fraud is rare but highly impactful. The objective of this project is to identify fraudulent transactions from highly imbalanced data using machine learning techniques.

##Key Features

Performed exploratory data analysis to identify fraud patterns

Engineered features such as balance inconsistencies

Handled extreme class imbalance using SMOTE

Trained models including Random Forest and XGBoost

Evaluated performance using recall, precision, and ROC-AUC

##Key Insights

Fraud mainly occurs in TRANSFER and CASH_OUT transactions

Fraud transactions show balance inconsistencies

Fraudsters often empty accounts rapidly

##Tech Stack

Python

SQL

pandas

scikit-learn

Seaborn

##Model Performance

High recall achieved for fraud detection

Balanced precision-recall tradeoff

Robust performance on imbalanced dataset

##Future Improvements

Real-time fraud detection pipeline

Deployment using API

Graph-based fraud detection

##requirements.txt

pandas

numpy

matplotlib

seaborn

scikit-learn
imbalanced-learn
jupyter
