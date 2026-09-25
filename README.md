# Bank-Loan-Analysis
# Loan Portfolio & Credit Risk Analysis using SQL

## Project Overview

This project analyzes a bank loan dataset using SQL to understand loan applications, funded amounts, repayment performance, borrower characteristics, and credit risk.

The analysis focuses on identifying patterns in loan performance and creating meaningful KPIs that can help understand the overall health of a loan portfolio.

The project covers both overall portfolio analysis and detailed analysis based on borrower and loan characteristics such as loan status, state, loan term, employment length, loan purpose, and home ownership.

---

## Project Objectives

The main objectives of this project are:

* Analyze the overall loan portfolio.
* Calculate important loan-related KPIs.
* Compare good loans and bad loans.
* Analyze loan performance based on loan status.
* Study monthly trends in loan applications and funded amounts.
* Analyze loan distribution across different states.
* Understand the effect of loan term on the portfolio.
* Analyze loan applications based on employment length.
* Study loan purposes and their contribution to the portfolio.
* Analyze loans based on home ownership.
* Build a foundation for understanding credit risk using loan data.

---

## Dataset

The dataset contains information about loan applications, borrowers, loan characteristics, and repayment performance.

### Major Fields Used

| Field                 | Description                                          |
| --------------------- | ---------------------------------------------------- |
| Loan ID               | Unique identifier for each loan.                     |
| Address State         | State/location of the borrower.                      |
| Employee Length       | Length of the borrower's employment.                 |
| Employee Title        | Borrower's occupation/job title.                     |
| Grade                 | Credit/risk grade assigned to the loan.              |
| Sub Grade             | More detailed classification within a grade.         |
| Home Ownership        | Borrower's housing status.                           |
| Issue Date            | Date when the loan was issued.                       |
| Last Credit Pull Date | Date of the most recent credit information check.    |
| Last Payment Date     | Date of the borrower's latest payment.               |
| Loan Status           | Current status of the loan.                          |
| Next Payment Date     | Expected date of the next payment.                   |
| Purpose               | Reason for taking the loan.                          |
| Term                  | Loan repayment duration.                             |
| Verification Status   | Indicates whether borrower information was verified. |
| Annual Income         | Borrower's yearly income.                            |
| DTI                   | Debt-to-Income ratio of the borrower.                |
| Instalment            | Monthly loan payment.                                |
| Interest Rate         | Interest charged on the loan.                        |
| Loan Amount           | Principal amount borrowed.                           |

---

# Key Performance Indicators (KPIs)

The project calculates several important KPIs to understand the loan portfolio.

### 1. Total Loan Applications

Total number of loan applications present in the dataset.

### 2. Total Funded Amount

Total amount of money funded through the loans.

### 3. Total Amount Received

Total payment amount received from borrowers.

### 4. Average Interest Rate

Average interest rate across the loan portfolio.

### 5. Average DTI

Average Debt-to-Income ratio of borrowers.

### 6. MTD Analysis

Month-to-Date values are calculated to monitor recent loan activity.

### 7. PMTD Analysis

Previous Month-to-Date values are used to compare current performance with the previous period.

---

# Good Loan Analysis

Loans classified as **Fully Paid** or **Current** are considered good-performing loans for this analysis.

The project calculates:

* Good Loan Percentage
* Good Loan Applications
* Good Loan Funded Amount
* Good Loan Amount Received

This helps understand the proportion and financial contribution of performing loans in the portfolio.

---

# Bad Loan Analysis

Loans with the status **Charged Off** are considered bad loans for this analysis.

The project calculates:

* Bad Loan Percentage
* Bad Loan Applications
* Bad Loan Funded Amount
* Bad Loan Amount Received

This provides an overview of the portion of the portfolio associated with poor loan performance.

---

# Loan Status Analysis

Loan performance is analyzed using different loan statuses.

For each loan status, the analysis considers:

* Number of loans
* Total amount received
* Total funded amount
* Average interest rate
* Average DTI

This helps compare the financial characteristics of different loan-performance categories.

---

# Detailed Analysis

## Monthly Analysis

Loan activity is analyzed month-wise to identify trends in:

* Loan applications
* Funded amount
* Amount received

This helps understand how loan activity changes over time.

---

## State-wise Analysis

Loan applications are analyzed across different borrower states.

Metrics include:

* Total loan applications
* Total funded amount
* Total amount received

This can help identify regions with higher loan activity.

---

## Term Analysis

Loans are analyzed according to their repayment term.

This helps compare the number and financial value of loans with different repayment durations.

---

## Employee Length Analysis

The project analyzes loan activity according to the borrower's employment length.

This can help understand whether employment stability is associated with differences in loan activity.

---

## Purpose Analysis

Loans are grouped according to their stated purpose.

Examples include:

* Debt consolidation
* Credit card
* Home improvement
* Major purchase
* Education
* Medical
* Small business

The analysis compares loan applications, funded amounts, and amounts received across different purposes.

---

## Home Ownership Analysis

Loans are also analyzed based on the borrower's home ownership status.

This helps understand how loan activity differs between different housing categories.

---

# Tools & Technologies

* **SQL**
* **Microsoft SQL Server**
* **SQL Server Management Studio (SSMS)**
* **Excel / CSV Dataset**
* **Power BI** *(if used for dashboard creation)*

---

# SQL Concepts Used

The project uses SQL concepts including:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `COUNT()`
* `SUM()`
* `AVG()`
* `CASE WHEN`
* Aggregate functions
* Date functions
* Conditional filtering
* KPI calculations

---

# Project Structure

```text
Loan-Portfolio-Credit-Risk-Analysis/
│
├── Dataset/
│   └── bank_loan_data.csv
│
├── SQL/
│   └── Loan_Analysis.sql
│
├── Dashboard/
│   └── Loan_Dashboard.pbix
│
├── Images/
│   └── dashboard_screenshots/
│
└── README.md
```

---

# Key Business Questions

This project attempts to answer questions such as:

* How many loans have been issued?
* What is the total amount funded?
* How much money has been received from borrowers?
* What is the average interest rate?
* What is the average borrower DTI?
* What percentage of loans are performing well?
* What percentage of loans are charged off?
* Which loan purposes have the highest loan activity?
* Which states have the highest number of loan applications?
* How does loan activity vary by loan term?
* How does employment length relate to loan activity?
* How does home ownership relate to loan distribution?
* How does loan performance change over time?

---

# Project Outcome

The analysis provides a structured view of the loan portfolio and helps identify patterns in loan performance, borrower characteristics, funding, repayment, and credit risk.

The project demonstrates how SQL can be used to transform raw loan data into meaningful business insights and KPIs that can support financial analysis and decision-making.

---

# Future Improvements

The project can be extended by:

* Adding more advanced SQL analysis.
* Building an interactive Power BI dashboard.
* Performing statistical analysis of loan defaults.
* Creating a loan default prediction model using machine learning.
* Comparing risk across grades and sub-grades.
* Developing automated monthly portfolio reports.

---

# Author

**Vamsi Krishna**

**B.Tech – Petroleum Engineering, IIT (ISM) Dhanbad**

---

⭐ If you find this project useful, feel free to explore the SQL queries and analysis included in the repository.
