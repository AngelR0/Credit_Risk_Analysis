# Credit Risk Analysis
## Description
---
This application is a credit risk analysis by predicting either the loan is or not risky, depending the creditworthiness of the borrower.

  * Inside the given data:
    * Loan Size
    * Interest Rate
    * Borrower Income
    * Debt to Income Ratio
    * Total Debt
    * Number of Accounts
    * Derogatory Marks
    * Loan Status

  * The model is uses Logistic Regression to determine the analysis from the potential borrower. After this step we will use a prediction function so in the future we can see which loan will be risky.

  * As said above we will use the Logistic Regression, and RandomOverSampler functions to resample data sets for the machine learning algorithm.
## Results
---
These are the results show the predicted risky loans:
* Logistic Regression (Non-Resampled Data):
  * **Precision:** 85%
  * **Recall:** 91%
  * **F1:** 88%
* Logistic Regression (Resampled Data):
  * **Precision:** 84%
  * **Recall:** 99%
  * **F1:** 91%

## Summary
---
From running the application we can see that the resampled data perform much better, and in the long run we can be confident on the futures prediction.

