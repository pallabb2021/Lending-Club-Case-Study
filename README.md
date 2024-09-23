# Lending Club Case Study Project

## Table of Contents
* [Business Objective](#Business-objective)
* [Python Module Usage](#Python-Module-Usage)
* [Conclusions](#Conclusion)
* [Contributer](#Contributer)

## Business-objective

We are assisting a consumer finance company in identifying key characteristics of applicants who are likely to default (fail to repay the loan) and those who are not, using Exploratory Data Analysis (EDA) methods. This company specializes in types of loans to customers. They receive applications and must decide whether to approve a loan based on the applicant’s ability to repay, aiming to enhance their performance.

To achieve this, we will analyze past data to determine which types of applicants are likely to default and which are not, thereby simplifying the loan approval or rejection process. We will utilize two files: a CSV file containing historical loan data (loan.csv) and an XLSX file with relevant information about the data (Data_Dictionary.xlsx).

## Python Module Usage

* pandas 2.2.2
* seaborn 0.12.2
* matplotlib 3.7.5
* numpy 1.26.4

## Conclusion

- The funded amount and loan amount shows high correlation which signifies in most of the cases the amount is approved.
- CA state has more than 800 charged off situation followed by FL which is close to 400. Also, most of the full payment happened from CA, so only state cannot be used for decision.
- Quarter 4 has seen a greater number of loans and also higher on the charge off situation.
- Not verified status has a greater number of charge off, so verification is mandatory going forward for new applicants.
- Charge off was majorly seen for sub grade B5, B3, C1 and C2.
- In the zip code analysis is the top 3 charge off happened from zip codes 945xx, 331xx, 917xx where as the top 3 for full payment was from 112xx, 606xx and 100xx. This could be an indicating factor.
- Charge off has shown a higher DTI in general
- Higher interest rate also risks towards charge off.
- Grade F and G has on the higher end of borrowing money and also, they are in the higher interest rate bucket leading to more charge off.
- Home ownership having rent or mortgage has paid fully compared to other categories.
- The median amount of charge off is around 15k
- Public record bankruptcies are highly correlated with public records, other variables are not correlated or negatively correlated.
- Total payment is highly correlated with loan amount, funded amount and funded amount investor.
- Installment shows high correlation with total payment and total payment investor
- Month, year and quarter are less correlated with other variables.
- Revolving balance is not highly correlated with other variables.
- More than 80% of loan are fully paid.
- Public bankruptcies are majorly less, close to 90%
- 30 Month term is preferred over 60-month term
- There were more number of borrowers with > 10+ years of experience with highest funded amount.
- DTI was on the higher end where the charge off happened, which signifies as the debit amount rose, the chances of repayment went down.
- Highest amount of loan was requested in December month. The loan amount increased year by year and and highest in 2011.
- The loan amount mean was around 8500, where 75% of borrowers had loan amount under 13000
- The funded amount mean around 8400, where 75% of borrowers had received 12800 as funded amount. So, most the loan request were approved.
- The salary had a mean around 54000 and after removing the outliers the maximum stands at 140000
- The interest rate had a mean around 11%, the maximum was set around 24%.
- 75% of installment amount was around 380 and maximum was around 934.
- Around 52% stayed in Rented home, followed by Mortgage which is 40%
- A lot of application was not verified which was around 46%, followed by verified at 27%
- The major reason for taking loan was debt_consolidation, which is over 40%
- More than 30% from the list belong to Grade B, followed by Grade A.
- Loan amount of 5k to 10k was most preferred loan amount.

## Contributer

- Pallab Bhattacharya
- Anilan M
