# Module 12 Report
# Author: Matthew Adent

## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of a machine learning model (logistic regression) in predicting credit risk. The goal of the model was to classify loans as either `0` (healthy loan) or `1` (high-risk loan) using financial data.

### Really Cool Facts About the Data That May Knock Your Socks Off
- The dataset contained financial information regarding loan applications.
- The target variable was binary, with `0` representing a healthy loan and `1` representing a high-risk loan.
- The `value_counts` for the target variable indicated class imbalance, with significantly more healthy loans than high-risk loans.

### Machine Learning Process
The steps for building and using the machine learning model were:
1. **Data Preparation** – Data was cleaned and split into training and testing sets.
2. **Model Selection** – Logistic Regression was used for classification.
3. **Model Training** – The model was trained on the training dataset.
4. **Model Evaluation** – Performance was evaluated using accuracy, precision, recall, and an F1-score.
5. **Victory Dance** - Obligatory.

## Results

### Machine Learning Model: Logistic Regression
- **Accuracy**: `99%`
- **Precision & Recall Scores**:
    - **Class `0` (Healthy Loans):**
        - Precision: `1.00`
        - Recall: `0.99`
        - F1-Score: `1.00`
    - **Class `1` (High-Risk Loans):**
        - Precision: `0.85`
        - Recall: `0.95`
        - F1-Score: `0.89`

## Summary

The logistic regression model performed exceptionally well, achieving a high overall accuracy of `99%`. It demonstrated near-perfect precision (`1.00`) and recall (`0.99`) for class `0`, which shows strong performance in predicting healthy loans. For class `1` (high-risk loans), the recall was strong (`0.95`), meaning most actual high-risk loans were correctly identified. That being said, it was slightly lower in every statistic, and precision was quite a bit lower (`0.85`).

### Recommendation
Despite my praise, I have to say that this logistic regression model is not suitable for predicting credit risk. 5% mispredictions isn't an insignificant amount across hundreds of thousands of people, and given that loans are typically large sums of money, 5% could be millions of dollars. I would have to recommend trying other models, such as Random Forest, KNN, or XGBoost.
