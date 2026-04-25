# Credit_score_system 
#base on credit score loan approval system
# Loan Approval Prediction

This project predicts whether a loan application will be approved or rejected based on applicant financial and personal data using machine learning.

## Dataset

The dataset `loan_approval_data.csv` contains 1000 records with 20 features including:

- Financial: Applicant Income, Co-applicant Income, Credit Score, DTI Ratio, Savings, Collateral Value, Existing Loans
- Personal: Age, Dependents, Marital Status, Gender, Education Level
- Loan Details: Loan Amount, Loan Term, Loan Purpose
- Employment: Employment Status, Employer Category
- Other: Property Area

## Results

 Model- Accuracy-Precision-Recall-F1 Score
Logistic Regression-87.5% -0.79 -0.80- 0.80 
Naive Bayes - 86.5% - 0.80 - 0.74 - 0.77 
KNN (k=5)- 74.0% -0.60 -0.46 -0.52

#Best Model: Logistic Regression

## Key Findings

- Credit Score has the strongest positive correlation with loan approval
- DTI Ratio has a strong negative correlation
- Higher income alone does not guarantee approval
- Feature engineering (adding squared terms for Credit Score and DTI Ratio) improved model performance

## Installation

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
