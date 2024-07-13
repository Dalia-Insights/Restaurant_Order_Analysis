![resturant order ananlysis jpg_1](https://github.com/user-attachments/assets/eeb0334c-eae4-4c3b-a078-b1375e7523a8)

# Taste World Cafe Customer Analysis Project

## Overview
This project aims to analyze customer data to evaluate the performance of menu items and understand customer preferences at Taste World Cafe.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Tools Used](#tools-used)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
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

## Exploratory Data Analysis

### Objective 1: Explore the items table
Your first objective is to better understand the items table by finding the number of rows, the least and most expensive items, and more.

### Objective 2: Explore the orders table
Your second objective is to understand the orders table by finding the date range, number of items per order, and more.

### Objective 3: Analyze customer behavior
Your final objective is to combine tables, find the least and most ordered categories, and analyze high spend orders.

---

## Data Analysis Queries
You can find the SQL queries used to answer the objectives in the project in this section.

---

## Results and Findings
This section presents the results and insights derived from the data analysis.

---

## References
- Guided Projects @ Maven Analytics: [Link to project](https://app.mavenanalytics.io/guided-projects/d7167b45-6317-49c9-b2bb-42e2a9e9c0bc#4mVvHvyFSbxxbwMliOuEx9)
