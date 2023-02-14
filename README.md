# Lending Club Case Study 


## Table of Contents
* Problem Statement
* Technologies
* Recommendations

## Problem Statement
  We work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the  company makes a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
  1) If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
  2) If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead 
      to a financial loss for the company


## Technologies 
- Numpy
- Pandas
- Matplotlib.pyplot
- Seaborn


## Recommendations

Likely repay the loan when :
- Loan amount to income proportion is less than 20%.
- The applicants who are given the loans of grade A.
- The loans are given to the less experience applicants.
- The loans are given for the purpose of car, credit card or wedding.

Likely default the loan when :
- Loan amount to income proportion is more than 20%.
- The applicants who are given the loans with grade F and G.
- The experience is more.
- The loans are given for the purpose of small business.
