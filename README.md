# Bank Loan Analysis - Project Overview
## The goal of this project is to investigate the performance of the loan portfolio of a bank in order to manage risk and ensure profitability. 

## Dataset Structure
The dataset consists of a table with 24 columns and 38576 rows.

## Insights Summary
#### In order to evaluate loan performance, we focused on the following key metrics:
- **Number of Applications**: The number of loan applications the bank has approved. 
- **Loan Yield**: The average interest rate a bank earns on the loans it has issued to borrowers, expressed as a percentage of the total amount of loans.
- **Loan Default Rate**: Percentage of loans where borrowers fail to make payments.

#### Signup Rate
- Across campaign categories, Health for All campaigns had the best-performing signup rate (2.9%) and the second-highest number of signups (3.5K).
- This high signup rate is due to the Health Awareness campaign type, which had by far the highest signup rate across all campaign types (3.72%).
- Interestingly, the category with the highest number of signups - #HealthyLiving - had a comparably low signup rate at 0.3%.

## Recommendations
- **Health for All**: Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. The second category outperforms across all key metrics, yet we have invested a relatively low amount ($20K) on them.
- **Health Awareness**: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.
- **COVID Campaigns**: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1K, compared to an average signup cost of $2.2. Consider removing these campaigns altogether.
- **#HealthyLiving**: Decrease investment in this campaign category, which has the highest spend ($46K) but mediocre signup rates compared to Health for All campaigns.

## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/christine3803/viz/RowHealthDashboard/Dashboard). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

<img width="812" alt="image" src="https://github.com/christinejiang11/rowhealth/assets/56368090/86756aa4-a0d8-44eb-a0d5-c128816f42ac">
