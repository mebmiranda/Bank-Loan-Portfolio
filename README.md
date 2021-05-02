# Bank-Loan-Portfolio
Markov Chain Analysis


### Objective ###

ABC Bank deals with both asset and liability products in the retail bank industry. A Big portfolio of the bank is based on loans. These loans make the majority of the total revenue earned by the bank. Hence, it is very essential for the bank to find the proportion of the loans 2 years and 3 years from now, and in the long run. Perform Markov Chain Analysis to determine the bank loan proportions. 

The following are the loan classifications:
 - Good Loan
 - Bad Loan
 - Risky Loan
 - Paid Up Loan

### Method ###
 - Generate 1,000 random past loan transitions (e.g. from 'Good Loan' to 'Bad Loan').
 - Compute the conditional probability for each of the loan types (e.g.  Prob(Good Loan | Bad Loan) ).
 - Generate 200 random current loans and compute the current year's loan proportion. 
 - Create the Markov Transition Matrix.
 - Write a script to create Makov Chain Analysis function.
 - Use the Markov Chain Analysis script function to determine the year 2 loan proportion, year 3 loan proportion and loan proportion in the long run.

### Conclusion
Based on the Markov Chain Analysis, for year 2, the portfolio will be 0.253527 for Good Loan, 0.248069 for Bad Loan, 0.231041 for Risky Loan and 0.267526 for Paid Up Loan. For year 3, the portfolio will be 0.253580 for Good Loan, 0.247933 for Bad Loan, 0.230961 for Risky Loan, and 0.267526 for Paid Up Loan. Lastly, in the long run or at steady state, the portfolio will be 0.253578 for Good Loan, 0.247936 for Bad Loan, 0.230966 for Risky Loan and 0.267519 for Paid Up Loan.
