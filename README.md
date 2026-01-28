# Walmart Sales Executive Analysis

## 📝 Project Overview
This project focuses on a comprehensive analysis of Walmart's sales data, transforming raw transactional records into actionable business insights. The analysis identifies key performance drivers, store efficiency, and departmental contributions to support strategic decision-making.

## 🛠️ Tools & Methodology
The analysis was performed entirely within **Microsoft Excel**, utilizing professional data workflows:
* **Data Cleaning & ETL:** Performed in Power Query/Excel to standardize dates, merge store/department catalogs, and handle missing values.
* **Data Modeling:** Enriched datasets with calculated columns for week-over-week comparisons and efficiency metrics.
* **Analytical Engine:** Used Pivot Tables to aggregate large volumes of data (over 400,000 rows) into summarized KPIs.
* **Visual Communication:** Designed an interactive Dashboard with slicers for dynamic filtering by department and time period.

## 📊 Key Performance Indicators (KPIs)
The report tracks three primary metrics:
1. **Sales per Sq. Meter:** Measures store efficiency by normalizing sales against the physical footprint.
2. **Participation %:** Evaluates the weight of each department relative to total company revenue.
3. **Weekly Trends:** Monitors sales fluctuations to identify seasonal patterns and holiday impacts.

## 📂 Project Structure
* `/data`: Contains raw source files (`ventas`, `tiendas`, `departamentos`).
* `Walmart_Sales_Analysis.xlsx`: The main workbook containing:
    * `clean_ventas`: The processed and merged dataset.
    * `Pivot`: The calculation engine for the report.
    * `Dashboard`: Interactive visual interface.
    * `Summary`: Executive report with key findings.
* `README.md`: Project documentation.

## 💡 Key Insights
* **Efficiency Leader:** The "Pantry & Basics" department was identified as the most efficient, yielding **$652.81 per m²**.
* **Revenue Drivers:** "Fresh Food" and "Household Goods" are the top contributors, representing over **20%** of total business volume.
* **Data Integrity:** Identified a **4.79%** "Undefined" sales category, highlighting an opportunity for better data classification at the source to improve future reporting accuracy.

## 📸 Dashboard Preview
*(Insert a screenshot of your Excel Dashboard here to showcase your work visually)*
![Dashboard Screenshot](img/dashboard_preview.png)

---
*Developed as part of a Business Intelligence Portfolio Project.*
