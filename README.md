#Food Delivery Analytics Case Study (SQL)

##Project Overview

This project simulates a real-world food delivery platform similar to Zomato/Swiggy. The goal is to analyze customer behavior, restaurant performance, and order trends using SQL.

---

##Database Schema

### customers

* customer_id
* name
* city
* signup_date

### restaurants

* restaurant_id
* name
* city
* cuisine

### orders

* order_id
* customer_id
* restaurant_id
* order_date
* delivery_time
* order_value

### order_items

* order_id
* item_name
* quantity
* price

---

##Business Questions

### Level 1

1. Total number of orders
2. Unique customer cities
3. Average order value
4. Top 5 highest value orders

### Level 2

5. Revenue per restaurant
6. Orders per customer
7. Restaurants with >50 orders
8. Most ordered item

### Level 3

9. Total spending per customer
10. Most popular cuisine
11. Average delivery time per restaurant
12. Customers ordering from >3 restaurants

### Level 4

13. Top 3 customers by spending
14. Monthly revenue trend
15. Repeat customers and their contribution


## Key Insights

--> Top customers contribute a significant portion of total revenue → opportunity for loyalty programs
--> Repeat customers are critical for sustained revenue
--> Monthly trends help identify seasonal demand patterns
--> Cuisine popularity can guide marketing and partnerships





##Author

Aashita Sharma
Business/Operations/Data Analyst

