# ML-Classification-project - Lending club loan data analysis Simplilearn project

A class project practicing machine learning classification algorithms.

## DESCRIPTION

Create a model that predicts whether or not a loan will default using the historical data.

## Problem Statement:

For companies like Lending Club correctly predicting whether or not a loan will be a default is very important. In this project, using the historical data from 2007 to 2015, you have to build a machine learning model to predict the chance of default for future loans. As you will see later this dataset is highly imbalanced and includes a lot of features that make this problem more challenging.

Domain: Finance

## Dataset columns and definition:

credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.\n
purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").\n
int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.\n
installment: The monthly installments owed by the borrower if the loan is funded.\n
log.annual.inc: The natural log of the self-reported annual income of the borrower.
dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
fico: The FICO credit score of the borrower.
days.with.cr.line: The number of days the borrower has had a credit line.
revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

## Workflow 
1.	Data collection 
2.	Exploratory data analysis 
3.	Splitting data 
4.	Data scaling 
5.	Balancing the imbalanced dataset 
6.	Made predictions using some ML algorithms 
7.	Used cross-validation and hyperparameter tuning of the best-performing base model
   
### Results


| Machine learning Classifier      | Accuracy %         |
| ------------- | ---------------------|
| Logistic Regression      | 64 |
| Support vector machine     | 67  |
| Random forest | 80 |
| XGBoost classifier | 81 |
| XGBoost with cross validation  | 87 |
| XGBoost with hyper parameter tuning| 82|


### Findings 

Ensemble models performed better on the dataset 
