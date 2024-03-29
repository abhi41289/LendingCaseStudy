# Lending Case Study
> Solving this assignment will give you an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
    - Python
    - Numpy
    - Panda
    - SNS
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
    - Analysis done by Abhishek Raj P and Praharika Reddy 

<!-- You can include any other section that is pertinent to your problem -->

## General Information
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

    If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

    If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

 

The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

 

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion  : We need to categorize the people who are most likely to default on the loan amount
    
        - The above analysis with respect to the charged off loans. There is a more probability of defaulting when :
        - Applicants taking loan for 'home improvement' and have income of 60k -70k
        - Applicants whose home ownership is 'MORTGAGE and have income of 60-70k
        - Applicants who receive interest at the rate of 21-24% and have an income of 70k-80k
        - Applicants who have taken a loan in the range 30k - 35k and are charged interest rate of 15-17.5 %
        - Applicants who have taken a loan for small business and the loan amount is greater than 14k
        - Applicants whose home ownership is 'MORTGAGE and have loan of 14-16k
        - When grade is F and loan amount is between 15k-20k
        - When employment length is 10yrs and loan amount is 12k-14k
        - When the loan is verified and loan amount is above 16k
        - For grade G and interest rate above 20%


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- References if any
    - https://towardsdatascience.com/an-extensive-guide-to-exploratory-data-analysis-ddd99a03199e
    - https://www.geeksforgeeks.org/what-is-exploratory-data-analysis/



## Contact
Created by [@abhi41289] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->