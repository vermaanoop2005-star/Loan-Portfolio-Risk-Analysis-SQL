# Loan Portfolio & Risk Analysis using SQL

## About the Project

This is a SQL project based on loan portfolio and customer data.

In this project, I used SQL queries to analyze loan applications, loan amounts, customer information, payment status, credit scores, outstanding amounts, overdue amounts and loan risk.

The project contains **80 SQL questions and queries**, starting from basic data retrieval and filtering to more advanced business and risk analysis.

## Project Objective

The main objective of this project is to use SQL to understand the loan portfolio and answer business-related questions such as:

* How many loan applications are there?
* How many loans are approved or disbursed?
* What is the total loan amount?
* Which loan types have the highest loan amounts?
* Which cities have higher loan disbursement?
* How much outstanding and overdue amount is there?
* What is the loan approval and rejection rate?
* Which customers fall into different risk categories?
* Which customers have high loan amounts compared with their income?
* Which customers have multiple loans?

## SQL Concepts Used

In this project, I practiced the following SQL concepts:

* `SELECT`
* `WHERE`
* `AND / OR`
* `IN`
* `BETWEEN`
* `LIKE / ILIKE`
* `ORDER BY`
* `LIMIT`
* `COUNT()`
* `SUM()`
* `AVG()`
* `MIN()`
* `MAX()`
* `ROUND()`
* `GROUP BY`
* `HAVING`
* `CASE WHEN`
* Subqueries
* `JOIN`
* Date functions
* `EXTRACT()`
* Conditional aggregation
* Percentage calculations
* Risk categorization

## Analysis Covered

### 1. Basic Loan Analysis

I started with basic queries to understand the loan data.

Examples:

* Display all loan records
* Display customer and loan information
* Find Personal Loan customers
* Find loans above a particular amount
* Find customers with higher credit scores
* Find approved loans
* Find overdue payments
* Find loans with high outstanding amounts

## 2. Sorting and Filtering

I used filtering and sorting to find specific records.

Examples:

* Top 10 largest loans
* Customers sorted by credit score
* Loans sorted by loan amount
* Loans with interest rate above 10%
* Customers within a specific age range
* Customers whose names start with a particular letter
* Customers from selected states or cities

## 3. Loan Portfolio Metrics

I calculated important portfolio-level metrics such as:

* Total loan applications
* Total approved loans
* Total requested loan amount
* Total disbursed amount
* Total outstanding amount
* Total overdue amount
* Average loan amount
* Average interest rate
* Average credit score
* Average annual income
* Maximum and minimum loan amount

## 4. Loan Type and Location Analysis

I also analyzed the loan portfolio by different categories.

This includes:

* Number of loans by loan type
* Total loan amount by loan type
* Average loan amount by loan type
* Total loan amount by city
* Number of customers by state
* Average credit score by loan type
* Outstanding amount by loan type
* Overdue amount by city
* Loans by payment status
* Loans by employment type

## 5. Risk Analysis

One of the main parts of this project is customer risk analysis.

I created risk categories based on credit score:

* **Low Risk:** Credit Score >= 750
* **Medium Risk:** Credit Score >= 650
* **High Risk:** Credit Score >= 550
* **Very High Risk:** Credit Score below 550

I then analyzed:

* Number of customers in each risk category
* Total outstanding amount by risk category
* Total overdue amount by risk category

This helped me understand how credit score can be used to categorize customers based on risk.

## 6. Loan Approval & Payment Analysis

I calculated important loan performance metrics such as:

* Loan approval rate
* Loan rejection rate
* Total disbursed amount
* Total outstanding amount
* Total overdue amount
* Default customer count
* Percentage of overdue loans

These queries can be useful for understanding the overall performance of the loan portfolio.

## 7. Date-Based Analysis

I also used date functions to analyze loan activity over time.

Examples:

* Loans applied for in a particular year
* Loans approved during a particular month
* Number of loans applied for each year
* Total loan amount disbursed each year
* Number of loans approved by month
* Average number of days between application and approval

## 8. Advanced SQL Analysis

Towards the end of the project, I used subqueries and more advanced conditions.

Some examples include:

* Customers whose loan amount is greater than the average loan amount
* Customers whose credit score is above the average
* Customer with the highest loan amount
* Customers with outstanding amount above average
* Loan type with the highest total loan amount
* Top 5 customers by total loan amount
* Top 3 cities by total loan disbursement
* Top 3 loan types by outstanding amount

## 9. Credit Risk Conditions

I also identified customers with potentially higher risk using multiple conditions.

For example:

* Credit score below 650
* Overdue amount greater than ₹50,000
* High loan amount compared with annual income
* Customers having multiple loans
* Customers having a closed previous loan but another active loan

The project also calculates a **loan-to-income ratio** to identify customers whose loan amount is high compared with their annual income.

## Business Questions Answered

The project helps answer questions such as:

1. How many loan applications are present?
2. What is the total loan amount?
3. What is the total disbursed amount?
4. How much outstanding amount is there?
5. How much overdue amount is there?
6. Which loan type has the highest total loan amount?
7. Which cities have higher loan disbursement?
8. What is the loan approval rate?
9. What is the loan rejection rate?
10. How many customers are in each risk category?
11. Which risk category has the highest outstanding amount?
12. Which customers have high overdue amounts?
13. Which customers have multiple loans?
14. Which customers have a high loan-to-income ratio?

## Tools Used

* SQL
* PostgreSQL-style SQL syntax
* SQL queries
* Relational data analysis

## Project Structure

```text
Loan-Portfolio-Risk-Analysis-SQL/
│
├── Loan_Portfolio_Risk_Analysis.sql
└── README.md
```

## What I Learned

Through this project, I improved my understanding of:

* Writing SQL queries
* Filtering and sorting data
* Aggregate functions
* Grouping data
* Business analysis using SQL
* Conditional logic using CASE
* Subqueries
* JOIN operations
* Date-based analysis
* Risk analysis
* Loan portfolio analysis
* Converting business questions into SQL queries

## Conclusion

This project helped me practice SQL from basic queries to more advanced business analysis.

By working on 80 different questions, I got practical experience in analyzing loan applications, customer credit information, loan status, payments, outstanding amounts and risk.

The main focus of the project was not only writing SQL queries, but also understanding how SQL can be used to answer real business and financial analysis questions.
