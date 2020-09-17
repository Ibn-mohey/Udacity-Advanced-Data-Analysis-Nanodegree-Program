
# Exploration of (Loan Data from Prosper)
## by Abd-elrhman Mohey

## Dataset

This data set contains **113,937 loans** with **81 variables** on each loan, including loan **amount**, **borrower rate (or interest rate**), **current loan status**, borrower **income**, and many others

## Summary of Findings

we have looked her in this large data set first to understand it's content, and come up with 2 questions
1. What **factors** affect a loan’s **outcome status**?

2. what affects the **borrower’s APR** or **interest rate**?

This is a very critical questions for banks and loaners in real life to minimize the risk.
our main Findings were
1. loans that are **charged-off**, loans with **past due payments** and **defaulted loans** have **slightly higher average monthly payments**  compare to others like **current and completed**
2. loans that are **charged-off**, loans with **past due payments** and **defaulted loans** have **in average higher interest rates** compare to others like **current and completed**
3. loans that are **charged-off**, loans with **past due payments** and **defaulted loans** have almost same **average Original Amount** compare to others like **current and completed**
4. The **length of the loan** have **NO impact** on the status of the loan.
5. The **Status of Employment** have **NO impact** on the status of the loan.
6. The **Income Range** have **NO impact** on the status of the loan.

and more we found that
1. EstimatedEffectiveYield has **negative** correlation with EstimatedLoss, and **positive** with EstimatedReturn
2. EstimatedLoss has **negative** correlation with EstimatedReturn
3. EstimatedReturn has **positive** correlation with EstimatedEffectiveYield, and **negative** with EstimatedLoss
4. LP_CustomerPayments has **positive** correlation with LP_CustomerPrincipalPayments
5. LP_CustomerPrincipalPayments has **positive** correlation with LP_CustomerPayments
6. LP_ServiceFees has **negative** correlation with LP_CustomerPayments , LP_CustomerPrincipalPayments and LP_InterestandFees
7. LP_GrossPrincipalLoss has **positive** correlation with LoanOriginalAmount and LP_NetPrincipalLoss
8. LP_NetPrincipalLoss has **positive** correlation with LoanOriginalAmount and LP_GrossPrincipalLoss
