Fintech & Telecom Analytics Dataset Engineering

This repository contains a Python-based data engineering and analytics pipeline that integrates multiple fintech and telecommunications datasets into structured, analysis-ready datasets for customer retention, transaction analysis, fraud detection, customer support analytics, and network performance evaluation.

Source Datasets

The project uses the following raw datasets:

customer_support_tickets_200k.csv – Customer support ticket records.
Telecom_Network_Data.csv – Telecommunications network performance and operational metrics.
nibss_fraud_dataset.csv – Digital payment transactions and fraud records.
TelecomCustomerChurn.csv – Telecom customer demographics, subscription details, and churn information used for customer retention analysis.
Generated Datasets

The preprocessing pipeline combines and transforms the raw data into five analytics-ready datasets:

1. Customer Retention Dataset
Customer demographics
Subscription information
Churn indicators
Customer lifetime and engagement metrics
2. Transaction Dataset
Digital payment transactions
Transaction attributes
Financial activity summaries
Customer transaction history
3. Fraud Log Dataset
Fraud events
Fraud classifications
Risk indicators
Investigation records
4. Customer Support Dataset
Support tickets
Issue categories
Resolution status
Customer satisfaction and service metrics
5. Network Dataset
Telecom network performance
Signal quality
Network availability
Operational and service quality metrics
Technologies
Python
Pandas
NumPy
Jupyter Notebook
CSV Data Processing
Project Objective

The goal of this project is to demonstrate end-to-end data engineering by integrating heterogeneous fintech and telecommunications data sources into standardized datasets suitable for exploratory data analysis (EDA), business intelligence, machine learning, customer churn prediction, fraud detection, customer support analytics, and telecom network performance analysis.
