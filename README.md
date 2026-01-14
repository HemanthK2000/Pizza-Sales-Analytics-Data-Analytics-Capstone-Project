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
- order_id – Unique identifier for each order
- pizza_id – Unique identifier for each pizza
- pizza_name – Name of the pizza sold
- quantity – Number of pizzas sold per order 
- total_price – Total revenue for each transaction
- order_date, order_time – Order timestamp for time-based analysis
- pizza_category – Classic, Supreme, Veggie, Chicken  
- pizza_size – S(Regular), M(Medium), L(Large), XL(X-Large), XXL(XX-Large)

---

## 📊 Key Performance Indicators (KPIs)
- **Total Revenue** = Sum of total_price
- **Total Orders** = Sum of quantity
- **Total Pizzas Sold** = Count of unique order_id
- **Average Order Value (AOV)** = Total Revenue ÷ Total Orders
- **Average Pizzas per Order** = Total Pizzas Sold ÷ Total Orders

---

Analysis & Visualizations
Ingredient Analysis
The pizza business aims to understand which ingredients are most frequently used across different pizza types. By identifying the most common ingredients, the store can

Daily Trend
A line/bar chart showing sales by day of the week.
•	Useful for staffing and operations planning.

Hourly Trend
A line/bar chart showing sales by hour of the day.
Useful for staffing, ingredients, customer rush and operations planning

Monthly Trend
A line chart depicting monthly revenue and orders.
•	Helps track seasonality and identify peak sales months.
•	Summer months show higher sales due to promotional campaigns.

% of Sales by Category
A bar chart representing revenue and quantity sold for each pizza category (Classic, Supreme, Veggie, Chicken).
•	Helps identify customer preferences.
•	Classic pizzas dominate sales, while Veggie has lower demand.

% Sales by Pizza Size & Category
A bar/ donut chart comparing sales revenue and quantity by pizza size (S, M, L, XL).
•	Highlights demand distribution by size and assist inventory planning.
•	Large (L) pizzas contribute the highest revenue.

Total Pizzas Sold by Pizza Category
•	Manage inventory by stocking ingredients used in the most popular categories.
•	Evaluate if low-performing categories should be optimized, redesigned, or discontinued.

Top 5 Best-Selling Pizzas
A horizontal bar chart showing pizzas with the highest sales (by revenue, orders or quantity).
•	Supports promotional and menu strategy.

Bottom 5 Least-Selling Pizzas
A horizontal bar chart of pizzas with the lowest sales.
•	Identifies products for improvement or possible removal from the menu.


