<h1 align="center"> █▓▒▒░░░PIZZA SALES DATA ANALYSIS░░░▒▒▓█ </h1>

## Business Understanding

### Problem Statement
A manager at a `Pizza Store` aims to analyze 2015 sales data to identify growth opportunities and enhance customer satisfaction. This analysis focuses on uncovering sales patterns, identifying peak demand periods, and understanding the popularity of various pizza categories to gain insights into customer preferences. By leveraging these findings, the manager plans to create data-driven strategies to optimize sales, refine marketing efforts, and drive overall revenue growth.

### Goals
1. **Increase Revenue**: 
2. **Increase Average Order Value (AOV)**:
   
### Objectives
- Identify sales patterns by time (monthly, hourly, weekday).
- Understand Customer Purchase Behavior
- Determine the most popular pizza categories or types.

### Business Metrics
1. **Total Revenue**: Total sales generated in the analysis period.
2. **Average Order Value (AOV)**: Average revenue per order.
3. **Total Pizzas Sold**: Total number of pizzas sold over the year.
4. **Total Orders**: Number of individual orders placed.
5. **Average Pizzas per Order**: Average quantity of pizzas per transaction.


## Exploratory Data Analysis (EDA)
### Dataset 
There are `48260 records` and `12 features`. The features terdiri dari:


### Decriptive Statistics
| Feature | Description | Detail |
| :------------ |:---------------| -----|
|pizza_id| A unique identifier for each type of pizza, useful for specifically identifying pizzas|48620 ids |
|order_id| A unique identifier for each order, helping to count the total number of orders and observe order trends|21350 ids |
|pizza_name_id| A specific ID for the pizza name, which can be used to group orders by pizza name| 92 ids|
|quantity| The number of pizzas ordered, essential for seeing sales volume and identifying best-selling pizzas|-|
|order_date| The date of the order, useful for analyzing sales trends by day, month, or season|01-01-2015 to 31-12-2015|
|order_time| The time of the order, beneficial for observing sales patterns during specific hours or times of day|9am - 11pm|
|unit_price| The price per pizza, useful for calculating total revenue and analyzing price differences among pizza categories||
|total_price| The total price of the order, allowing for the analysis of average order value and total revenue|-|
|pizza_size| The size of the pizza, which can be used to determine the most popular pizza sizes among customers|Regular, Medium, Large, X-Large, XX-Large|
|pizza_category| The category of the pizza (e.g., vegetarian, meat lovers, etc.), helpful for understanding which categories customers prefer|Chicken, Classic, Supreme, Veggie|
|pizza_ingredients| A list of ingredients in the pizza, which can be analyzed to identify preferences for toppings or ingredients|32 kinds|
|pizza_name| The name of the pizza, making it easier to identify the types of pizzas ordered|32 kinds|



### Insights

## Analyze & Visualize Data

### 1. KPI's
  ![image](https://github.com/user-attachments/assets/0d17f8e0-883e-4d28-b826-35b216965f26)


### 2. Sales Trends
 ![image](https://github.com/user-attachments/assets/621a3ee9-a69a-4caf-ad80-d1572dd93728)


### 3. Pizza Category

![image](https://github.com/user-attachments/assets/a6558516-6db5-4c1e-a75f-f8c5cdf4fc91)

https://github.com/user-attachments/assets/b6dab537-10d4-478d-a4e7-8bf29539a96e
> **Classic pizza**: Traditional flavors.
> **Supreme pizza**: A variety of toppings.
> **Chicken pizza**: Main ingredient is chicken.
> **Veggie pizza**: Fresh and vegetarian option.
  
#### Explanation:  

* Based on sales, **Classic** is the most popular category among customers at this pizza shop, generating revenue of **$220.05K**, which accounts for 26.91%. `The 3rd best-selling pizzas` in this category are **The Classic Deluxe, The Hawaiian, and The Pepperoni**.

* The 2nd highest sales category is **Supreme**, with revenue of **$208.20K (25.46%)**. `The 3rd best-selling pizzas` in this category are **The Sicilian, The Spicy Italian, and The Italian Supreme**.

* The 3rd highest sales category is **Chicken**, which contributes **23.96%** of the total revenue **($195.92K)**. `The 3rd best-selling pizzas` in this category are **The Barbecue Chicken, The Thai Chicken, and The California Chicken**.

* The lowest sales category is **Veggie**, contributing approximately **23.68% or $193.69K** in revenue. The top 3 selling pizzas in this category are **The Four Cheese, The Vegetables+Vegetables, and The Mexicana**.


### 4. Pizza Size
![image](https://github.com/user-attachments/assets/7d934ac9-8af5-450c-908b-bf1a68f9d1a5)

https://github.com/user-attachments/assets/243dca8f-62ab-4aac-9b55-6bdd9cbfb0ee

#### Explanation:

* The majority of pizzas are available in Small, Medium, or Large sizes, except for a few specialty pizzas such as:
    - The Big Meat in the Classic category is only available in Small size.
    - The Greek is also available in X-Large and XX-Large sizes, but the XX-Large size has very few customers, with only 28 orders.
    - The Brie Carre in the Supreme category is only available in Small size.
    - The Five Cheese in the Veggie category is only available in Large size.
    - The Four Cheese is only available in Medium and Large sizes.

* Based on revenue, the Large pizza size contributes approximately 45% of total revenue, Medium contributes about 30%, and Small contributes around 21%. Meanwhile, **X-Large and XX-Large sizes** have **very low revenue**, at less than 2%. In terms of customer preferences, the **Large size** is also the most popular, with **59.65%** of total customers who have ordered, followed by 52.27% for Medium and 49.13% for Small.

### 5. Best/Worst-Selling 

![image](https://github.com/user-attachments/assets/e2449575-1831-4a43-904c-92611fff8b06)

#### Explanation:

* `The Best-Selling pizzas` based on the highest sales are **The Classic Deluxe**, which sold **2,453 boxe**, contributing approximately ~10% of the total revenue, followed by The Barbecue Chicken, The Hawaiian, The Pepperoni, and The Thai Chicken. The 5th best-selling pizzas are **Chicken and Classic pizza categories**.
*  Conversely, `the Worst-Selling Pizzas` is **The Brie Carre** with **490 boxes** sold. This is likely due to it being the most expensive pizza type, with the small size priced at **$23.65**. For the worst-selling pizzas, **the Supreme category** has poor sales performance.



## Business Insights & Recommendation
### Insights

1. The peak hours for customers ordering pizza are from **12:00-1:00 pm** during `lunch` and **5:00-6:00 pm** during `dinner`. When looking at customer preferences, more orders are placed during **lunchtime**. In terms of pizza categories, during both peak hours, **Classic Pizza Category** is the most ordered by customers.

2. `The total revenue` this year is **$817.9K**, with the `highest revenue` occurring in **the second quarter (Q2)**, specifically in **July**. A closer look shows that sales are highest on **Thursdays, Fridays, and Saturdays** compared to other days.

3. Overall, the pizza category that generates `the highest revenue` is **Classic**, accounting for `26.91%` or $220.05K, but other categories also contribute nearly balanced proportions of revenue.

4. 



### Recomendations
1. we should consider removing pizzas that have consistently low sales figures, such as the **Brie Carre**, which has sold only 490 boxes. This may be due to its higher price point and less familiar flavor profile among our customers. By removing underperforming items, we can streamline the menu and focus on pizzas that resonate more with our target audience.
2. we can leverage promotions for our best-selling pizzas, particularly the **Classic Deluxe**, which sold 2,453 units and contributes significantly to our revenue. Here are a few promotional ideas:

    1. **Limited-Time Offers**: Create special deals for our best-selling pizzas during peak hours, such as "Buy One, Get One Half Off" or a discount on larger sizes. This can help boost sales during lunch and dinner rushes.
    
    2. **Combo Deals**: Introduce meal bundles that pair popular pizzas with sides or drinks at a discounted rate. For example, a "Family Meal Deal" that includes a large Classic Deluxe pizza, a side of garlic bread, and a 2-liter soda could encourage larger orders.
    
    3. **Seasonal Promotions**: Consider launching seasonal pizzas or themed promotions that highlight popular ingredients during specific times of the year, such as summer barbecue flavors or holiday-themed pizzas.
    
    4. **Loyalty Programs**: Implement a loyalty program where customers can earn points for every pizza purchase. Once they accumulate enough points, they can redeem them for free pizzas or discounts on future orders. This encourages repeat business and builds customer loyalty.
    
    5. **Feedback and Surveys**: Actively seek customer feedback through surveys to understand their preferences better. This can guide us in adjusting our menu and promotions to better meet customer demands.
    
