# Lending Club Case Study
> Working for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

>When a person applies for a loan, there are two types of decisions that could be taken by the company:
Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

- Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

- Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

- Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

>Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Table of Contents
* [Business Overview](#Business-Objective)
* [Technologies Used](#technologies-used)
* [Exploratory Data Analysis](#Steps)
* [Conclusions](#conclusions)

#Business-Objective

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

- The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.
- The company can utilise this knowledge for its portfolio and risk assessment.

- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

- Our aim is to identify the loan application which can be defaulted or deliquanted which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate

> #dataset : loan.csv

## Technologies Used
- pandas     - Version: 1.2.4
- numpy      - Version: 1.20.1
- pandasql   - Version: 0.7.3
- matplotlib - Version: 3.3.4
- seaborn    - Version: 0.11.1

# Exploratory Data Analysis

## Steps

- Data Cleaning Missing Data Teatment
- Data Cleaning Removing Customer Behavior Variables
- Data Cleaning - Standardizing Values, Units, Date & Text
- Data Cleaning - Outlier Analysis
- Dervied Metrics & Binnning
- Univariate Analysis
- - Continous variable
- - Categorical variable
- Segmented Univariate Analysis
- Bivariate Analysis
- - Continuous vs Continuous
- - Continuous vs Categorical
- - Categorical vs Categorical
- MultiVariate Analysis & Correlation Matrix
- Summary Statistics
- Missing Data Treatment Analysis Report
- Univariate Data Analysis Report
- Bivariate Data Analysis Report
- Final Conclusion
- Important Points and Assumptions
- Considering values greater than Q3+1.5IQR(Upper Bound) & Q1-1.5IQR(Lower Bound) for Outliers treatment provided we got approval from Business
- Loan_status Chargedoff Conversion - 0 & FullyPaid Conversion -1
- Custom functions created for visualisation for code readibility
- Graph used : Power Law Distribution , Barchart - Horizontal & Vertical , piechart , boxplot , - - -scatterplot, barplot ,catplot, violinplot , heatmap , countplot
- used pivot table & pandasql for Data Analysis

## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis



## Contact
Created by [@shashank1989] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
