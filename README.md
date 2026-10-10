# Loan Default Risk Analysis (Power BI)

## Overview
Analysis of 255K+ loan records to find which borrower and loan characteristics drive default.
Overall default rate: 11.6%.

## Tools
Power BI, DAX, MS SQL Server, Power BI Dataflows, Excel

## Pipeline
Excel/CSV → MS SQL Server → Power BI Dataflow → Power BI dashboard

## Dashboard pages
1. Loan Default & Overview
2. Default Risk Drivers
3. Applicant Demographics & Financial Profile
4. Financial Risk Metrics
5. Insights and Recommendations

## Key findings
- Default rate is 21.0% for ages 18-24 vs 4.9% for ages 65-69.
- Lowest income quartile defaults at 17.4% vs 9.0% for the highest.
- Default rises from 6.6% to 18.8% across interest-rate bands.
- Ages 18-34 are 33% of loans but 52% of defaults.

## Recommendations
- Stricter checks (co-signer, income verification) for young applicants
- Weight income and job tenure more heavily
- Review pricing for high-risk borrowers

## DAX measures
Default Rate %, Share of Loans %, Share of Defaults %, Risk Lift, etc (each validated
against source data).

## Limitations
- Dataset appears synthetic (interest rate is unrelated to credit score, income or age).
- Findings show association, not causation.
