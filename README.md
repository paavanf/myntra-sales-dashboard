# Myntra Sales Dashboard

An interactive two-page Power BI dashboard that turns raw Myntra order data into actionable business insight — covering brand performance, customer behaviour, regional demand and discount effectiveness.

## Overview

Built in Microsoft Power BI Desktop on the Kaggle Myntra dataset. The report is organised across two pages with shared slicers (Year, Brand, Sub-category, Category) that synchronise filters across the full report.

- **Page 1 — Executive Summary** answers *what is selling*
- **Page 2 — Detailed Insights** answers *who is buying and how*

Coverage: 3,500 orders across 3,071 products and 100 customers, spanning 2023–2025.

## Tech Stack

Power BI Desktop · DAX · Power Query (M) · Microsoft Excel · Star-Schema Data Model

## Key Features

- Six headline KPIs — Total Orders, Total Sales, Total Revenue, Avg Sales Amount, Avg Discount, Total Products
- Brand leaderboard, category donut and product-mix analysis
- State-wise revenue stacked by category
- Time-series trends by day, month and quarter
- Customer KPIs — AOV, Revenue per Customer, age-group and city breakdowns
- Discount-bracket effectiveness chart revealing the optimal discount zone
- Cross-page filter synchronisation

## Key Insights

| Metric | Value |
|---|---|
| Total Orders | 3,500 |
| Total Sales | ₹26.9 L |
| Avg Order Value | ₹770 |
| Avg Discount | 31.6% |
| Revenue per Customer | ₹26.9 K |
| Top State | Punjab |
| Top Brand | H&M |

- Optimal discount zone is 20%–40% — order volume peaks in this bracket
- Punjab and Uttar Pradesh lead revenue, ahead of traditional markets
- 26–35 age group accounts for nearly half of all customers

## How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Repoint the data source to the bundled `Myntra_dataset.xlsx` if prompted
4. Interact with the slicers to filter both pages

## Future Improvements

- Sales forecasting with Power BI built-in or Python scripts
- RFM-based customer segmentation (Recency-Frequency-Monetary)
- Drill-through pages for each brand and customer
- Row-Level Security for state-wise access control
- Live data connection with scheduled refresh

## Acknowledgment

Dataset sourced from Kaggle and used for academic and learning purposes.

## Author

**Paavan Fatepuria**
