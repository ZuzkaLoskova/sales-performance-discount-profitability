
# 📊 Sales Performance & Discount Profitability Analysis

<p align="left">
  <img src="https://img.shields.io/badge/Project-Data%20Analysis-blue?style=for-the-badge&logo=databricks" alt="Data Analysis">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge&logo=checkmarx" alt="Completed">
  <img src="https://img.shields.io/badge/Period-2020--2023-lightgrey?style=for-the-badge" alt="Analysis Period">
</p>

**Tools:** 
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=microsoftsqlserver&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-F2C811?style=flat&logo=powerbi&logoColor=black)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

---


## 📌 1. Project Overview

**Sales Performance & Discount Profitability Analysis** extends the existing Sales Dashboard project with an independent Executive Profitability & Discount Analysis covering 2020–2023.

The project focuses on sales performance, discount profitability and product-level performance. It involves independent data preparation, exploration, validation and analysis, with the findings presented through interactive Power BI visualisations.

The objective is to identify key profitability patterns, evaluate product performance and provide data-driven business recommendations using SQL, Power Query and Power BI.

---



## 🎯 2. Business Objectives

The analysis aims to:

- 📈 **Evaluate Overall Profitability** – assess Total Sales, Total Profit, Profit Margin and Total Orders from 2020 to 2023.
- 💰 **Analyse Discount Impact** – examine how Total Sales, Total Profit and Profit Margin vary across discount levels.
- 📊 **Examine Discount Distribution** – analyse how orders are distributed across individual discount levels.
- 🏷️ **Evaluate Product Profitability** – identify the most and least profitable product categories and subcategories.
- 📅 **Compare Yearly Performance** – identify changes in financial performance and profitability trends over time.
- 💡 **Support Business Decisions** – provide data-driven recommendations for pricing, discount management and product portfolio decisions.

---


## 🛠️ 3. Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Excel – Power Query** | Data cleaning and transformation |
| **SQL Server / SSMS** | Data exploration, validation and quality assessment |
| **Microsoft Power BI** | Data modelling, measure development, analysis and visualisation |

---

## 📂 4. Data Source

The project uses the sales dataset provided by **Data With Baraa** as part of the [Sales Dashboard Project](https://github.com/DataWithBaraa/tableau-ultimate-course/tree/main/04_projects/sales-dashboard-project).

The original dataset served as the foundation for an independent analytical extension, including additional data preparation, SQL analysis and Power BI visualisations.

**Source tables:**
- `Orders` – sales transactions and order-related information.
- `Products` – product details and categorisation.

**Analysis period:** 2020–2023.

---


## ⚙️ 5. Project Workflow

The project followed a structured data analytics workflow:

1. **Data Cleaning & Transformation (Power Query)** – reviewed selected fields, standardised data types and prepared the source tables for analysis.
2. **Data Exploration & Quality Assessment (SQL)** – explored the prepared data and performed data quality checks and validation.
3. **Data Modelling & Measure Development (Power BI)** – resolved 32 repeated Product IDs affecting 64 records in the Products table, established table relationships and developed analytical measures.
4. **Data Analysis & Visualisation (Power BI)** – analysed business performance and developed an interactive dashboard with yearly filtering.

---

## 📊 6. Key Findings

- **Business Growth:** Between 2020 and 2023, Total Sales increased by 51.41%, Total Profit grew by 88.60% and Total Orders increased by 74.10%.
- **Discount Profitability:** Discount levels above 20% consistently generated negative Profit Margins across all four years.
- **Category Performance:** Technology and Office Supplies contributed approximately 93.6% of total profit over the analysed period. Technology achieved the highest Total Profit and Profit Margin in 2023.
- **Subcategory Performance:** Accessories consistently ranked among the top three most profitable subcategories. Copiers became the leading profit contributor in 2022 and 2023.
- **Profitability Issues:** Tables ranked as the least profitable subcategory in every analysed year, recording a loss of $8,140.69 in 2023.
- **Profit Margin Trend:** Overall Profit Margin peaked at 13.43% in 2022 before declining to 12.74% in 2023.
---

## 💡 7. Business Recommendations

- **Discount Strategy:** Strengthen discount controls, particularly for discounts above 20%.
- **Category Profitability:** Review Furniture profitability and prioritise Technology and Office Supplies.
- **Product Portfolio:** Address recurring losses in Tables while monitoring leading subcategories such as Accessories, Copiers and Phones.
- **Performance Monitoring:** Track Total Sales, Total Profit, Profit Margin and Total Orders together to support sustainable business performance.

---
## 📁 8. Project Files & Structure

The repository is organised into the following directories:

```text
sales-performance-discount-profitability/
│
├── data/
│   ├── raw/
│   │   ├── orders_raw.csv
│   │   └── products_raw.csv
│   │
│   └── processed/
│       ├── orders_processed.csv
│       └── products_processed.csv
│
├── outcomes/
│   ├── final_report.docx
│   └── final_report.pdf
│
├── powerbi/
│   ├── Dashboard_2020.png
│   ├── Dashboard_2021.png
│   ├── Dashboard_2022.png
│   ├── Dashboard_2023.png
│   └── dashboard_interactivity_demo.mp4
│
├── queries/
│   └── queries.sql
│
├── .gitignore
└── README.md
```

### 📂 Directory Description

| Directory / File | Description |
|---|---|
| `data/raw/` | Original source datasets (`Orders` and `Products`). |
| `data/processed/` | Cleaned and transformed datasets prepared for analysis. |
| `outcomes/` | Final analytical report in DOCX and PDF formats. |
| `powerbi/` | Yearly dashboard screenshots and an interactive dashboard demonstration video. |
| `queries/` | SQL queries used for data exploration, validation and analysis. |
| `.gitignore` | Specifies files and directories excluded from Git tracking. |
| `README.md` | Project documentation and overview. |





