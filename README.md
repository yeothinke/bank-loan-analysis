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
- Overall, the bank has a loan charge-off rate of 15%.
- This is a considerably high charge-off rate, as compared to the industry's average in 2021, which is 0.25% on average as obtained from the [Board of Governors of the Federal Reserve System](https://www.federalreserve.gov/releases/chargeoff/chgallsa.htm).
- With government stimulus and economic recovery following the pandemic in 2020, we should not expect particularly high loan default rate in 2021.
- Therefore, this high charge-off rate may signal a need for the bank to reassess their lending procedures in order to reduce their credit risk.
- It is worth looking at the bank's historical loan data to investigate the trend in charge-off rate. This allows us to know whether this charge-off rate is considered abnormally high and to investigate the cause of it.

## Recommendations
**Strengthen Risk Assessment**:
- To reduce the high charge-off rate, the bank can consider tightening credit standards by implementing stricter debt-to-income (DTI) ratios.
- As seen from the dashboard, only 25.3% of the borrowers are source verified, while 32% are verified and 42.7% are not verified. This means that the information provided by borrower could be false. Borrowers could inflate thier annual income or provide inaccurate employment status in order to increase the probability of their loan getting approved. This could lead to a higher risk of loan default if the borrower does not actually have the financial means to repay their loans. This poses a greater risk for the bank, therefore there is a need to enhance their borrower verification to tackle the high charge-off rate.
- The bank could also consider using additional data such as utility and rent payment histories, and bank account transaction data to assess thin-file borrower.
  
**Strengthen Debt Collections & Recovery**:
- The bank can strengthen outreach and engagement with borrowers by contacting borrowers at first signs of stress, not just after default. The bank can also consider restructuring the loan such as loan modifications, or extended terms to reduce charge-offs.
  
**Limit exposure by geography**
- The bank can reduce concentrations in states/regions with persistently higher default risk. We observe that the top three states with highest non-performing loan ratios are Nebraska, Nevada, and Alaska.
- It is worth looking into these states to understand why the non-performing loan ratios are one of the highest so as to reassess whether to continue issuing loans in these states or evaluate the need for tightened credit standards.


## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/views/LoanAnalysis_17549240916880/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link). 

This dashboard consists of a two layer structure:
- The main dashboard consists of an overview of the performance of the loan portfolio for the loans issued in 2021, including key metrics such as loan application growth rate, loan yield, and charge-off rate. There is a monthly trend chart whereby user can filter by the total loan applications, total loan amount and total repayment amount to visualise the trend in terms of loan demand and loan revenue. 

- The second dashboard focuses on loan segmentation, allowing users to examines the loan and borrower background in more details whereby user can filter by the different loan status.

<img width="812" alt="image" src="https://github.com/christinejiang11/rowhealth/assets/56368090/86756aa4-a0d8-44eb-a0d5-c128816f42ac">
