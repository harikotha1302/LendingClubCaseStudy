# Lending Club Case study
Lending Club case study is about analyzing the data of consumer finance company to analyze the dimensions driving the loan repayment of applicant. Consumer finance companies normally gives loans to urban customers.
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision.

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

the objective of the case study is to analyze and derive conclusions on the different dimensions of loan applicant on the capability of repayment of loan using historical data available.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Objective of the case study to analyze the data available to identify applicants who are more prone to default and minimize the losses to company. Methodology used for analyzing is Exploratory data analysis using python.

Objective is to identify the factors behind the loan default, variables which are strong indicators and correlate with default of loan. Based on which company can decide to approve loan to applicant or not.

We need to find out two kind of variables
1. Identify the variables which are strong indication of loan repayment, which enables the company to disburse loan to proper customer to generate more revenue.
2. Identify the Variables which are strong indication of loan default, which leads to loss of business for company



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

1. Grade B,C and D customers are more prone to loan default. Implement stricter guidelines when disbursing loan to mentioned grades
2. Sub grades B3, B4, and B5 are also more prone to loan default. Implement stricter guidelines when disbursing loan to mentioned grades
3. Longer term loans are more prone to loan default. Move with caution when dealing with them or charge high interest so that loss can be minimum.
4. Customers with more experience are prone to loan default. Which suggest that experience alone cannot trusted when disbursing loan consider other indicators also.
5. Q4 are peak periods for loan applications, likely due to the holiday season. The company should anticipate increased demand during these periods and ensure efficient processing to meet customer needs.
6. debt consolidation loan has more prone to loan default. Maintain caution when dealing with such type of loans
7. Customers living in rented or mortgaged are prone to loan default.
8. As expected Verified customers are less likely to default. So bring in more robust verification process and maximum try to verify all customers
9. Applicants receiving loan amounts of $15,000 or higher are more likely to default.
10. High Debt-to-Income (DTI) ratios and interest rates in the 13%-17% range are associated with defaults.
11.  Applicants with annual incomes less than $40,000 have a higher likelihood of defaulting. The company should consider offering financial education resources or setting maximum loan amounts based on income levels to ensure affordability for borrowers.
12. The steady increase in the number of loan applicants from 2007 to 2011 indicates growth in the market. The company can capitalize on this trend by maintaining a competitive edge in the industry while keeping risk management practices robust.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- [Python](https://www.python.org/) - version 3.12.4
- [Matplotlib](https://matplotlib.org/) - version 3.8.4
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by live session of upGrad on EDA 
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform

## Collaborators

Created by [@harikrishna](https://github.com/harikotha1302) and [@hemant Ramapuram]()


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
