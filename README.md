# Credit Risk Classification
### Author: Matthew Adent

This project aims to classify loan applications as either **healthy loans (0)** or **high-risk loans (1)** using machine learning (logistic regression). The goal is to develop an accurate predictive model that can assist with determining the financial risk of a loan based on some features of the borrower.

## Project Structure
```
CREDIT-RISK-CLASSIFICATION/
│── Resources/
│   ├── lending_data.csv          # Dataset used for training and evaluation
│── .gitignore                    # Files to be ignored by Git
│── credit_risk_classification.ipynb  # Jupyter Notebook with ML implementation
│── LICENSE                        # License information, I happened to choose the MIT one
│── README.md                      # This file
│── report.md                       # Project report with model results
```

Pretty cool, right?

## Dataset
The dataset (`lending_data.csv`) has financial data on loan applications.

- **Target Variable:**  
  - `0` → Healthy Loan  
  - `1` → High-Risk Loan  

- **Features:**  
  - Loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt, loan status.
