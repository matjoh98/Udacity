# Prosper Loan Analysis
## by Mattias Johansson

## Dataset

The dataset contains detailed information on 113,937 loans, with 81 different variables recorded for each loan. These variables include the loan amount, the borrower's interest rate, the current status of the loan, the borrower's income, and many other relevant details. Some rows are collected only from 2009 and forward, creating a numerous amount of NaN values that may affect the historical analysis. 

## Summary of Findings

This investigation aims to explore and analyze correlations between the prosper loans and APR that the loan takers will recieve. The parameters of focus is the loan amount, APR (Annual Percentage Rate), loan rate, occupation, loan status, employment status. Other parameters that helped the analysis are income and monthly loan payment. 

The key insights that the exploratory analysis provides are the following:

- Employed people have in average generally lower borrower rate than unemployed which may be explained by that people that earn more get a lower APR in general.
- The spread of the APR is more tangible for lower incomes and denser the more you earn based on how much you pay each month back in mortgage and rate.
- The non-informational category "Other" in the "Occupation" variable are among the top loan takers in this dataset. The category Professional, Computer programmer, Executive, Teacher and Analyst are among the top 5 loan takers. These categories are more prone to take a loan than other categories.
- We observe when filtering large loan takers that all of them do have an employment of any kind. Mostly they also have these loans as active and the top Occupations are Professional, Excecutive, Other, Computer Programmer, and Analyst
- In general, looking and different income ranges: 500-1200 dollar, > 1200 dollar, IncomeRange and BorrowersAPR share a linear relationship in terms of the sorted ordinal category IncomeRange. In short, people that earn more get a lower APR in general.
- The variance of the different ranges vary a lot, where the MonthlyLoanPayment > 1200 dollars have a broad spread of values for each category. 
- We can summarize that the ordinal category IncomeRange can explain some sub-correlations between BorrowerAPR and MonthlyLoanPayment in terms of variance between the intervals of MonthlyLoanPayment. This can be concluded as the variance of the BorrowerAPR increases with MonthlyLoanPayment.

## Key Insights for Presentation

- The category Professional, Computer programmer, Executive, Teacher and Analyst are among the top 5 loan takers. These categories are more prone to take a loan than other categories.
- The more you earn, the less APR you get.