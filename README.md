# 📊 Bank Loan Analysis Dashboard (SQL + Power BI)

## 📌 Project Overview
The Bank Loan Analysis Dashboard is an end-to-end data analytics project built using SQL and Power BI to analyze loan portfolio performance, monitor lending trends, and assess financial risk.

This project transforms raw bank loan data into meaningful insights by calculating key performance indicators (KPIs), analyzing borrower characteristics, and visualizing trends using interactive dashboards.

The dashboard enables stakeholders to understand loan performance, identify risk patterns, and make data-driven financial decisions.

---

## 🎯 Business Objectives

The primary objectives of this project are:

- Analyze overall loan portfolio performance
- Track total loan applications, funded amounts, and repayments
- Identify good loans and bad loans based on loan status
- Monitor month-to-date (MTD) and previous month trends
- Analyze borrower profiles based on employment length, home ownership, and loan purpose
- Identify regional lending trends
- Support risk assessment and strategic decision-making

---

## 🛠️ Tools & Technologies Used

- SQL (MySQL)
- Power BI
- Excel / CSV Dataset
- Data Analysis
- Data Visualization
- Business Intelligence

---

## 📂 Dataset Description

The dataset contains detailed loan information, including:

- Loan ID
- Loan Amount
- Total Payment Received
- Interest Rate
- Debt-to-Income Ratio (DTI)
- Loan Status (Fully Paid, Current, Charged Off)
- Issue Date
- Loan Term
- Employment Length
- Home Ownership
- Loan Purpose
- Loan Grade
- Address State

---

## 📊 Dashboard Features

### 1. Summary Dashboard

Provides high-level KPI overview:

- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average DTI Ratio
- Good Loan Percentage
- Bad Loan Percentage
- Month-to-Date vs Previous Month Comparison

---

### 2. Overview Dashboard

Provides detailed loan analysis:

#### Monthly Trends
- Loan applications by month
- Funded amount trends
- Payment received trends

#### Regional Analysis
- Loan distribution by state
- Regional performance comparison

#### Loan Term Analysis
- Performance based on loan duration

#### Employment Length Analysis
- Loan distribution by employment length

#### Loan Purpose Analysis
- Most common loan purposes
- Funding by loan purpose

#### Home Ownership Analysis
- Loan distribution by home ownership

---

## 📈 Example SQL Queries Used

### Total Loan Applications
```sql
SELECT COUNT(id) AS Total_Loan_Applications
FROM bank_loan_db.bank_loan_data;
