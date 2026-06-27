# Customer Churn Risk Analysis (Excel + Power BI)

This project analyzes telecom customer churn using Excel and Power BI to identify customer behaviors associated with retention risk.

The analysis connects churn outcomes to business drivers such as contract renewal, support call frequency, tenure, and service usage. Instead of only reporting churn rate, this project frames churn as a customer retention problem where behavioral signals can be used to identify high-risk segments and guide retention strategy.

## Dashboard Preview

![Customer Churn Dashboard](screenshot/churn_dashboard.png)

## Business Questions

- What percentage of customers churn?
- Does contract renewal reduce churn risk?
- Do frequent support calls signal higher customer dissatisfaction?
- Which customer segments are most likely to churn?
- What retention actions could reduce preventable churn?

## Business Process

Customer Account → Service Usage → Support Experience → Contract Renewal → Retention / Churn

## KPI Framework

| Business Area | Outcome KPI | Driver KPIs / Segments |
|---|---|---|
| Customer Retention | Churn Rate | Total Customers, Total Churned, Contract Renewal Status |
| Support Experience | Churn Risk by Support Calls | Customer Service Calls, Support Call Group |
| Customer Lifecycle | Tenure-Based Churn | Account Weeks, Tenure Group |
| Usage & Value | Behavioral Risk Signals | Monthly Charge, Data Usage, Overage Fee |

## Project Workflow

- Prepared telecom customer data in Excel.
- Created customer segments for support call frequency and tenure.
- Built churn rate calculations and customer risk indicators.
- Designed a Power BI dashboard to compare churn behavior across contract status, tenure, and support call groups.
- Used the analysis to identify customer segments that may need targeted retention outreach.

## Key Findings

- Overall churn rate was 14.49%.
- Customers without contract renewal churned nearly four times more often than customers who renewed.
- Churn risk increased sharply after three or more support calls.
- Customers with six or more support calls showed churn rates above 60%.
- Shorter-tenure customers showed slightly higher churn risk.

## Tools Used

- Excel
- Power BI
- DAX
- Data Preparation
- Customer Segmentation
- KPI Development
- Churn Analysis
- Retention Analysis

## Repository Structure

```text
dashboard/
data/
screenshot/
README.md
```

## Full Portfolio Walkthrough

A deeper project walkthrough is available in my Notion portfolio, including the business process, KPI framework, dashboard analysis, customer risk logic, and retention recommendations.
