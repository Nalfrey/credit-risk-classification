# credit-risk-classification
This analysis is reviewing the the loan risk for a set of data that includes the loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, total debt and the loan status.
Loan status is considered as value 0 = healthy loan, value 1 = high risk for default
This reads in the data from the CSV, then splits the data into training and testing sets. After that it creates a logistic regression model with the original data. 
# Module 20 Report Template

## Overview of the Analysis

In this section, I will describe the analysis I completed for the machine learning models used in this Challenge. This includes:

This analysis is reviewing the the loan risk for a set of data that includes the loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, total debt and the loan status.
Loan status is considered as value 0 = healthy loan, value 1 = high risk for default - This is what we are attempting to predict. 
This reads in the data from the CSV, then splits the data into training and testing sets. After that it creates a logistic regression model with the original data. Explain the purpose of the analysis.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
Given the results of the training and testing noted above the results were as listed below. The logistic regression model predicts in the 99% accuracy range.
with healthy loans it has an 84% accuracy, and with high risk loans it has an 89% accuracy. 
    precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? The evaluation of healthy loans is shown as more accurate than evaluating or determining a high risk loan.
* As this is a 99% accuracy, but high risk loans are near 84%

