## Credit Risk Analysis Report

## Overview of the Analysis
The purpose of this analysis was to build a machine learning model to predict the creditworthiness of loan applicants, assess the results, and determine the model’s ability to predict healthy and high-risk loans. The dataset provided was financial lending data comprised of the size of the loan, interest rate, borrower’s income, debt to income ratio, number of accounts, derogatory remarks, and the loan status (healthy or high-risk loan). After reading in the CSV and creating an initial data frame, the machine learning steps that I applied were first, separating the data into labels and features by determining the dependent variable as the loan status, and the independent variable as the rest of the dataset. Once the independent and dependent variables were established, I then split the data into training and testing datasets using Scikit learn. After completing that step, I created a logistic regression model to classify the data and initiate the loan status predictions. Following the generation of predictions, I assessed their efficiency by using a confusion matrix and classification report.
## Results
Healthy Loan Predictions:
•	Accuracy:  A score of 99% indicates that the model is very accurate.
•	Precision: A score of 100% indicates a very strong ratio of correctly predicted positive observations and a low false positive rate.
•	Recall: A score of 99% also indicates a very strong ratio of correctly predicted positive observations and a low false negative rate.
High Risk Loan Predictions:
•	Accuracy: A score of 99% indicates that the model is very accurate.
•	Precision: A score of 85% indicates a strong ratio of correctly predicted positive observations and a low false positive rate.
•	Recall: A score of 91% also indicates a strong ratio of correctly predicted positive observations and a low false negative rate.
## Summary
Based on the results, this model can predict loan risk very well. As expected, the healthy loans were predicted more accurately than high risk loans, however the difference was marginal. The high-risk class having a precision of 85% and recall of 91% is still very promising and doesn’t dissuade confidence in the model’s ability to predict loans that will likely default. Given these impressive results for both classes, I highly recommend this model to be used by the company for future loan applications.
