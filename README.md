# 📊 Sales Performance Dashboard (Power BI)

![Dashboard Preview](dashboard_preview.png.jpg)

## 📌 Project Overview
This interactive **Power BI Sales Performance Dashboard** provides a comprehensive view of global revenue, profitability, order volume, and regional trends across multiple product lines. Built as an end-to-end business intelligence solution to help stakeholders track KPIs and identify top-performing markets at a glance.

## 🛠️ Tools & Techniques Used
* **Power Query Editor:** Data cleaning, text standardization (uppercase formatting), data type validation, and custom column creation (`Profit Margin %`).
* **Data Modeling:** Built a **Star Schema (`1:*` One-to-Many)** relationship connecting the `financials` fact table with a custom `Country_Info` regional dimension table.
* **DAX Measures:** Created dynamic KPI measures using `SUM`, `DIVIDE`, and `COUNTROWS` for accurate margin and order tracking.
* **Data Visualization & UX:** Designed an executive-level layout featuring KPI cards, monthly profit trend area charts, comparative country bar charts, and interactive dropdown slicers.

## 💡 Key Business Insights
* **Top Revenue Market:** The **United States** leads overall sales at **$25.03M**, closely followed by **Canada ($24.89M)** and **France ($24.35M)**.
* **Profitability & Volume:** The company generated **$118.73M** in total sales and **$16.89M** in profit across **700** total orders, achieving an overall profit margin of **14.23%**.
* **Seasonal Growth:** Monthly profit trends show strong upward momentum in the final quarter of the year, peaking in **October** and **December**.

## 📂 Files Included
* `Sales_Performance_Dashboard.pbix` — Complete Power BI Desktop report file.
* `dashboard_preview.png.jpg` — High-resolution dashboard overview.
