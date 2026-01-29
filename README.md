# loan-risk-analytics-platform

🚀 End-to-End Loan Risk Analytics & Credit Scoring Platform

Tech Stack: SQL • Python • Tableau • MySQL • Pandas • NumPy

📌 Project Summary

This project implements a complete end-to-end financial analytics system for loan default risk analysis and credit scoring, covering:

Data Warehousing (Star Schema design)

SQL-based ETL & KPI Engineering

Python-based Analytics Engineering & Risk Modeling

Tableau Executive Dashboards

The goal is to transform raw banking data into actionable business intelligence and predictive risk insights.

🎯 Business Objective

To build a data-driven credit risk assessment system that enables banks to:

Identify high-risk customers

Predict loan default probability

Monitor credit exposure

Improve loan approval and portfolio risk decisions

🏗 Data Architecture
Raw Tables

raw_application_train

raw_previous_application

raw_bureau

raw_installments_payments

Staging Tables

stg_application_train

stg_previous_application

stg_bureau

stg_installments_payments

Star Schema Model

Dimension Tables:

dim_customer

dim_contract

Fact Tables:

fact_application_train

fact_previous_application

🛠 SQL Work (ETL + KPI Engineering)

Concepts Used:

CTEs

Window Functions

Star Schema Modeling

Aggregations

Business KPI Engineering

Key KPIs Built:

Default Rate %

Payment Delay Metrics

Late Payment Frequency

Credit Exposure

Active Credit Burden

🐍 Python Analytics Engineering
Libraries Used

pandas

numpy

sqlalchemy

mysql-connector-python

matplotlib

seaborn

Work Performed

MySQL → Python data pipeline

Feature engineering

Risk scoring model

Dataset preparation for Tableau

📊 Credit Risk Scoring Model

A composite risk score was engineered using multiple behavioral and financial features.

Risk Score Formula
Risk Score =
0.4 × Default History
+ 0.3 × Payment Delay
+ 0.2 × Credit Exposure
+ 0.1 × Credit Burden

Risk Categories
Risk Score	Category
≤ 30	Low Risk
30 – 60	Medium Risk
> 60	High Risk
📁 Final Analytics Dataset

Generated using Python:

customer_risk_dataset.csv


Contains:

Customer ID

Default Flag

Payment Delay

Overdue Amount

Active Credits

Risk Score

Risk Category

Used directly in Tableau dashboards.

📈 Tableau Dashboard (In Progress)

KPIs Visualized:

Total Customers

Default Rate

Risk Category Distribution

High-Risk Customer Segmentation

Credit Exposure Monitoring

🧠 Key Business Insights

Identified high-risk customer segments

Analyzed payment behavior leading to default

Quantified portfolio credit exposure

Built early-warning risk indicators

🎯 Skills Demonstrated

SQL: Advanced queries, CTEs, window functions, data modeling

Python: Data engineering, feature engineering, analytics modeling

Tableau: KPI dashboards, executive reporting

Finance Domain: Credit risk & loan portfolio analytics

🏆 Project Outcome

Built a production-grade financial analytics pipeline delivering predictive risk insights and executive dashboards for loan portfolio management.
