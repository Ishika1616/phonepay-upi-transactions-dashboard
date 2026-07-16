# PhonePe UPI Transactions Dashboard

## Overview
This project analyzes a year of my personal UPI/PhonePe transaction history 
(Jul 2025 – Jul 2026, 762 transactions) to uncover spending patterns, category 
breakdowns, and behavioral trends. The transaction statement was exported from 
PhonePe as a PDF, converted into structured data, cleaned, categorized, and 
visualized in an interactive Power BI dashboard.

## Tech Stack
- **Data extraction:** PhonePe PDF statement → structured CSV
- **Data cleaning:** Excel (deduplication, merchant name standardization, 
  category correction)
- **Data modeling & visualization:** Power BI Desktop (DAX measures, date 
  table relationships, custom theme)

## Dashboard Features
- KPI cards: Total Spend, Total Received, Transaction Count, Avg Daily Spend
- Monthly spend trend (line chart)
- Spend by category (donut chart)
- Top merchants by spend (bar chart)
- Weekday vs. weekend spend comparison (donut chart)
- Month and transaction-type slicers for interactive filtering

## Key Insights
- Transfers to Friends/Family made up ~38% of total spend, the largest category
- May 2026 was the peak spending month, nearly 4x an average month
- Weekdays outspend weekends overall, but Sunday was the single highest-spending 
  day of the week
- Healthcare spend was minimal, while education-related payments ranked among 
  the largest individual transactions

## Files
- `dashboard/phonepay_transactions.pbix` — Power BI dashboard file
- `data/upi_transactions_categorized.csv` — cleaned transaction dataset
- `screenshots/dashboard_preview.png` — dashboard preview image

## Dashboard Preview
![Dashboard Preview](screenshots/dashboard_preview.png)
