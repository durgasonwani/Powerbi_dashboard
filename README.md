# Insurance Power BI Dashboard

## Project Overview
This project is an Insurance Data Analysis Dashboard created using Microsoft Power BI.

The dashboard analyzes insurance data such as policy details, premium amount, claim amount, customer information, policy type, and claim status. It helps understand insurance business performance through clear visuals and KPIs.

## Tools Used
- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel

## Dashboard Includes
- Total Policies
- Total Premium Amount
- Total Claim Amount
- Total Customers
- Policy Type Analysis
- Claim Status Analysis
- Customer Analysis
- Premium and Claim Comparison
- Interactive Filters and Slicers

## Data Cleaning
- Removed duplicate records
- Handled missing values
- Changed data types
- Formatted date columns
- Cleaned policy and customer data

## Analysis Performed
- Premium amount analysis by policy type
- Claim amount analysis by insurance category
- Customer analysis by gender and age
- Active, closed, and pending policy analysis
- Claim status comparison
- KPI reporting using DAX measures

## DAX Measures
```DAX
Total Premium Amount = SUM(Insurance[Premium Amount])

Total Claim Amount = SUM(Insurance[Claim Amount])

Total Policies = COUNT(Insurance[Policy Number])

Total Customers = DISTINCTCOUNT(Insurance[Customer Name])
