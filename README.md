# Lending Club Case Study
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


## Table of Contents
* [Objective](#objective)
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Libraries Used](#libraries-used)

<!-- You can include any other section that is pertinent to your problem -->

## Objective
In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.


## General Information
When a person applies for a loan, there are two types of decisions that could be taken by the company:

- Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

  - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

  - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

  - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

- Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- **Interest Rates and Default Risk**: *Higher interest rates are strongly correlated with a higher likelihood of loan default. Borrowers with rates in the "Very High" category had the highest default rates.*
- **Income and Loan Default**: *Borrowers with lower annual incomes (particularly those below $40K) are more likely to default on their loans. This emphasizes the need for stringent income verification and assessment.*
- **Employment Tenure**: *A shorter employment period, particularly under 5 years, is associated with higher default risks. Borrowers with over 10 years of employment have lower default rates.*
- **Loan Amount and Default**: *Loans in the mid-range ($5K-$15K) see the highest number of defaults. However, the proportion of defaulters is highest in the $15K and above category.*
- **Home Ownership**: *Renters have a higher default rate compared to homeowners, particularly those with a mortgage. This indicates that home ownership status is a significant factor in assessing loan risk.*
- **Purpose of Loan**: *Loans taken for small businesses have the highest default proportions, while debt consolidation loans have the highest number of defaulters. This insight can guide the development of targeted loan products.*
- **Geographic Influence**: *Certain states, such as Nevada (NV), show higher proportions of defaults, suggesting geographic location plays a role in loan repayment behavior.*
- **Verification Status**: *Loans that were not verified show a higher rate of default, highlighting the importance of thorough verification processes in loan approval.*

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Libraries Used
- numpy - 1.26.4
- pandas - 2.2.2
- seaborn - 0.13.2
- matplotlib.pyplot - 3.8.4
