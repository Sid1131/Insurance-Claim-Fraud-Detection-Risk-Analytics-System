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

###AGE DISTRIBUTION
<img width="882" height="592" alt="image" src="https://github.com/user-attachments/assets/f714ed58-7bf8-4054-b382-3998fbd1dd0e" />

###CLAIM AMOUNT DISTRIBUTION
<img width="937" height="571" alt="image" src="https://github.com/user-attachments/assets/a7bb6d64-6ed6-4547-8154-2d8ffb6b276d" />

###FRAUD VS CLAIM AMOUNT
<img width="877" height="556" alt="image" src="https://github.com/user-attachments/assets/a583707b-21af-44c5-9380-0c27e8643e14" />

###FRAUD VS INCIDENT SEVERITY
<img width="881" height="648" alt="image" src="https://github.com/user-attachments/assets/52de84a0-fecb-4dfa-97c7-c8c9cbce97b8" />

###FRAUD VS COLLISION TYPE
<img width="865" height="631" alt="image" src="https://github.com/user-attachments/assets/9fd47386-9391-40c0-a7a1-a5646332ce65" />

###VEHICLE AGE VS FRAUD REPORTED
<img width="832" height="565" alt="image" src="https://github.com/user-attachments/assets/486e5759-93fc-4017-a9d6-b2e906d49594" />

###FRAUD VS OCCUPATION
<img width="1227" height="671" alt="image" src="https://github.com/user-attachments/assets/c3878d8f-41cc-4cd2-a768-3c509bea2c45" />


## Key Insights

- Higher claim amounts were associated with increased fraud likelihood.
- Certain incident types showed higher fraud rates.
- Claims without authority involvement demonstrated elevated fraud risk.
- Vehicle age and policy duration influenced fraud probability.


## Model Development
Models Used:
1. Logistic Regression
2. Random Forest
3. XGBoost

 ## Model Performance
| Model | Accuracy |
|---------|---------|
| Logistic Regression | 74% |
| Random Forest | 78% |
| XGBoost | 81% |







