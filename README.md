# Power BI - Handwritten Notes ✍️

This repository contains my personal handwritten notes on Power BI, including:

- 📊 Types of Visuals (Bar chart, Pie chart, TreeMap, etc.)
- 🔧 Power Query Editor (Steps, Merging, Cleaning data)
- 📐 DAX Formulas (Calculated Columns, Measures, Functions)

## Folder Structure

- `visuals/` – Notes related to Power BI visuals
- `power_query_editor/` – Power Query transformation steps
- `dax/` – Notes on DAX expressions and logic

## 🚫 What’s Not Included

- Join concepts during merge (assumed known via SQL)
- Data type handling (too basic to include)
- Full dashboards or sample datasets

Feel free to explore and use for your learning!

---

## 📌 Quick Reference: Joins & Data Types

### 🔗 Merge Join Types in Power Query

| Join Type       | Description                                       |
|------------------|---------------------------------------------------|
| **Inner Join**   | Returns only matching rows from both tables       |
| **Left Outer**   | All rows from first (left) table, with matches    |
| **Right Outer**  | All rows from second (right) table, with matches |
| **Full Outer**   | All rows from both tables, matched where possible |
| **Anti Joins**   | Return non-matching rows (Left/Right Anti)        |

> 🛠️ Use: `Home → Merge Queries → Choose Join Kind`  
> ✅ Follows SQL join logic

---

### 🔢 Common Data Types in Power BI

| Data Type     | Used For                            |
|----------------|--------------------------------------|
| **Text**        | Names, IDs, categories               |
| **Whole Number**| Counts, rankings                     |
| **Decimal**     | Prices, averages, percentages        |
| **Date/DateTime**| Calendar-based filtering            |
| **Boolean**     | Logical filtering (True/False)       |
| **Currency**    | Formatted monetary values            |

> 🛠️ Use: `Transform → Data Type` or right-click column → `Change Type`  
> ⚠️ Incorrect types can affect merges, DAX, and visuals
