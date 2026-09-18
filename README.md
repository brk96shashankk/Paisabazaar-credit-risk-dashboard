# Paisabazaar-credit-risk-dashboard
Power BI dashboard analyzing credit risk across 12,500 Paisabazaar customers — score distribution, risk drivers, and behavior trends from 100K monthly records.

## Overview
An interactive Power BI dashboard analyzing credit risk across Paisabazaar's customer base, built to help stakeholders understand how income, debt, payment behavior, and demographics relate to credit-score outcomes.

## Dataset
- **100,000** monthly records across **12,500** unique customers
- **8 months** of observations per customer
- **27** analytical columns covering income, loans, credit cards, payment history, credit mix, and more

## Dashboard Pages
1. **Executive Credit Overview** — portfolio-level KPIs, credit score distribution (Poor/Standard/Good), income and debt comparisons by score, monthly trend, and age-group breakdown
2. **Credit Risk Drivers** — interest rate, credit inquiries, loan count, credit history age by score, plus an income-vs-debt scatter plot and a risk metrics matrix
3. **Customer Behaviour** — payment behavior and credit mix patterns by score, occupation distribution, and monthly balance/EMI trends
4. **Detail Explorer** — a filterable, row-level table for drilling into individual customer-month records

## Key Insights
- 53% of records fall into the "Standard" credit-score band, 29% "Poor," 18% "Good"
- Poor-score customers carry ~2.6x the average outstanding debt of Good-score customers, and pay ~2.6x the interest rate
- Credit mix is the strongest behavioral signal: 60% of customers with a "Bad" credit mix are Poor-score, vs. just 1.5% of those with a "Good" mix
- Score quality improves consistently with age — the 51–60 group is 33% Good-score vs. 11% for the 14–20 group

## Tools Used
Power BI Desktop · DAX · Power Query · Data Visualization

## Files
- `PAISABAZAAR_DASHBOARD.pbix` — the Power BI dashboard file
- `Paisabazaar_Cleaned_Final_Dataset.csv` — the underlying dataset
