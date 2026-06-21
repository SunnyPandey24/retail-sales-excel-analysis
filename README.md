# Retail Sales & Operations Analysis (Excel Project)

End-to-end Excel analytics project: raw messy transactional data → cleaned & validated dataset → pivot-style analysis → KPI dashboard with charts → written business recommendations. Built to demonstrate real-world data cleaning and analyst skills, not just chart-making.

## Problem Statement
A retail business logs sales transactions with no standardized process — inconsistent date formats, inconsistent text casing/spacing, missing discount/sales values, and duplicate entries. This project cleans that data and turns it into an executive-ready dashboard with actionable recommendations.

## What's Inside (`Retail_Sales_Analysis.xlsx`)

| Sheet | Purpose |
|---|---|
| **Dashboard** | KPI cards (Revenue, Profit, Orders, AOV) + 4 charts: Sales by Region, Revenue Share by Category, Monthly Trend, Top 10 Products |
| **Raw_Data** | 468 untouched transaction records exactly as "logged" — includes 2 mixed date formats, inconsistent text casing/spacing, missing values, and 18 duplicate rows |
| **Cleaned_Data** | Every field rebuilt with formulas (`TRIM`, `PROPER`, `DATEVALUE`) — duplicates excluded, Sales/Profit recalculated from source fields rather than trusted blindly |
| **Analysis** | Pivot-style summary tables (Region, Category, Monthly Trend, Top 10 Products) built entirely with `SUMIF`/`COUNTIF` — no hardcoded numbers |
| **Summary_Recommendations** | Dynamic, formula-driven insights (`INDEX`/`MATCH`) plus written business recommendations and a methodology note |

## Skills Demonstrated
- Data cleaning with formulas (TRIM, PROPER, DATEVALUE, IFERROR)
- Duplicate identification and handling
- Pivot-style aggregation (SUMIF, COUNTIF) across multiple dimensions
- KPI design and dashboard layout
- Chart selection (bar, pie, line) matched to the question being answered
- Dynamic, self-updating insights using INDEX/MATCH instead of hardcoded text
- Business communication — translating numbers into recommendations

## How to Use
1. Open `Retail_Sales_Analysis.xlsx` in Excel.
2. Start on the **Dashboard** tab for the high-level view.
3. Drill into **Analysis** for the underlying SUMIF/COUNTIF tables.
4. Check **Cleaned_Data** to see exactly how raw data was transformed.
5. Read **Summary_Recommendations** for the business takeaways.

To extend with new data: paste new rows into `Raw_Data`, extend the formulas down a few rows in `Cleaned_Data`, and every table and chart recalculates automatically.

## Tools
Microsoft Excel — formulas, SUMIF/COUNTIF pivot tables, native charts, KPI dashboard design.
<img width="1356" height="665" alt="Screenshot 2026-06-21 135459" src="https://github.com/user-attachments/assets/fe4b02f5-2f3c-4853-afcd-acd52636512b" />
<img width="1822" height="451" alt="Screenshot 2026-06-21 135443" src="https://github.com/user-attachments/assets/ea121418-caef-4550-acda-b72f10497885" />
<img width="1821" height="656" alt="Screenshot 2026-06-21 135322" src="https://github.com/user-attachments/assets/af20f9b7-eb43-4a4a-873e-5b508760d90f" />
<img width="720" height="662" alt="Screenshot 2026-06-21 135306" src="https://github.com/user-attachments/assets/282224e3-8eb6-46b4-9ec3-a41afd5d4943" />
<img width="1091" height="722" alt="Screenshot 2026-06-21 135245" src="https://github.com/user-attachments/assets/b6d4042f-0073-4083-95df-201ddd8b4002" />
