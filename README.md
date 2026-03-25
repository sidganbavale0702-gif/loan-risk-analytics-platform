Credit Risk Analytics: From Risk Scoring to Decision System

🔹 Project Overview
   This project implements an end-to-end credit risk analytics system, evolving from a traditional risk analysis dashboard to a financial decision-making system.

   Version 1 focused on risk segmentation and KPI analysis, while Version 2 extends it into predictive modeling, financial risk estimation, and loan decision support.

   The goal is to transform raw banking data into actionable insights for credit risk management.

🔹 Business Objective
    To build a data-driven credit risk system that enables financial institutions to:

  - Identify high-risk customers
  - Predict loan default probability
  - Quantify financial exposure
  - Improve loan approval and portfolio risk decisions

🔴 RISK ANALYTICS SYSTEM
🔹 Key Business Insights
  - Identified high-risk customer segments
  - Analyzed payment behavior leading to default
  - Quantified portfolio credit exposure
  - Built early-warning risk indicators

🔹 Skills Demonstrated
    SQL:
  - Advanced queries
  - CTEs
  - Window functions
  - Data modeling (Star Schema)

  Python:
  - Data engineering
  - Feature engineering
  - Risk score modeling

  Tableau:
  - KPI dashboards
  - Executive reporting

🔹 Data Engineering
    Raw Tables:
  - application_train
  - previous_application
  - bureau
  - installments_payments

  Staging Tables:
  - stg_application_train
  - stg_previous_application
  - stg_bureau
  - stg_installments_payments

  Star Schema:
  - Dimension Tables: dim_customer, dim_contract
  - Fact Tables: fact_application_train, fact_previous_application

🔹 Risk Scoring Model
   A composite risk score was engineered using behavioral and financial features:

  Risk Score =
  0.4 × Default History +
  0.3 × Payment Delay +
  0.2 × Credit Exposure +
  0.1 × Credit Burden

🔹 KPIs Built
  - Total Customers
  - Default Rate %
  - Payment Delay Metrics
  - Late Payment Frequency
  - Credit Exposure
  - Active Credit Burden


🔹 Output
  Generated dataset:
  customer_risk_dataset.csv

  Used for Tableau dashboards

🔴 CREDIT RISK DECISION SYSTEM

🔹 Objective
  Extend risk analysis into a decision-making system by:

  - Predicting default probability (PD)
  - Estimating financial loss
  - Enabling loan approval decisions

🔹 Machine Learning
  Model: Logistic Regression

  Purpose:
  - Predict Probability of Default (PD)

🔹 Financial Modeling
  PD  = Probability of Default
  LGD = Loss Given Default (assumed 50%)
  EAD = Exposure at Default

  Expected Loss = PD × LGD × EAD

🔹 Decision Framework
  Customers are segmented into:

  - Approve → Low Risk
  - Review → Medium Risk
  - Reject → High Risk

🔹 Key Results
  - Total Portfolio Risk ≈ ₹25M+
  - Only ~14% customers eligible for approval
  - Majority of losses driven by high-risk segment
  - Review group represents largest population

🔹 Dashboard Outputs
🔹 Version 1 Dashboard
  Risk category distribution
  Default rate analysis
  High-risk customer identification
  
🔹 Version 2 Dashboard (Final)
  Loan decision distribution
  Portfolio risk (Expected Loss)
  Financial impact by segment
  Decision-driven insights

🔹 Tech Stack
    SQL | Python | Pandas | NumPy | Scikit-learn | Tableau | MySQL

🔹 Project Workflow
  SQL Data Extraction →
  Data Cleaning (Python) →
  Feature Engineering →
  Risk Scoring →
  Machine Learning →
  Financial Modeling →
  Dashboard Visualization

🔹 Project Outcome
Developed a production-style credit risk analytics system that evolved into a financial decision-making tool, enabling data-driven lending strategies and portfolio risk optimization.

