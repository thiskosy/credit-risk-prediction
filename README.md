# Credit Risk Prediction — Logistic Regression Model

## Overview
Analyzed 32,581 loan records to predict the probability of loan default 
using exploratory data analysis and logistic regression modeling.

## Business Problem
Which borrowers are most likely to default and how can a bank 
automate credit decisions to minimize losses?

## Key Findings
- Loan Grade is the strongest predictor — Grade G defaults at 98.4%
- Debt consolidation loans carry the highest default risk (28.6%)
- Low income borrowers (under $30k) default at 45.5%
- loan_percent_income (0.38) is the strongest numeric predictor

## Model Performance
- Accuracy: 84%
- ROC-AUC: 0.853
- Threshold optimization saved $3.95M in potential losses

## Risk Tier System
- LOW RISK — Auto Approve (75% of customers)
- MEDIUM RISK — Manual Review (15%)
- HIGH RISK — Auto Reject (9%)

## Tools
Python · Pandas · Scikit-learn · Logistic Regression · Seaborn · Matplotlib

## Files
- Credit_Risk_Prediction.ipynb — full analysis and model
- Credit Risk Prediction.pdf — professional project report

## Author
Kosi Nweke · github.com/thiskosy · kosinweke.e@gmail.com
