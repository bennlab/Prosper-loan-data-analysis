# Prosper Data Exploration
## by Ben Mumo


## Dataset

The dataset contained 81 variables and 113937 observations. The dataset was accompanied by a CSV that had variable definitions to make it easy to understand the variables. The dataset is available [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv).


## Summary of Findings

> In my exploration I noticed that prosper score is negatively correlated with the effective yield, since the better the scores the lesser effective yield amount. Which means the lender prioritizes his best customers and offers them lower rates for their loans.Looking into the effect of Prosper score and term on effective yield, the exploration showed that better scores decrease the effective yield and increases the loan amount and vice versa.There is a negative correlation between Loan amount and effective yield since as Loan amount increases, the effective yield decreases, which is a good incentive for people to borrow bigger amounts. 


> Away from my main variable of interest, Loan Original amount and monthly loan payment, have a linear relationship, which means as loan amount goes up, so does the monthly loan payment go up. This depicts a positive correlation between the two variables. It is also clear that with better scores, Loan amounts increase and borrowers with bigger loan amounts tend to have longer loan terms. Therefore Prosper Score and Loan terms strengthened each other in looking into Original Loan amount.

> Finally, looking into our single variables It is clear that mostly the Employed and Fulltime category of borrowers borrow more and they mostly borrow loans with a duration of 36 months. The Employed category however has the highest 60 months loan-term loans.It is also important to note that most of our borrowers have a prosper score of 6 and most of them opt for the 36 months loan-term package over the other loan-term packages


## Key Insights for Presentation

> Here my main focus is features that affect Effective yield(which is a form of Interest rate for the loans). I start by exploring the distribution of my main features of interest(Prosper_Score, Loan_original_amount, Monthly_loan_ payment and Term). Then I compare each with effective yield and study how they affect the main feature. Finally I get into exploring relationships between the variables in relation to my main feature.