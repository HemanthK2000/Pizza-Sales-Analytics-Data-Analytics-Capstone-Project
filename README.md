# 🍕 Pizza Sales Analytics – Data Analytics Capstone Project

A complete end-to-end Data Analytics Capstone Project analyzing pizza store sales using **Excel, SQL, Python, Tableau, and Power BI**.  
This project focuses on extracting business insights, KPIs, trends, and visual dashboards to support data-driven decision-making for sales, marketing, and operations.

---

## 📌 Project Objective
To analyze transactional pizza sales data and deliver:
- Overall revenue, total pizzas sold, and total number of orders.
- Determine sales distribution by pizza category, size, and type.
- Analyse time-based trends in sales (daily, monthly, and yearly).
- Highlight best-selling and least-selling pizzas by revenue and quantity.
- Understand customer purchasing behaviour through Average Order Value (AOV) and Average Pizza per Order.
- Provide visualization dashboards for effective decision-making.

---

## 🛠 Tools & Technologies
| Tool | Purpose |
|------|---------|
| Excel | Data Cleaning, Pivot Tables, Exploratory Analysis |
| SQL Server | Data Extraction, KPI Calculation, Trend Queries |
| Python (Pandas, Matplotlib, Seaborn) | Data Analysis & Visualization |
| Tableau | Interactive Dashboards |
| Power BI | Business Intelligence Reports |
| GitHub | Version Control & Portfolio Showcase |

---

## 📂 Dataset
**File:** [pizza_sales.csv](https://github.com/user-attachments/files/24592357/pizza_sales.csv)

**Key Columns:**
- order_id – Unique order identifier  
- pizza_id – Unique pizza identifier  
- pizza_name – Name of pizza  
- quantity – Number of pizzas ordered  
- total_price – Revenue per order  
- order_date, order_time – Date & time of order  
- pizza_category – Classic, Supreme, Veggie, Chicken  
- pizza_size – S, M, L, XL  

---

## 📊 Key Performance Indicators (KPIs)
- **Total Revenue**
- **Total Orders**
- **Total Pizzas Sold**
- **Average Order Value (AOV)**
- **Average Pizzas per Order**

---

-- Total Orders
SELECT COUNT(DISTINCT order_id) AS Total_Orders FROM pizza_sales;
