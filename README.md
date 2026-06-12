# Loan Default Prediction

## Overview
Built a Logistic Regression model to predict loan default risk using borrower demographic, financial, and loan-related data.

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Feature Engineering
Created additional risk indicators including:
- LoanToIncomeRatio
- DebtExposure
- InterestBurden
- InterestToIncome
- IncomePerCreditLine
- CreditAdjustedLoan

## Results
- ROC-AUC Score: **0.761**
- Improved model performance through feature engineering.

## Key Risk Factors
- LoanToIncomeRatio
- InterestRate
- NumCreditLines
- EmploymentType_Unemployed
- DTIRatio

## Key Protective Factors
- Age
- MonthsEmployed
- HasCoSigner
- HasDependents
- EmploymentType_Full-time

## Conclusion
The model successfully identified important drivers of loan default risk and demonstrated good discrimination ability with a ROC-AUC score of 0.761.
