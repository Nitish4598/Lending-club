# Lending-club
In this assignment we will get an idea about how real business problems are solved. We will develop a basic understanding of risk analytics in banking and financial services and understand how we need to minimise the risk of losing money while lending to customers.

Business Understanding: We work for a consumer finance company which specialises in lending various types of loans to urban customers. Here when the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 

Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.

If the applicant is not likely to repay the loan, then approving the loan may lead to a financial loss for the company.

The given dataset contains information about past loan applicants whether they are ‘defaulted’ or not. The aim is to identify the patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan etc.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan,then there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan.

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'. 

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. the applicant has defaulted on loan

Loan rejected:The company checks with the above mentioned senarios and decide. If the candidate comes under 3rd category then candidate will be rejected for loan as the candidate does not meet their requirements.

If one is can identify risky loan applicants,such loans can be reduced by cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the reason behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for risk assessment.
