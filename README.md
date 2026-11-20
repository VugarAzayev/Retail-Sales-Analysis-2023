# 2023 Retail Sales Analysis (Excel)

Analysis of 998 retail sales transactions from 2023 using Excel (`SUMIFS`, `COUNTIFS`, `UNIQUE`).

> Note: The `Data` sheet contains 1,000 rows, but 2 transactions are dated 2024-01-01. All analysis is filtered to `<202401`, so it covers 998 transactions in 2023.

## Key Highlights

- **Total Revenue:** 454,470 | **Transactions:** 998 | **Avg Check:** 455.38 (Median: 135) | **Units Sold:** 2,510
- **Pareto Effect:** Prices 300 and 500 represent 39.6% of transactions (395) but drive 88.3% of revenue (401,400).
- **Categories:** Electronics 156,875 (34.5%) | Clothing 155,580 (34.2%) | Beauty 142,015 (31.2%). No category dominates.
- **Timing & Segments:** Peak month is May (53,150), lowest is September (23,620). Saturday leads in revenue (78,815) and average check (525.43). Age 46-55 generates the highest total revenue (100,660), while 18-25 has the highest average check (500.30).

## What I Found

- Cheap products (25 / 30 / 50) bring traffic: 60.4% of transactions, but only 11.7% of revenue.
- Expensive products (300 / 500) bring money: 39.6% of transactions, but 88.3% of revenue.
- Gender gap is small: Female 232,840 (510 transactions) vs Male 221,630 (488 transactions).
- Focus campaigns on May and Saturday, use promotions to boost September and Thursday.

## File Included

- `Retail_Sales_Analysis_2023.xlsx`
    - `Data` - 1,000 raw transactions (Transaction ID, Date, Customer, Gender, Age, Category, Quantity, Price, Total Amount)
    - `Analysis` - all calculations with live Excel formulas (`SUMIFS`, `COUNTIFS`, `SUMIF`, `UNIQUE`)
    - `Dashboard` - KPI cards + 6 charts
    - `Insights` - key findings and recommendations

## How to Use

1. Open `Retail_Sales_Analysis_2023.xlsx`
2. Start with `Dashboard` for the overview
3. Check `Analysis` to see how every number is calculated
4. Read `Insights` for findings and recommendations

## Data Source

Retail Sales Dataset (Kaggle) - 2023 transactions.
