#  Pizza Sales Dashboard – Data Analysis Project  

## 🎯 Project Objective  
The objective of this project is to analyze pizza sales data to uncover key business insights that can help improve sales performance, product strategy, and operational efficiency.  

This dashboard aims to:  
-  Identify top-performing pizza categories and sizes that generate the highest revenue.  
-  Determine the busiest days and peak ordering hours to optimize staffing and inventory management.  
-  Highlight best and worst-selling pizzas to guide marketing and menu decisions.  
-  Analyze customer purchasing trends through total sales, order volume, and average order value.  
-  Provide an interactive and data-driven visualization for management to make informed, strategic business decisions.


## 📘 Project Overview  

This project analyzes pizza sales data using **SQL** and **Excel** to uncover insights on revenue, top-selling pizzas, and customer trends.  
It features an interactive dashboard that highlights **sales performance**, **peak order times**, and **best/worst-selling products**, helping businesses make **data-driven decisions** for improved efficiency and growth.  

## 🧩 Problem Statement  

We need to analyze key indicators for our pizza sales data to gain insights into business performance.  
Specifically, we aim to calculate the following metrics (KPIs):  

### 📊 KPI Requirements  

1. **Total Revenue:**  
   The sum of the total price of all pizza orders.  

2. **Average Order Value:**  
   The average amount spent per order, calculated by dividing the total revenue by the total number of orders.  

3. **Total Pizzas Sold:**  
   The sum of the quantities of all pizzas sold.  

4. **Total Orders:**  
   The total number of orders placed.  

5. **Average Pizzas Per Order:**  
   The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.  

## 📊 Charts Requirement  

We aim to visualize various aspects of our pizza sales data to gain insights and understand key trends.  
The following charts were created to fulfill these requirements:  

1. **Daily Trend for Total Orders:**  
   A bar chart displaying the daily trend of total orders over a specific time period.  
   This helps identify patterns or fluctuations in daily order volumes.  

2. **Hourly Trend for Total Orders:**  
   A line chart illustrating the hourly trend of total orders throughout the day.  
   This reveals peak hours or periods of high order activity.  

3. **Percentage of Sales by Pizza Category:**  
   A pie chart showing the distribution of sales across different pizza categories.  
   This provides insights into the popularity of pizza categories and their contribution to total sales.  

4. **Percentage of Sales by Pizza Size:**  
   A pie chart representing the percentage of sales attributed to different pizza sizes.  
   This helps understand customer preferences for pizza sizes and their impact on sales.  

5. **Total Pizzas Sold by Pizza Category:**  
   A funnel chart presenting the total number of pizzas sold for each category.  
   This allows comparison of sales performance across different pizza categories.  

6. **Top 5 Best Sellers by Total Pizzas Sold:**  
   A bar chart highlighting the top 5 best-selling pizzas based on total pizzas sold.  
   This identifies the most popular pizza options.  

7. **Bottom 5 Worst Sellers by Total Pizzas Sold:**  
   A bar chart showcasing the bottom 5 worst-selling pizzas based on total pizzas sold.  
   This helps identify underperforming or less popular pizza options.  


## 🛠️ Tools & Technologies  

| Tool / Technology | Purpose |
|--------------------|----------|
|  **Microsoft Excel** | Data visualization, dashboard creation, and analysis using charts, pivot tables, and slicers |
|  **SQL (MS SQL Server)** | Data extraction, cleaning, aggregation, and trend analysis |

## 📂 Dataset Information  

The dataset used in this project is [**pizza_sales.csv**](./pizza_sales.csv), which contains detailed sales records for a pizza store.  
It includes information about orders, pizza types, categories, sizes, quantities, prices, and order dates. 

## 🔎 Key Insights  
- Total Revenue: **$71,403**  
- Average Order Value: **$38.53**  
- Total Pizzas Sold: **4,328**  
- Highest Orders: **Friday & Saturday evenings (12–1 PM, 4–8 PM)**  
- Best Sellers: **Classic Deluxe** and **Chicken Pizzas**  
- Lowest Seller: **Brie Carre Pizza**

## ⚙️ SQL Tasks Performed  

-  **Data Cleaning & Filtering:** Used `WHERE`, `LIKE`, and `BETWEEN` clauses to clean and filter data.  
-  **Data Aggregation:** Applied `SUM()`, `AVG()`, `COUNT()`, and `GROUP BY` to calculate key metrics.  
-  **Time-Based Analysis:** Used `DATEPART()` and `ORDER BY` to analyze daily and hourly sales trends.  
-  **Category & Size Analysis:** Performed joins and subqueries to compare sales across pizza categories and sizes.  

## 🚀 Business Impact  

-  Helped identify **top-selling pizza categories** for targeted promotions.  
-  Optimized **staffing schedules** around peak business hours.  
-  Improved **inventory planning** based on size and category trends.  
-  Enabled management to make **data-driven decisions** with visual clarity and confidence.  

## 📊 Dashboard Preview  

![Pizza Sales Dashboard](Pizza_sales_Dashboard.jpg)
