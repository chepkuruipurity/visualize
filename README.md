# (Dataset Exploration for Prosper Loan Data)
## by (Purity Chepkurui)


## ProsperLoanData

> The data for this investigation is gotten from [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000). The dataset contains information on borrowers' profile, and listing informations. prosper is an online peer-to-peer lending marketplace, where credit worthy borrowers can request a loan and investors can invest in "notes" (or portions) of each loan ref. Basically, the aim of this analysis is to investigate how income levels of borrowers who seek loan on prosper actually influence the loan process. It is however, a known fact that income plays an important role in loan sourcing. A higher income provides much more security to obtaining loans not only faster, but as well the amount of loan one could possibly get. Hence the focus of this analysis is to investigate income levels of borrowers and how it interacts with other variables in the dataset. There is a total of 81 columns and 113937 in the dataset, however, I will be limiting the analysis to only 9 variables of interest. The respective columns are;

* LoanStatus: The loan status of  the loan. Lender yield is equal to the interest rate on the loan less than the service fee
* LoanOriginalAmount: The original amount of the loan at the time of listing.
* BorrowerRate: The Borrower's interest rate for this loan.
* MonthlyLoanPayment: Specifies whether the monthly amount to repay the loan.
* Term: The time stated on listing for loan repayment.
* ProsperScore:Prosper score  ranges from 1 to 11, with 11 being the best, or lowest risk, score. The worst, or highest risk, score, is a 1.
* Occupation: The occupation selected by the Borrower at the time they created the Listing.
* EmploymentStatus: The employment status of the Borrower at the time the posted the Listing.
* IncomeRange: The income range of the Borrower at the time the Listing was created.

## Summary of Findings

> There is: a strong positive correlation between loan original amount and monthly loan payment, ProsperScore vs BorrowerRate have a negative correlation,
MonthlyLoan Payment vs BorrowerRate have a negative relationship,
LoanOriginalAmount vs BorrowerRate have a negative relaionship,
LoanOriginalAmount and Monthly Loan Payment have a positive correlation. The more the LoanOriginalAmount the more the MonthlyLoanPayment,
Borrowers with Prosperscore of 1 have the highest Chargedoff loans,
Borrowers with ProsperScore of 9 and 1 have the highest Completed loans,
Borrowers with ProsperScore of 11 have majority of their loans being Current,
Borrowers with ProsperScore 1 have the highest number of defaulted loans,
Majority of Employed borrowers have current loans,
Majority of Full time employees have Completed loans,
The highest completed loans come from full time and part time borrowers,
Employed and other then self employed have current loans,
Not Available(Employment status not stated ) have the highest defaulting rate followed by full time and retired,
Income Range 50k-74999 has the highest current loans,
25k-49999 has the highest completed as well as the highest charged off,
Income Not displayed has the highest defaulted loan,
Majority of borrowers fall under the $(25000-49999) income range,
Loans whose term is 1 year have a higher completed status,
Loans whose term is 5 years have a higher current status,
The shorter the term of the loan the higher the chances of being completed.


## Key Insights for Presentation

> The lower the term, the higher the monthly loan payments, as seen with 12 months term having the highest monthly loan payments.
The longer the term, the higher the loan original amount. The higher the ProsperScore the lower the rates of defaulted loans.The shorter the term of the loan the higher the chances of being completed.