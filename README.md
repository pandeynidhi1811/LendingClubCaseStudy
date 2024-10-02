# Lending Club Case Study Analysis


## General Information
- The consumer finance company faces two critical risks in the loan approval process: potentially missing out on profitable business by rejecting creditworthy applicants and incurring financial losses by approving loans for applicants likely to default. 

- The objective of this case study is to analyze data from past loan applicants to identify patterns and factors that indicate the likelihood of loan defaults.

## Approach
We will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
- Accepted
  - Fully Paid - Loan is completely repaid.
  - Current - Applicant is still making payments.
  - Charged-off - Applicant has defaulted on the loan.
- Rejected: No transactional history is available for the applicant.

## Conclusions

Determinants of Default Risk:
 -Annual Income: Lower incomes correlate with higher default rates.
- Loan Term: 60-month loans show higher default rates than 36-month loans.
- Employment Length: Longer employment tenure (10+ years) is associated with higher repayment rates.
- Loan Grade: Higher-grade loans (A, B) have lower default rates compared to lower-grade loans (D, E, F, G).

Economic Indicators:
- High Debt-to-Income (DTI) ratios and revolving credit utilization indicate greater risk.
- Interest Rates:
- Charged-off loans tend to have higher median interest rates, reflecting increased repayment burdens.

Predictive Decision-Making:
- The company should refine loan approval criteria based on data-driven insights to better manage risk.
- Enhanced Risk Management:
- Pivot tables and correlation analyses highlight interactions between various factors influencing default risk.

## Technologies Used
- Python Libraries (Pandas, Numpy, Seaborn, Matplotlib)
- MS Excel
- Jupyter notebook


