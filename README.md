# Business Insights 360 🚀📊

Power BI analytics project for **AtliQ Hardware**, a fictional consumer electronics company, to enable data-driven decision-making using modern BI tools and techniques.

---

## 📌 Problem Statement

**AtliQ Hardware** is a fast-growing electronics company based in India, with operations in multiple countries. Despite their rapid growth, they relied heavily on Excel for data analysis, which proved inefficient, error-prone, and incapable of generating actionable insights.

Due to the lack of effective analytics, the company suffered major losses in the Latin America region. To address this, the senior leadership initiated a business intelligence project to build insightful dashboards using **Power BI** for better strategic decisions.

---

## 🛠️ Technologies Used

- **SQL** – For data extraction and transformation  
- **Excel** – For additional datasets like market targets and shares  
- **Power BI** – For report and dashboard development  
- **DAX Language** – For data modeling and calculations  
- **DAX Studio** – For performance tuning and optimization  

---

## 🗃️ Data Sources

### 📁 SQL Databases

**gdb041**
- `dim_customer` – Customer details  
- `dim_market` – Market and country-level info  
- `dim_product` – Product details  
- `fact_sales_monthly` – Monthly sales quantity  
- `fact_forecast_monthly` – Monthly forecasted quantity  

**gdb056**
- `freight_cost` – Freight and other logistics costs  
- `gross_price` – Gross price by product  
- `manufacturing_cost` – Product manufacturing costs  
- `pre_invoice_deductions` – Discounts before invoice  
- `post_invoice_deductions` – Post-invoice and other discounts  

### 📁 Excel Workbooks

- `targets` – Contains net sales, gross margin, and net profit targets by market  
- `marketshare` – Contains AtliQ’s and competitors' market share data  

---

## 🧩 Data Model

- **Model Type**: Snowflake schema  
- **Entity Relationship Diagram**:  
  ![Data Model](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Data%20Model.png)

---

## 📊 Dashboards Overview

All dashboards are built within Power BI and navigated via a centralized **Home View**.  

### 1. 🏠 Home View
Navigation panel for different views with interactive buttons:
- Finance View  
- Sales View  
- Marketing View  
- Supply Chain View  
- Executive View  
- Support

![Home View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Home%20View.gif)

---

### 2. 💰 Finance View
- Full profit and loss statement  
- Track performance over time across customers, products, and markets  
- Designed to support financial analysis  

![Finance View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Finance%20View.gif)

---

### 3. 📈 Sales View
- Key metrics: Net Sales, Gross Margin, Gross Margin %  
- Evaluate customer performance  

![Sales View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Sales%20View.gif)

---

### 4. 🎯 Marketing View
- Key metrics: Net Sales, Gross Margin %, Net Profit, Net Profit %  
- Focuses on product-level performance  

![Marketing View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Marketing%20View.gif)

---

### 5. 🚚 Supply Chain View
- Forecast accuracy, net errors  
- Customer & product-wise analysis against last year  
- Helps identify gaps in planning and delivery  

![Supply Chain View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Supply%20Chain%20View.gif)

---

### 6. 🧑‍💼 Executive View
- Consolidated key KPIs  
- Market share insights  
- High-level dashboard for company executives  

![Executive View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Executive%20View.gif)

---

## ✅ Project Outcome

This project empowers **AtliQ Hardware** to:

- Replace fragmented Excel-based reporting with unified, interactive dashboards  
- Gain faster and deeper insights across departments: Finance, Sales, Marketing, and Supply Chain  
- Improve **forecasting accuracy** and **cost control**  
- Identify underperforming regions and customers  
- Track progress against strategic targets  
- Make **data-driven decisions** to fuel international growth  
- Enable executives to make **confident strategic moves** with real-time analytics  

---
