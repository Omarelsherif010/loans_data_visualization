# Prosper Loan Data Exploration (Data Analysis Easy Steps )
## by Omar Elsherif


## Dataset

This dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. But I choosed only the variables that make interest in our exploration and they are bout 20 variables.


## Summary of Findings

In the exploration, I found that there was a strong positive correlations between Lender yield and Borrower APR. Prosper Score and Prosper Rating are also positive correlation. Credit Score upper range has also some weak +ve correlation with prosper score.

Negative correlation between prosper score & APR, and prosper score & Lender yield. Negative correlation between prosper ratings & APR, and prosper score & Lender yield.
There was a negative relationship between loan original amount and borrower apr, means large loans have relatively less annual interest rate from the borrower. From the relation between EmploymentStatus and BorrowerAPR: 
1-People who are not employed receive high interest rate compared to the employed. 2-The higher the income, the lower the interest rate.
The loan status for the past dues have a high interest rate.
Number of Defaulted loans for Self-employed people are larger than those for Not Employed

Borrower APR and Lender yield are directly positively correlated as when the interest borrowers pays more , the lender yield will increase. Higher the prosper score lower will lower borrower apr and then the lender yield will also be lower.

## Key Insights for Presentation

For the presentation, I focus on just the influence of the factors that is affected by the loan status and the emplyment status to see if the borrower will take a risk by how much.
Relation between EmploymentStatus, LoanStatus and BorrowerAPR:
1- Employed people are diverse regarding the Loan Status and BorrowerAPR as they have sometimes high borrower rate like in chargeoff and sometimes low borrower rate like in the past dues.
2- Employees with Full-Time and part-time tend to have lower BorrowerAPR across all loan status categories.
3- Employees with Not-Employed & Self-Employed tend to have higher BorrowerAPR in some areas like the past dues but lower BorrowerAPR in the current and completed status.

At the end I checked the BorrowerAPR vs. ProsperScore using LoanOriginalAmount and found that most of the loans with higher amounts (>$20,000) are taken by people with higher prosper score.
