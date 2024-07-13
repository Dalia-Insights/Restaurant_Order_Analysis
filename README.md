![resturant order ananlysis jpg_1](https://github.com/user-attachments/assets/eeb0334c-eae4-4c3b-a078-b1375e7523a8)

# Taste World Cafe Customer Analysis Project

## Overview
This project aims to analyze customer data to evaluate the performance of menu items and understand customer preferences at Taste World Cafe.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Tools Used](#tools-used)
4. [Exploratory Data Analysis: Uncovering Insights](#exploratory-data-analysis-:-uncovering-Insights)
    - [Objective 1: Explore the items table](#objective-1-explore-the-items-table)
    - [Objective 2: Explore the orders table](#objective-2-explore-the-orders-table)
    - [Objective 3: Analyze customer behavior](#objective-3-analyze-customer-behavior)
5. [Data Analysis Queries](#data-analysis-queries)
6. [Results and Findings](#results-and-findings)
7. [References](#references)

---

## Project Overview
Taste World Cafe recently debuted a new menu at the beginning of the year. This project aims to analyze customer data to evaluate the performance of menu items. The goal is to identify which menu items are performing well and which ones are not, and to understand customer preferences. By analyzing this data, the project seeks to provide insights into what the top customers prefer and which menu items are popular.

---

## Dataset
The project utilizes data from two main tables:
- **menu_items**: Contains details about each menu item including its columns:
  - `menu_item_id`: Unique ID of a menu item.
  - `item_name`: Name of a menu item.
  - `category`: Category or type of cuisine of the menu item.
  - `price`: Price of the menu item (US Dollars $).

- **order_details**: Provides information on each customer order, linking menu items to specific orders through item IDs. It includes columns for:
  - `order_details_id`: Unique ID of an item in an order.
  - `order_id`: ID of the order.
  - `order_date`: Date when the order was placed.
  - `order_time`: Time when the order was placed.
  - `item_id`: Matches the `menu_item_id` in the `menu_items` table.
  
![Dataset Schema](https://github.com/user-attachments/assets/aa6cbf83-24f9-4b0c-8c9e-2f382d4a23e4)

---

## Tools Used
- **MySQL**: For data storage and querying from the `menu_items` and `order_details` tables.

---

## Exploratory Data Analysis: Uncovering Insights

### Objective 1: Explore the items table
Explore the `menu_items` table to better understand the menu offerings:
- Find the total number of items on the menu.
- Identify the least and most expensive items.
- Determine the prices of items within each category.
- Count and analyze Italian dishes, including their least and most expensive options.

### Objective 2: Explore the orders table
Dive into the `order_details` table to analyze customer orders:
- Determine the date range of orders.
- Calculate the number of orders and items ordered within the specified date range.
- Identify orders with the highest number of items.
- Investigate how many orders had more than 12 items.

### Objective 3: Analyze customer behavior
Combine data from `menu_items` and `order_details` to gain insights into customer preferences:
- Merge tables to analyze the least and most ordered items and their respective categories.
- Identify the top 5 orders with the highest total spend.
- Review details of the highest spend order, including specific items purchased.
- Explore details of the top 5 highest spend orders for additional insights.

---

## Data Analysis Queries
### Objective 1: Explore the items table

#### Query 1: Total number of items on the menu
```sql
SELECT COUNT(*) AS total_items
FROM menu_items;
```
---

## Results and Findings
This section presents the results and insights derived from the data analysis.

---

## References
- Guided Projects @ Maven Analytics: [Link to project](https://app.mavenanalytics.io/guided-projects/d7167b45-6317-49c9-b2bb-42e2a9e9c0bc#4mVvHvyFSbxxbwMliOuEx9)
