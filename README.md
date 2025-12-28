# 📊 Superstore Sales Analysis using SQL

## 📌 Project Overview
This project is an **end to end SQL data analysis** performed on the **Superstore Sales Dataset** to extract meaningful business insights related to **sales performance, profitability, customer behavior, product performance, and operational efficiency**.

The analysis focuses on answering **real world business questions** using SQL and presenting insights that can support **data driven decision making**.

---

## 🎯 Objectives
- Analyze overall **sales and profit performance**
- Identify **high performing and loss making products**
- Evaluate **regional and customer level profitability**
- Study the impact of **discounts on profit margins**
- Understand **order and shipping behavior**
- Apply **advanced SQL concepts** such as window functions

---

## 🗂️ Dataset Information
- **Dataset:** Superstore Sales Dataset  
- **Format:** Excel (`.xlsx`)
- **Key Tables Used:**
  - `Orders`
  - `Returns`

### Key Columns:
`Order Date`, `Ship Date`, `Sales`, `Profit`, `Discount`, `Quantity`,  
`Category`, `Sub-Category`, `Product Name`,  
`Customer Name`, `Segment`, `Region`, `State`, `Ship Mode`

---

## 📁 Repository Structure
```
superstore-sql-sales-analysis/
│
├── data/
│   └── superstore_dataset.xlsx
│
├── presentation/
│   └── superstore_sql_analysis_presentation.pptx
│
├── report/
│   └── superstore_sql_analysis_report.docx
│
├── sql/
│   └── superstore_sql_analysis.sql
│
├── visuals/
│   └── query_results/
│       ├── p1_total_sales.png
│       ├── p2_profit_by_category.png
│       └── ...
│
└── README.md

```

---

## 📊 Key KPIs Analyzed
- Total Sales  
- Total Profit  
- Profit Margin (%)  
- Return Rate  
- Average Discount  
- Average Order Value (AOV)  
- Average Shipping Time  

---

## 🔍 Analysis Performed

### 🟦 Sales Performance Analysis
- Total Sales & Total Profit
- Profit Margin (%)
- Yearly & Monthly Sales and Profit Trends
- Top 10 Products by Sales
- High Sales but Negative Profit Products

### 🟦 Regional & Location Analysis
- Sales & Profit by Region
- Top 5 and Bottom 5 States by Profit
- Regions with High Discounts but Low Profit

### 🟦 Customer Analysis
- Average Order Value (AOV)
- Sales & Profit by Customer Segment
- Top 10 Customers by Profit
- Customers with High Sales but Loss

### 🟦 Product & Category Profitability
- Loss making SubCategories
- High Discount – Low Profit Products
- Quantity vs Profit Analysis
- Profit Margin by Discount Level

### 🟦 Order & Shipping Analysis
- Average Shipping Time
- Orders by Shipping Mode
- Profit by Shipping Mode

### 🟦 Advanced SQL (Window Functions)
- Product Ranking by Profit within Category
- Month over Month (MoM) Sales Growth using `LAG()`

---

## 🛠️ SQL Concepts & Skills Used
- Aggregate Functions (`SUM`, `AVG`, `COUNT`)
- `GROUP BY`, `HAVING`, `ORDER BY`
- `JOIN` (Orders & Returns)
- Date Functions (`YEAR`, `MONTH`, `DATEDIFF`)
- Common Table Expressions (CTEs)
- Window Functions (`RANK`, `LAG`)
- Business KPI Calculations

---

## 📈 Key Insights (Sample)
- Certain products generate **high revenue but cause losses due to heavy discounts**
- Some regions show **high average discounts with low profitability**
- **Standard shipping mode** contributes significantly to overall profit
- Profit margins decline sharply beyond specific discount thresholds
- Clear seasonal trends observed in monthly sales performance

---

## 🚀 Tools & Technologies
- **SQL** (Microsoft SQL Server)
- **Microsoft Excel** (Dataset)
- **PowerPoint** (Business Presentation)
- **GitHub** (Version Control & Portfolio)

---

## 📌 How to Use This Project
1. Download the dataset from the `data/` folder  
2. Import it into your SQL environment  
3. Run queries from `sql/superstore_sql_analysis.sql`  
4. Refer to:
   - `visuals/` for query output screenshots  
   - `report/` for detailed explanations  
   - `presentation/` for executive-level insights  

---

## 👤 Author
**MIT TRIVEDI**  
Data science Professional  
📧 Email: trivedimit04@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mit-trivedi-8714a5344/)  
🔗 [Portfolio](https://github.com/trivedimit/) 


---


