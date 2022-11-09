## **Problem Statement And Business Case**
- As an investor, it is important to invest in people who have a high probability of paying you back.
- Using the past data ML model can be made to check which borrower is more likely to default on payment.

### **Objective:** To develop a model that could predict whether the borrower will pay back the loan or not

### **Data Description:**

### 

| **Field Name**               | **Description**                                                         |  
|------------------------------|-------------------------------------------------------------------------|  
| credit.policy                |  If the customer meets the credit underwriting criteria or not   |  
| purpose                      | The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other")|  
| int.rate                     | The interest rate of the loan|  
| log.annual.inc               | The natural log of the self-reported annual income of the borrower|  
| dti                          | The number of days the borrower has had a credit line|  
| days.with.cr.line            | The number of days the borrower has had a credit line|  
| revol.bal                    | The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).|  
| revol.util                   | The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available)            |  
| inq.last.6mths               | The borrower's number of inquiries by creditors in the last 6 months|   
| delinq.2yrs                  | The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments)|  
| pub.rec                      | The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments)|  
| not.fully.paid               | Whether borrower paid the loan back or not|  

###
**Tasks performed:**

1.  Importing necessary libraries
2.  Data Exploration
3.  Data Modeling
    - Without balancing the data
      - Train and evaluate Random Forest Classifier
    - Balancing the dataset using SMOTE
      - Train and evaluate Random Forest Classifier
      - Train and evaluate XGBoost Classifier
      - Train and evaluate AdaBoost Classifier
      - ROC Curve
4.  Comparison of various models
