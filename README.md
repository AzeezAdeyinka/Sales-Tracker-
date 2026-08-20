# Sales-Tracker-
An end-to-end sales performance tracker and dashboard built entirely in Microsoft Excel, It is designed to give a business owner a live, at-a-glance view of revenue, orders, outstanding payments, and top performers without needing any external BI tool.
![Dashboard Preview](Sales_Tracker_Excel_Application.png)

## What it does

- **Automated KPI Dashboard** — Total Revenue, Total Orders, Outstanding Payments, and Top Product update live from the Sales Log with zero manual entry.
- **Trend visualization** — Monthly revenue trend chart and revenue-by-salesperson chart, both dynamically fed from the transaction log.
- **Product Search sheet** — Look up any product's performance using `AGGREGATE` + `INDEX` formulas with partial-match search (type part of a name, get every matching result).
- **Sales Log** — The single source of truth: every transaction (date, customer, product, quantity, price, payment status) feeds the rest of the workbook.
- **Lookup & ChartData sheets** — Clean helper tables that keep the dashboard formulas fast and the chart data properly shaped, instead of charting messy raw data directly.
- Currency formatted in **Naira (₦)** with **DD/MM/YYYY** date formatting, built for the Nigerian small-business market — easy to re-key for any other currency/locale.

## Sheets

| Sheet | Purpose |
|---|---|
| `Dashboard` | KPI cards + charts, all formula-driven |
| `Sales Log` | Raw transaction entry point |
| `Product Search` | Partial-match product lookup tool |
| `Lookup` | Reference/validation tables |
| `ChartData` | Pre-aggregated data that feeds the dashboard charts |

## Skills demonstrated

Excel formulas (`SUMIFS`, `COUNTIFS`, `AGGREGATE`, `INDEX`/`MATCH`), pivot-style KPI design without pivot tables, chart automation, data validation, conditional formatting, and dashboard/UX layout for non-technical end users.


---
Built by **Azeez Adeyinka Idowu** — Data Analyst | [Portfolio](https://azeezadeyinka.github.io/) | [LinkedIn](https://www.linkedin.com/in/azeez-adeyinka-idowu/)
