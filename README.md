# 📊 Global Sales & Logistics Performance Dashboard (Power BI)
![Global Sales & Logistics Performance Dashboard](https://github.com/tharannum/Global-Sales-Logistics-Performance/blob/main/Global%20Sales%20%26%20Logistics%20Performance%20Dashboard.png)
## Executive Summary  

Global sales and logistics operations generate large volumes of transactional, financial, and operational data across products, shipping modes, and geographic regions. However, without structured analytics, organizations struggle to understand revenue drivers, profit margins, and logistics cost efficiency.  

This Business Intelligence project analyzes global sales and logistics performance data using **Power BI** to uncover insights across revenue, profit, product performance, logistics costs, and regional trends.  

The goal is to provide **data-driven visibility into business performance and supply chain efficiency**, enabling stakeholders to optimize pricing, logistics strategies, and regional sales planning.  

The analysis includes:  

- Sales Performance Analysis: Total revenue, profit, and profit margin trends  
- Product-Level Insights: Sales and profit by product category  
- Logistics Cost Impact: Understanding how shipping costs affect profitability  
- Shipping Mode Analysis: Cost distribution across shipping methods  
- Time-Based Trends: Monthly revenue and profit performance  
- Geographic Performance: Regional revenue and profit visualization  

An interactive **Power BI dashboard** has been built to visualize these insights and support strategic business decisions for sales, supply chain, and leadership teams.  

---

## 🌍 Overall Performance Dashboard  

The Global Sales & Logistics Performance Dashboard provides a high-level overview of key business metrics in a single view.  

It enables stakeholders to quickly understand:  

- Total Sales: 240M  
- Total Profit: 51M  
- Profit Margin: 0.21  
- Total Logistics Cost: 13M  
- Product-wise revenue distribution  
- Monthly performance trends  
- Regional revenue and profit contribution  

📌 **Power BI Dashboard Link:**  
(Add your Power BI Service / PDF / Portfolio link here)

---

## 🗂️ 1. Project Overview  

The purpose of this project is to transform raw global sales and logistics data into a structured, interactive BI dashboard that answers critical business questions such as:  

- How are sales and profits performing across products and regions?  
- Which products generate the highest revenue and profit?  
- How do logistics costs impact overall profitability?  
- Which shipping modes are the most cost-effective?  
- How does performance change month over month?  
- Which regions contribute the most revenue and profit?  

This dashboard helps both technical and non-technical users explore KPIs, identify inefficiencies, and make informed decisions.  

---

## 🗃️ 2. Data Description  

### Dataset Source  
The dataset was provided in structured Excel/CSV format containing global sales, logistics, and financial records.  

### Included Fields  

**Sales Data:**  
- Product Name  
- Revenue  
- Profit  
- Profit Margin %  

**Logistics Data:**  
- Shipping Mode  
- Logistics Cost  

**Time Data:**  
- Month  
- Year  

**Geographic Data:**  
- Region  
- Country  

---

## 🔧 Data Preparation (Power Query)  

The following transformations were performed:  

- Removed duplicates and null values  
- Standardized numeric and currency formats  
- Created calculated columns for Profit Margin and Month-Year  
- Categorized products  
- Cleaned shipping mode categories  
- Created region mapping for geographic visualization  

---

## ⭐ Data Model (Star Schema)  

**Fact Table:**  
- Fact_Sales_Logistics  

**Dimension Tables:**  
- Dim_Product  
- Dim_Date  
- Dim_Region  
- Dim_ShippingMode  

Relationships were created using primary and foreign keys such as product_id, date_id, and region_id.  

---

## 📈 3. Analysis Performed  

### Power Query Transformations  
- Data cleaning and reshaping  
- Creating Month, Quarter, and Year columns  
- Logistics cost categorization  

### DAX Measures  
- Total Sales  
- Total Profit  
- Profit Margin %  
- Total Logistics Cost  
- Monthly Revenue & Profit  
- Product-wise Sales Contribution  
- Regional Revenue & Profit  
- Shipping Mode Cost Share  

---

## 📊 Visualizations  

- KPI Cards (Total Sales, Profit, Profit Margin %, Logistics Cost)  
- Bar Chart (Revenue by Product)  
- Combined Bar Chart (Sales vs Profit by Product)  
- Logistics Impact Analysis  
- Pie Chart (Logistics Cost Distribution by Shipping Mode)  
- Line Chart (Monthly Sales & Profit Trends)  
- Map Visualization (Revenue and Profit by Region)  
- Slicers (Product Category, Date, Region)  

---

## ❓ 4. Business Questions Answered  

- What is the total global sales and profit?  
- Which products generate the highest revenue?  
- How much logistics cost is incurred, and how does it affect profit?  
- Which shipping mode contributes the most logistics cost?  
- How do monthly sales and profit trends change over time?  
- Which regions contribute the most revenue and profit?  

---

## 🔍 5. Insights & Interpretation  

### Insight 1 — Base Oil is the Top Revenue Driver  
Base Oil contributes the highest revenue (~72M), followed by HSFO and MGO, indicating strong market demand.  

### Insight 2 — Profit Margin Pressure  
Overall profit margin is relatively low, suggesting high operational and logistics costs impacting profitability.  

### Insight 3 — Logistics Cost Impact  
Total logistics cost (13M) significantly affects profit, making supply chain optimization essential.  

### Insight 4 — Shipping Mode Cost Distribution  
Certain shipping modes contribute disproportionately to logistics costs, creating opportunities for cost reduction strategies.  

### Insight 5 — Monthly Performance Fluctuation  
Sales and profit trends show seasonal variation, highlighting forecasting and demand planning opportunities.  

### Insight 6 — Regional Revenue Concentration  
Revenue is concentrated in specific global regions, indicating expansion opportunities in emerging markets.  

---

## 📌 6. Recommendations  

### Sales Team  
- Focus on high-performing products  
- Improve pricing strategies to enhance margins  

### Supply Chain Team  
- Optimize shipping modes to reduce logistics costs  
- Improve route planning and freight negotiations  

### Marketing Team  
- Target high-growth regions  
- Support underperforming products with campaigns  

### Leadership  
- Set KPIs for logistics cost reduction  
- Invest in predictive analytics for demand forecasting  

---

## 🛠️ 7. Skills Used  

- Power BI Desktop  
- Power Query (M Language)  
- DAX (Time Intelligence, KPI Measures)  
- Data Modeling (Star Schema)  
- Data Cleaning & Transformation  
- Business Intelligence Reporting  
- Data Visualization  
- Analytical Storytelling  

---

## 🏁 8. Project Outcome  

This project delivers:  

- A fully interactive Global Sales & Logistics Performance Dashboard  
- Cleaned and structured dataset with a star schema model  
- DAX-driven KPIs and insights  
- Actionable business recommendations  
- A professional BI portfolio project  

This dashboard enables organizations to optimize sales strategy, reduce logistics costs, and improve global profitability using data-driven decision-making.

---

## 📷 Dashboard Preview  

![Global Sales & Logistics Performance Dashboard](https://github.com/tharannum/Global-Sales-Logistics-Performance/blob/main/Global%20Sales%20%26%20Logistics%20Performance%20Dashboard.png)
