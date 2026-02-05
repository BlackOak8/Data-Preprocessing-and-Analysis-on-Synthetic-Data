# Data-Preprocessing-and-Analysis-on-Synthetic-Loan-Application-Data
This project utilizes R to create two synthetic data sets about secured and unsecured loans performances of five retail branches in January in order to better understand market trends and customers’ need. This project mainly focused on data preprocessing and analysis using these synthetic data sets.

## Background
The head of retail banking division would like to random check about secured and unsecured loans performances of five retail branches in January in order to better understand market trends and customers' need.
In this report, there are two synthetic data sets with 120 observations created; one contains January loan applications details and status that the data set is managed by the loan department; when another data set is managed by retail middle office that contains personal information records of applicants in bank.

## Rmarkdown.Rmd
- The R codes that depicted the overall process of this project

## Data generation
1."Loan applications" Data Set
- Contains the details and status of each loan application 
- Is created with total 120 observations and 8 variables with different data type, 
including date, character, factor and integer. Moreover, the data set is exported to CSV file in working directory.
- Attributes:
  - ApplicationDate
  - ApplicationNo
  - LoanType
  - Amount
  - Tenor
  - CustomerNo
  - CustomerName
  - ApplicationStatus

2."Retail Banking Customer" Data Set
- Contains some personal information in order to get a better understanding of each customer's financial status. Each retail customer is assigned to and followed by a retail branch.
- Is created with total 120 observations and 8 variables with different data type, 
including date, character, factor and integer. Moreover, the data set is exported to CSV file in working directory.
- Attributes:
  - BranchCode
  - CustomerNo
  - CustomerName
  - CustomerType
  - Salary
  - NetAssets
  - Occupation
  - ApplicationNo
 
  3."Report" Data Set
  - The combination of Loan applications and Retail Banking Customer data sets
  - Includes 120 observations of loan application information in detail sorted by date in January, and followed by the personal information of the applicants.
  - When reading the Report dataset, it could be easy to identify the total no. of loan application are successfully drawdwon of home loan, car loan & personal loan particularly and also identify which retail branch could achieve better performance in loan sector that obtained more number of drawdown loans.
 
## Data-Preprocessing
1. Merging data sets
2. Data types conversion
3. Missing value checking
4. Missing value replacement
5. Summary statistic for numeric variables

## Output.htm
- Demonstrates the whole process of creating the synthetic data sets, performing the data preprocessing and conducting the summary statistic for numeric variables
- Displays the result of this project
