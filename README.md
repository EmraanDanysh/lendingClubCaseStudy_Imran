# Lending Club Case Study

Lending Club, a consumer finance marketplace focused on providing diverse loan options to urban clientele, encounters a significant challenge in overseeing its loan approval process. In assessing loan applications, the organization is required to make prudent decisions to reduce financial losses, which primarily arise from loans granted to applicants deemed "risky.”
Financial losses, known as Credit Losses, arise when borrowers do not fulfil their loan repayment obligations or default on their loans. In more straightforward terms, borrowers classified as Charged-Off contribute the largest share of losses for the company.
When a loan application is submitted to the company, it must evaluate the applicant's profile to determine whether to approve the loan. This decision involves two types of risks: 
	a. If the applicant is deemed capable of repaying the loan, failing to approve it could mean a missed business opportunity for the company. 
	b. Conversely, if the applicant is assessed as unlikely to repay the loan, approving it could result in a financial loss for the company.
Lending Club seeks to pinpoint high-risk loan applicants to minimize the issuance of such loans, ultimately reducing potential credit losses. Our objective is to uncover the key factors that contribute to loan defaults.


## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Objectives

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

 

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

## Conclusions

1. **Lending Club should exercise caution regarding loans designated for Small Business purposes, as the charge-off rate can reach as high as 27.1%. It is advisable to prioritize loans intended for Weddings, major purchases, vehicles, and credit card consolidation.

2. **There is a correlation between loan amount and the likelihood of charge-offs; thus, Lending Club should focus on approving smaller loans. The highest volume of applications, totaling 12,410, falls within the  5,000𝑡𝑜 10,000 range, where the probability of charge-offs is significantly lower, indicating a reduced risk for the organization.

3. **Lending Club may benefit from increasing its acceptance of loans from applicants with an annual income exceeding $100,000, as these individuals exhibit a minimal charge-off probability.

4. **It would be prudent for Lending Club to accept more loans with interest rates below 7.5%, as these loans also demonstrate a lower likelihood of charge-offs.

5. **Lending Club should aim to approve a greater number of loans classified as grade A and B, while remaining cautious with loans that fall into grades E, F, and G.

6. **Lending Club should consider increasing its acceptance of loans from homeowners, as they tend to present a lower risk profile.

7. **The number of loan applicants is on the rise each year, which is beneficial for Lending Club, leading to an increase in both accepted loans and charge-offs. The final months of the year are particularly significant, as many loans are either fully repaid or charged off during this period.

8. **Lending Club should focus on accepting more loans with a 36-month term, as the percentage of charge-offs is lower and the number of applicants is higher. Additionally, the average amount of fully paid loans has been increasing, while the average amount of charged-off loans has been decreasing over the years..

## Technologies Used
- [Google Collab](collab.research.google.com) --- Majorly used in this case study
- [Python](https://www.python.org/)
- [Matplotlib](https://matplotlib.org/)
- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/) 

