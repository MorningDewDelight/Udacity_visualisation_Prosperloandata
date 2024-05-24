# Udacity_visualisation_Prosperloandata
Prosper laon data Visualisation

## Introduction

Dataset contains loan information from prosper, having 113937 rows of loan listings with 81 columns.
It features columns like 'LoanStatus', 'ClosedDate','BorrowerAPR','BorrowerRate','Occupation', 'CreditScoreRangeLower',EmploymentStatus','DebtToIncomeRatio',IncomeRange',
'TotalProsperLoans','MonthlyLoanPayment'.

#### Data Dictionary:

https://docs.google.com/spreadsheets/d/1k60B40cr0YAR51X8dmqLGyYBqKzN80Vm2Pnxx3GtHcw/edit?usp=sharing


Prosper was founded in 2005 as the first peer-to-peer lending marketplace in the United States. Since then, Prosper has facilitated more than USD 12 billion in loans to more than 770,000 people.
Through Prosper, people can invest in each other in a way that is financially and socially rewarding. Borrowers apply online for a fixed-rate, fixed-term loan between USD 2,000 and USD 40,000. Individuals and institutions can invest in the loans and earn attractive returns. Prosper handles all loan servicing on behalf of the matched borrowers and investors. 
(source: https://www.prosper.com/about)


Following are some of the key points or questions I am looking for in the dataset.
#### Problem statement:
1. Does owning home impacts borrowers eligibility of loan amount, interest rate irrespective of their credit score and income range?
2. Is there change in borrower rate over the period?
3. Does income has any association with interest rate?

#### Findings:
- Owning home doesn't mean they have high credit score, but due to underlying security they do get loans at lower interest rate compare to non home owners
- Whoever falls in higher income range gets higher loan amount than their counterparts
- Facet plot helps to see people with lower income gets less loan amount with higher interest rate.
- Most of the borrowers falls in medium credit risk basket
- Having low credit risk doesn't mean they always get high loan amount
- Till 2011 Average loan amount was under USD 10000, 2013 onwards volume of loan increased thus the increase in average loan amount, Year 2009 onwards there is no disbursement of loan for high credit risk and undisclosed income borrower.

## Conclusion
   Wherever risk is high returns also high, that echoes in lending business whenever they have high risk customer they will charge them more to balance the risk they take. Owning home doesn't mean they have high credit score, but due to underlying security they do get loans at lower interest rate than non home owners.

   Income range does affect the loan amount they receive, low income people get less loan amount. Here in our dataset most of the borrowers are employed and have medium credit risk.Interest rate increased till 2011, then it declines. Due to decrease in interest rate, volume of loan disbursement increased in 2013.


   Visualisation in Tableau:

   https://public.tableau.com/views/P2P_loan_data_analysis/Story1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link



   ![Story 1](https://github.com/MorningDewDelight/Udacity_visualisation_Prosperloandata/assets/112013346/645c44b9-6157-458d-b689-b0be87194a5f)

