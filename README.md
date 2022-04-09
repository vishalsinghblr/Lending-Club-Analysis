# Lending-Club-Analysis
Exploratory Data Analysis (EDA) performed for a consumer finance company to understand the If the applicant is likely to repay the loan or not.

**Business Understanding**__
A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
Two types of risks are associated with the bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

![image](https://user-images.githubusercontent.com/87148352/162561442-569af68e-bbb0-47e0-90d5-9f169a25fc1d.png)

When a person applies for a loan, there are two types of decisions that could be taken by the company:

_Loan accepted_: If the company approves the loan, there are 3 possible scenarios described below:

_Fully paid_: Applicant has fully paid the loan (the principal and the interest rate)

_Current_: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

_Charged-off_: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan.

_Loan rejected_: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


**Business Objective**__
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.
