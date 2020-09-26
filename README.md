# Data Analysis and Predictive Model for any Bad Credit Behaviour in Credit Card Application Dataset 
We have done data analytic and built ML model which can help us in order to get an idea, whether a person will be doing any default activity
#### -- Project Status: [Active]

## Project Intro/Objective
The purpose of this project is helping the financial institution to know in advance for any bad credit behaviour in Credit Card Application
  
### Methods Used
* Exploratory Data Analysis and Vintage Analysis
* Feature Selection using Random Forrest and SelectKBest (f_classif)
* Predictive Modeling
* Evaluation Metrix

### Technologies
* Python
* Pandas
* numpy 
* matplotlib
* Seaborn
* sklearn

## Project Description
For most financial institutions, such as banks and multi-finance companies, their main source of income is coming from their lending activities. By engaging in this activity, it means that lenders are exposed to the potential risk, where debtors stop repaying their loans, causing losses to the lenders. To mitigate this loss, lenders are expected to appropriately choose who are qualified for a loan, at what rate, and at what amount.
In this project, we are tasked to help the troubled lenders with this problem by creating a model that can help them make their decision. 

Vintage analysis is a widely-used method for managing credit risk, it illustrate the behavior after an account was opened. Based on same origination period, it calculates charge-off ratio of a loan portfolio. 

Here comes our datasets, in which `credit_record.csv` contains loan accounts' credit records, the detailed data explanation is here:

|  credit_record.csv           | 　                        | 　                                                                                                                                                                                                                            |
|:-----------------------:|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Feature name          | Explanation               | Remarks                                                                                                                                                                                                                       |
| ID                    | Client number             | 　                                                                                                                                                                                                                            |
| MONTHS_BALANCE        | Record month              | The month of the extracted data is the starting point,  backwards, 0 is the current month, -1 is the previous month,  and so on                                                                                               |
| STATUS               | Status                    | 0: 1-29 days past due 1: 30-59 days past due   2: 60-89 days overdue 3: 90-119 days overdue    4: 120-149 days overdue 5: Overdue or bad debts, write-offs for more than 150 days    C: paid off that month X: No loan for the month  |



-----



while the `application_record.csv` contains appliers' features, such as gender, income. This notebook will show some necessary EDA on credit_record table.

## Important Concepts
Credit card and home loans are two very good examples of credit given to a borrower by a lender. Money in a credit card is not ours, We need to pay it back. If we fail to pay it, we need to repay with interest. Home loans are another type of credit given. For this, we have a collateral i.e, this could be used to recover money if the customers fails to pay back. Asset financing is another good example of credit. Organizations don't buy the assets at one go instead they finance it and pay it over the time. 