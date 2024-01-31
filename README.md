# credit-risk-classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis is to see if the model can correctly identify healthy and high risk loans.
The data is based on loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks and total debt.
The dataset contained 75,036 healthy loans and 2,500 high risk loans.
The analysis consisted of using the Logistic Regression model.


## Results

* Logistic Regression Model (original data):
  * Balanced Accuracy - 95%
  * Precision for healthy loans - 100%
  * Precision for high risk loans - 85%
  * Recall for healthy loans - 99%
  * Recall for high risk loans - 91%


## Summary

The results show that the model is fairly accurate. It identifies healthy loans with 100% precision and 99% recall. However, it is much worse at correctly identifying high risk loans, with 85% precision and 91% recall.

I would not recommend using the model as it does not do a good enough job predicting high risk loans and that is more important than predicting healthy loans.