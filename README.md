# Insurance-Claim-Fraud-Detection-Risk-Analytics-System
## Overview

Insurance fraud results in significant financial losses for insurance companies.

This project develops a Machine Learning solution to identify fraudulent insurance claims using customer, policy, incident, and vehicle-related information.

The project includes:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning Models
- Power BI Dashboard
- Fraud Risk Insights
  
## Business Problem
Insurance companies process thousands of claims every year.
Manual fraud investigation is time-consuming and expensive.
The objective is to build a predictive model that can:
- Identify potentially fraudulent claims
- Reduce investigation effort
- Improve claim processing efficiency
- Support data-driven decision making

## Dataset
Rows: 1000
Columns: 40
Target Variable:
fraud_reported
Classes:
Y = Fraudulent Claim
N = Genuine Claim

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- SQL
- Power BI

## Data Cleaning
Performed:
- Replaced hidden missing values ('?')
- Handled null values
- Removed irrelevant features
- Converted date columns
- Created new analytical features


## Feature Engineering
Created:
1. Vehicle Age
2. Policy Duration
3. Claim-to-Premium Ratio
4. Customer Risk Indicators

These features improved model interpretability and fraud detection capability.

## Exploratory Data Analysis
### Fraud Distribution
<img width="911" height="557" alt="image" src="https://github.com/user-attachments/assets/a6da1bec-8e6e-432f-895e-2cd232922459" />
