# Lending club case study 
> Lending club Project detail


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
By this case study we need to understand the real time problem scenario and how we can analyse the problem by the help of EDA .  By EDA analysis we need to minimize the risk in banking industry 
We work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

Data given contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

When a person applies for a loan, there are two types of decisions that could be taken by the company:
Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

##Inputs

Total provided inputs are in 39717 columns and 111 row .
Import directories 
Check for missing values 
Data cleaning by removing missing values.
After cleaning 39717 colums and 56 rows
Highlight the values required for analysis 



## Conclusions
- Analysis Based on Grades
- ![image](https://user-images.githubusercontent.com/84132394/201460527-f2a5711b-c4b5-4ab2-9b4f-2fe47183baee.png)
Defaulter can be mapped with the grade of loan as A is having least defaulters and G is highest. 
![image](https://user-images.githubusercontent.com/84132394/201460549-f2b26167-23e0-49e1-b5dc-eed1f7d84dd5.png)
##Defaulter can be mapped with the grade of loan as A is having least defaulters and G is highest. 


- Analysis Based on Tenure
![image](https://user-images.githubusercontent.com/84132394/201460596-6ca84f64-01be-44c7-8d2d-7c3b9e7a65ad.png)
Persons applying for more tenure are likely to default more 

- Analysis based on Intrest Rate 

![image](https://user-images.githubusercontent.com/84132394/201460617-315bdd9d-9616-4870-b5c5-3fd8e1202b5f.png)
Higher the intrest rate more risk of default 
![image](https://user-images.githubusercontent.com/84132394/201460622-393d24de-8222-480b-8c1f-04ab4b75490e.png)


- Analysis based on Income
- ![image](https://user-images.githubusercontent.com/84132394/201460638-f33c41a5-eb99-4822-acc4-e4c9d51bc9d4.png)
Less Annual income means more chances to default



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python
Numply directory
Pandas directory
Matplot
Seaborn






