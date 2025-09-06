# Bank Loan Analysis - Project Overview
## The goal of this project is to investigate the performance of the loan portfolio of a bank in order to manage risk and ensure profitability. 

## Dataset Structure
The dataset consists of a table with 24 columns and 38576 rows.

## Insights Summary
#### In order to evaluate loan performance, we focused on the following key metrics:
- **Number of Applications**: The number of loan applications the bank has approved. 
- **Loan Yield**: The average interest rate a bank earns on the loans it has issued to borrowers, expressed as a percentage of the total amount of loans.
- **Charge-Off Rate**: Percentage of loans where borrowers fail to make payments for prolonged period and the loan is charged-off.

#### Number of Applications
- Overall, we observe that the number of loans issued has increased steadily from January to December by 85%.
- This steady increase indicates higher demand for credit, which can be good by increasing bank profits and driving economic activity. However, it's only truly beneficial if the bank manages risk effectively to prevent a rise in non-performing loans, which may affect its profitability.
- The loan purpose category with the highest total application across all months is debt consolidation.

#### Loan Yield
- Based on the total amount of loans the bank has issued and the amount of payment received in 2021, the loan yield is calculated to be 8.5%.
- This amount is likely to be higher as the loan term for the loans is 36 or 60 months, therefore some of the loans have not been fully paid off yet.
- It will be useful to compare the loan yield against the bank's cost of funding for these loans to determine the bank's profitability.

#### Charge-Off Rate
- Overall, the bank has a loan charge-off rate of 13.8%.
- This is a considerably high charge-off rate, as compared to the industry's average in 2021, which is 0.25% on average as obtained from the [Board of Governors of the Federal Reserve System](https://www.federalreserve.gov/releases/chargeoff/chgallsa.htm).
- With government stimulus and economic recovery following the pandemic in 2020, we should not expect particularly high loan default rate in 2021.
- Therefore, this high charge-off rate may signal a need for the bank to reassess their lending procedures in order to reduce their credit risk.
- It is worth looking at the bank's historical loan data to investigate the trend in charge-off rate. This allows us to know whether this charge-off rate is considered abnormally high and to investigate the cause of it.

## Recommendations
- **Health for All**: Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. The second category outperforms across all key metrics, yet we have invested a relatively low amount ($20K) on them.
- **Health Awareness**: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.
- **COVID Campaigns**: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1K, compared to an average signup cost of $2.2. Consider removing these campaigns altogether.
- **#HealthyLiving**: Decrease investment in this campaign category, which has the highest spend ($46K) but mediocre signup rates compared to Health for All campaigns.

## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/views/LoanAnalysis_17549240916880/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

<img width="812" alt="image" src="https://github.com/christinejiang11/rowhealth/assets/56368090/86756aa4-a0d8-44eb-a0d5-c128816f42ac">
