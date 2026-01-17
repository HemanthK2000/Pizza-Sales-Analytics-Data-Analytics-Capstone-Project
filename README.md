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
- pizza_ingredients - Ingredients used in preparing the pizza

![Image](https://github.com/user-attachments/assets/76f110de-e30d-4925-823d-1ab5bfcbe6fa)

---

## 📊 Key Performance Indicators (KPIs)
- **Total Revenue** = Sum of total_price
- **Total Orders** = Sum of quantity
- **Total Pizzas Sold** = Count of unique order_id
- **Average Order Value (AOV)** = Total Revenue ÷ Total Orders
- **Average Pizzas per Order** = Total Pizzas Sold ÷ Total Orders

---

## 📉 Analysis & Visualizations
**Ingredient Analysis**
- The pizza business aims to understand which ingredients are most frequently used across different pizza types.

**Daily Trend**
- A line/bar chart showing sales by day of the week.
- Useful for staffing and operations planning.

**Hourly Trend**
- A line/bar chart showing sales by hour of the day.
- Useful for staffing, ingredients, customer rush and operations planning

**Monthly Trend**
- A line chart depicting monthly revenue and orders.
- Helps track seasonality and identify peak sales months.
- Summer months show higher sales due to promotional campaigns.

**Percentage of Sales by Category**
- A bar chart representing revenue and quantity sold for each pizza category (Classic, Supreme, Veggie, Chicken).
- Helps identify customer preferences.
- Classic pizzas dominate sales, while Veggie has lower demand.

**Percentage Sales by Pizza Size & Category**
- A bar/ donut chart comparing sales revenue and quantity by pizza size (S, M, L, XL, XXL).
- Highlights demand distribution by size and assist inventory planning.
- Large (L) pizzas contribute the highest revenue.

**Total Pizzas Sold by Pizza Category**
- Manage inventory by stocking ingredients used in the most popular categories.
- Evaluate if low-performing categories should be optimized, redesigned, or discontinued.

**Top 5 Best-Selling Pizzas**
- A horizontal bar chart showing pizzas with the highest sales (by revenue, orders or quantity).
- Supports promotional and menu strategy.

**Bottom 5 Least-Selling Pizzas**
- A horizontal bar chart of pizzas with the lowest sales.
- Identifies products for improvement or possible removal from the menu.

---

## 🗃️ SQL Queries
![Image](https://github.com/user-attachments/assets/0d4dd075-9a48-472c-9e95-adda7a54ec0c)
![Image](https://github.com/user-attachments/assets/0ff52574-6af7-4579-b569-a85eab628152)
![Image](https://github.com/user-attachments/assets/d056fab4-a90a-4fef-b1c8-c497ff1de020)
![Image](https://github.com/user-attachments/assets/d3985b3a-2b31-4a19-a796-8010a4d3a9c0)
![Image](https://github.com/user-attachments/assets/8d0b61ed-2b78-4ee9-88d9-dd373485788c)
![Image](https://github.com/user-attachments/assets/fb63bacd-e702-4347-8697-b836ac510635)
![Image](https://github.com/user-attachments/assets/0369cfc5-7b19-4b24-88b9-26a9156f6262)

## 📊 Dashboards

## **📈 Power BI Dashboard** 

**📊🎥 Interactive Dashboard Videos :-** Interactive Slicers (Date,Pizza Category)

https://github.com/user-attachments/assets/bfabbf44-7aa3-45a5-adc5-86627e4dc04f

https://github.com/user-attachments/assets/84fed81c-6cdf-4fac-9d06-15ccf27be73c


- KPI's (Total Revenue, Average Order Value, Total Pizzas Sold, Total Orders, Average Pizzas Per Order)
![Image](https://github.com/user-attachments/assets/b102ca0c-db4a-437c-ab8c-631c6bf12c9f)

- Daily Trend for Total Orders
![Image](https://github.com/user-attachments/assets/f4996dbf-850c-492a-aff9-48eb0ca730ee)

- Montly Trend for Total Orders
![Image](https://github.com/user-attachments/assets/febbba37-2b15-4d60-8ed0-b2118729ec11)

- Percentage of Sales by Pizza Category
![Image](https://github.com/user-attachments/assets/aa283c2f-481e-439a-b7cb-0e0b7556263c)

- Percentage of Sales by Pizza Size
![Image](https://github.com/user-attachments/assets/8fcd4493-511d-4df8-b5ac-4b3b9b5f6285)

- Total Pizzas Sold by Pizza Category
![Image](https://github.com/user-attachments/assets/ad1f3e82-f0ef-45ea-8886-3183f512665a)

- Top 5 Pizzas by Revenue, Quantity, Total Orders
![Image](https://github.com/user-attachments/assets/2b3bf486-4219-49ab-80d3-e25bef3a0600)

- Bottom 5 Pizzas by Revenue, Quantity, Total Orders 
![Image](https://github.com/user-attachments/assets/1122550a-7d88-42da-80a7-114352d5c3e8)

**📈 Dashboard Images :-**

![Image](https://github.com/user-attachments/assets/c82ba249-1ec4-49ac-9f5d-e93d76ef4d58)

![Image](https://github.com/user-attachments/assets/0a07d8d8-1a63-4e86-a3c6-b58d38e2469e)

**Key Insights:-**
- Orders are highest on weekends, Friday/Saturday evenings.
- There are maximum orders from month of July and January.
- Classic Category contributes to maximum sales & total orders.
- Large size pizza contributes to maximum sales.
- The Thai Chicken pizza contributes to maximum revenue.
- The Classic Deluxe pizza contribute to maximum total quantities.
- The Classic Deluxe pizza contributes to maximum total orders.
- The Brie Carre pizza contributes to minimum revenue.
- The Brie Carre pizza contribute to minimum total quantities.
- The Brie Carre pizza contributes to minimum total orders.

## **🧩 Tableau Dashboard**
- KPI Cards
- Daily & Monthly Trends
- Category & Size Contribution
- Top / Bottom Performing Pizzas

## **🧪 Excel Analysis**
- KPI Cards

## **🧪 Python Analysis**
Performed using Jupyter Notebook:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- KPI Calculations
- Visualizations (Bar Charts, Line Charts, Pie Chart etc)
- **Libraries Used:**- pandas, numpy, matplotlib, seaborn

**Charts:-**
- Ingredient Analysis
- Daily Trend - Total Orders
- Daily Trend - Total Revenue
- Daily Trend - Total Quantity
- Hourly Trend - Total Orders
- Hourly Trend - Total Revenue
- Hourly Trend - Total Quantity
- Montly Trend - Total Orders
- Montly Trend - Total Revenue
- Montly Trend - Total Quantity
- Percentage of Sales by Category
- Percentage of Sale by Pizza Size & Category
- Total Pizzas Sold by Pizza Category
- Top 5 Best-Selling Pizzas - Total Orders
- Top 5 Best-Selling Pizzas - Total Revenue
- Top 5 Best-Selling Pizzas - Total Quantity
- Bottom 5 Least-Selling Pizzas - Total Orders
- Bottom 5 Least-Selling Pizzas - Total Revenue
- Bottom 5 Least-Selling Pizzas - Total Quantity

![Image](https://github.com/user-attachments/assets/688e33e2-0208-445e-873e-2ced785474d5)
![Image](https://github.com/user-attachments/assets/8479e472-1f7e-41c2-b63f-6533754f4613)
![Image](https://github.com/user-attachments/assets/e4acaf1b-a052-4892-8293-c5b599819677)
![Image](https://github.com/user-attachments/assets/0bb65217-6955-42a0-9226-9b8f08b491b2)
![Image](https://github.com/user-attachments/assets/3c315416-efdb-4c13-99f2-bac26b5465d8)
![Image](https://github.com/user-attachments/assets/3ad74e90-f450-490f-9093-c3265ccd6879)
![Image](https://github.com/user-attachments/assets/3998e14b-7633-461c-bb97-ce4ab282c443)
![Image](https://github.com/user-attachments/assets/37c18c20-f57a-4005-ae75-d16eccd8be49)
![Image](https://github.com/user-attachments/assets/8020a89a-05cc-493d-84dc-26f9aea00458)
![Image](https://github.com/user-attachments/assets/ebe8c901-563b-485b-80bd-40c6235db739)
![Image](https://github.com/user-attachments/assets/3c329697-8487-4149-acd1-2e8c6da14d6a)

---

## 🔍 Business Questions Answered
- What is the total revenue generated?
- How many pizzas were sold in total?
- Which category and size of pizzas perform best?
- Which pizzas are the top and bottom performers?
- What is the average order value and average pizzas per order?
- What are the sales trends by day, month, and time of day?

---

## 📝 Conclusion & Recommendations

The analysis provides a comprehensive view of pizza sales performance. Management can leverage these insights to:
- Focus marketing on high-performing categories.
- Optimize the menu by reconsidering least-selling pizzas.
- Plan inventory and staffing based on sales peaks.
- Monitor KPIs regularly through dashboards for continuous improvement.

---

## 👤 Author

### **Hemanth K**  
Data Analytics Capstone Project
<br> Tools: |Excel| |SQL| |Python| |Tableau| |Power BI|
<br> |Portfolio Ready | Resume Project | Interview Showcase|
<br> Aspiring Data Analyst  
📫 LinkedIn: *(https://www.linkedin.com/in/hemanth-k-7469a9196?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)*  
📂 Portfolio: *(https://github.com/HemanthK2000)* 
