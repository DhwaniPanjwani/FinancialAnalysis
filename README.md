# FinancialAnalysis
Case Study
In this Study, we use the historical data from loans that were issued on LendingClub
between April 2008 and September 2019. You can download the dataset from the following
link: [https://www.andrew.cmu.edu/user/shubhras/mlps/cs-data/]
The dataset contains more than hundred features, including the following, for each loan:
1. Loan amount
2. Interest rate
3. Monthly installment amount
4. Several additional attributes about the borrower (type of house ownership, annual
income, monthly FICO score, debt-to-income ratio, number of open credit lines, etc.)
5. Loan status (e.g., fully paid, default, charged-off)
Loan status is defined as summarized in Table 1.1. Current refers to a loan that is still being
reimbursed in a timely manner. Late corresponds to a loan on which a payment is between
16 and 120 days overdue. If the payment is delayed by more than 121 days, the loan is
considered to be in Default. If LendingClub has decided that the loan will not be paid off,
then it is given the status of Charged-Off.
Number of days past due Status
0 Current
16-120 Late
121-150 Default
150+ Charged-off
Loan statuses in LendingClub

In short, each loan expires 5 months after the term of the loan has ended, and ends in
one of two LendingClub states—fully paid or charged-off. In the former, the investor is
reimbursed fully for the balance plus interest, and has earned positive return. The latter,
on the other hand, causes loss depending on how much of the loan was paid of before being
charged-off.
