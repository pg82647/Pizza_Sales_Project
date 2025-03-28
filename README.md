# Pizza_Sales_Project
Capstone Project on Pizza Sales

<details>  
<summary> BUSINESS UNDERSTANDING </summary>  

- <h5> OBJECTIVE:</h5>  
In order to optimize sales, improve on existing menu offerings, and enhance customer experience, the PIZZA SALES DATA (2015) was provided with the aim of making data-driven decisions and to maximise profit.  
- <h5> KEY GOALS:</h5>  
  - BUSINESS ANALYSIS: Understand, Total Revenue, sales fluctuations, and seasonal trends  
  - PRODUCT PERFORMANCE: Identify top selling and least selling pizza types in order to optimize the menu/ingredients  
  - CONSUMER BEHAVIOUR: Understand purchasing patterns based on time, day, month, and order volume.  - PRICING AND DISCOUNTS: Assess the impact of pricing on sales and explore seasonal promotions.  
  - INGREDIENT OPTIMIZATION: Analyze the usage of ingredients and assess the cost vs. revenue for each pizza type.  
  - OPERATIONAL EFFICIENCY: Improve order fulfillment by analyzing order processing times and delivery vs. dine-in sales.  
- <h5> BUSINESS QUESTIONS:</h5>  
1. Sales Performance & Revenue Analysis:  
  - Total Revenue: What is the total revenue generated in 2015?.  
  - Monthly Revenue Trends: How do sales fluctuate across different months? Are there any seasonal patterns?  
  - Daily & Hourly Sales Distribution: What are the peak sales days and times?.
  - Average Order Value (AOV): What is the average revenue per order?  
2. Product Performance & Menu Optimization:  
  - Top & Bottom-Selling Pizzas: Which pizza types are the most and least popular based on quantity sold?  
  - Revenue by Pizza Category: How does sales performance vary across different categories (e.g., Vegetarian, Non-Vegetarian, Vegan)?  
  - Revenue by Pizza Size: What proportion of sales comes from small, medium, and large pizzas?  
3. Customer & Order Behaviour:  
  - Average Quantity per Order: How many pizzas are typically ordered in a transaction?  
  - Most Common Order Time: At what time of the day are most orders placed?  
  - Day of the Week Analysis: Which days have the highest and lowest sales volumes?  
4. Pricing & Discount Strategy:  
  - Price Sensitivity: Do higher-priced pizzas sell less compared to lower-priced ones?  
  - High-Value vs. Low-Value Orders: What percentage of orders contribute the most revenue?  
  - Seasonal Pricing Effects: Are there opportunities for seasonal promotions based on demand trends?  
5. Ingredient & Inventory Optimization:  
  - Most Used Ingredients: Which ingredients are in highest demand based on sales?  
  - Cost vs. Revenue Analysis: How do ingredient costs compare to revenue generated per pizza type  
6. Operational Efficiency & Order Fulfillment:  
  - Order Processing Time: If timestamps are available, what is the average time between order placement and fulfillment?  
  - Delivery vs. Dine-in Sales (if applicable): How do sales compare across different service channels?
</details>  
<details>  
<summary> DATA UNDERSTANDING:</summary>  
- <h5> DATASET OVERVIEW:</h5>  
The dataset contains transactional data from 2015, including details such as pizza orders, pricing, quantities, and timestamps. Key metadata columns include:  
o	pizza_id: Unique pizza identifier.  
o	order_id: Unique identifier for each order.  
o	pizza_name_id: Identifier for specific pizza types.  
o	quantity: Number of pizzas in an order.  
o	order_date & order_time: When the order was placed.  
o	unit_price & total_price: Price details for each pizza.  
o	pizza_size: Size of the pizza (Small, Medium, Large).  
o	pizza_category: Category of pizza (e.g., Veggie, Non-Veg).  
o	pizza_ingredients: List of ingredients in the pizza.  
o	pizza_name: Human-readable name of the pizza.  
This provides a structured view of the data to understand how sales can be analyzed in terms of volume, revenue, and customer behavior.  
</details>  
<details>  
<summary> DATA PREPARATION:</summary>    
The order_date column had a mix of date and text data types. All cells in the column were formatted to proper date data type.  
A similar situation was noticed in the order_time column before they were all formatted to the proper time data type.  
The unit_price and total_price columns were formatted to two decimal places with the dollar symbol added.  
Five (5) columns were created to ease the analytical process. They are month, day_of_week, hour, price_grade, and quarter columns. While the month, day_of_week, and hour were extracted from order_date and order_time, the price_grade and quarter columns were classified based on unit_price and order_date columns.  
</details>  
<details>  
<summary> ANALYSIS: </summary>  
Pivot tables, pivot charts and slicers were used to answer most of the business questions.  
Two (2) dashboards were created. One is the REVENUE DASHBOARD while the other is a SALES DASHBOARD  
Due to unavailable data, the second business question for number five and the questions for number six could not be treated at this time.
</details>  

