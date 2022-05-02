#Exploring the different variables that affect the loan status
##by Mohamed Elwakel


## prosperLoanData

> This data set contains 113,937 loans with 81 variables on each loan, including
 loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others

## Summary of Findings

I found some interesting relations during this work between the following variables

> 
Loan Status
We find that most counts concentrated between the first three categories
which also make sense here and there is nothing suspecious to run after

>Term
It turns out the majority of people apply to the 36-months-loan

>Borrower Rate , Borrower APR & lender yield
we found that most of the previous three plots concentrated around 0.20

>Estimated Loss
Something interesting huge amount of loans have the Estimated loss around 0.08

> bivariate
>some relations in the heatmap should be 1.0 or -1.0 but it's not, so it tells us how much lost during the process

>The less the borrower rate is the less number of investors take part in the loan

>People with large income apply for the larger loans because the policy of bank and payment ability as well

>In the multivariate we found a quiet equally distributed distribution for home ownership through the different values 
and negative relation between the yield and the number of investors

>The 36-months-loan has the lion part through all loan types but the 12-months-loan here has a good existance here too 
and there's a negative relation between the Available BankcardCredit and the loss


## Key Insights for Presentation

For the presentation, I focused in the first part on exploring each variable alone i explored loan status, term ,Borrower Rate, Borrower APR and lender yield 
single variables visualized by bar and countplots 

Afterwards, I introduced bivariate the chosen variables with heatmaps, boxplots and regressoin model 
Then, I used replot to visualize multivariate visualizations














