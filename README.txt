# Superstore Data Analysis - README

## 📁 Project Overview
This project involves cleaning and analyzing the 'Sample - Superstore' dataset for use in a Power BI dashboard. The goal is to extract key business insights and create a structured, analysis-ready file.

---

## ✅ Steps Performed

1. **Loaded Dataset**: 'Sample - Superstore.csv' was loaded using proper encoding (ISO-8859-1).
2. **Data Cleaning**: used python to clean the data.
   - Converted 'Order Date' and 'Ship Date' columns to datetime format.
   - Removed duplicate rows.
   - Stripped whitespace from all text columns.
   - Dropped unnecessary columns like 'Row ID'.
3. **Saved Cleaned Data**: Exported to Excel as 'Cleaned_Superstore.xlsx'.
4. **Generated KPIs**: Created DAX measures like Profit Margin and Average Shipping Time.
5. **Extracted Insights**: Wrote 5 short insights summarizing trends in sales, shipping, and customer behavior.

---

## 📎 Files Included

- `Sample - Superstore.csv` — Original raw dataset.
- `Cleaned_Superstore.xlsx` — Cleaned version ready for Power BI.
- `Superstore_Insights.txt` — 5 short business insights for presentation.
- `README.txt` — This file, describing the project scope and contents.
- `Sales_Dashboard.png` - Screenshot of Dashboard.
---

## 📊 Use in Power BI

You can import `Cleaned_Superstore.xlsx` into Power BI and use the DAX measures provided in this project for KPIs like:
- Total Sales
- Total Profit
- Profit Margin (%)
- Average Order Value
- Average Shipping Time
---

This project is licensed under the MIT License.
---