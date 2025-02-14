# Bank-Loan-Report

### Introduction

This Power BI dashboard provides insights into bank loan applications, funding, and repayment trends. It helps financial analysts, loan officers, and business stakeholders understand key metrics such as loan approval rates, funded amounts, interest rates, and loan status distribution.

### Problem Statement

Banks and financial institutions need a way to monitor loan performance, borrower behavior, and repayment patterns to mitigate risks and optimize lending strategies. This dashboard aims to address:

* What is the total number of loan applications and their approval rates?
* How do funded loan amounts compare with received loan payments?
* What is the impact of loan duration and interest rates on repayment trends?
* How do different loan purposes affect repayment and default rates?

### Dataset Overview

Source: Financial Loan Dataset from Kaggle

Data Processing: The data was first loaded into MySQL for structuring and preprocessing before being imported into Power BI Desktop for visualization.

Key Attributes:

* Loan Application Count
* Loan Status (Good Loan vs. Bad Loan)
* Funded Amount
* Received Amount
* Interest Rate
* Debt-to-Income (DTI) Ratio
* Loan Purpose (Debt Consolidation, Credit Card, Home Improvement, etc.)
* Loan Term (36 months, 60 months)
* Employment Length

### Key Insights & Features

* Total number of loan applications and approval rates
* Good vs. bad loan distribution and repayment trends
* Interest rate variations across different loan categories
* Debt-to-income ratio analysis for borrowers
* Loan applications based on employment length and purpose
* Trends in loan-funded vs. received amounts over time

### Visualizations Used

* Bar Chart: Loan application count by category and term
* Line Chart: Trends in funded and received loan amounts
* Pie Chart: Loan status distribution (Good Loan vs. Bad Loan)
* Scatter Plot: Relationship between interest rates and repayment success
* Tree Map: Total Loan application by Home Ownership
  
### How to Use the Dashboard

* Download the bank_loan.pbix file from this repository.
* Open it in Power BI Desktop.
* Explore interactive visualizations and filters to gain insights
