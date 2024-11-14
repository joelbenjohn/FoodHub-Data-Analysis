# FoodHub Data Analysis Project

[![View Project](https://img.shields.io/badge/View-GitHub%20Page-blue)](https://joelbenjohn.github.io/FoodHub-Data-Analysis/)

This repository contains a comprehensive analysis of the FoodHub dataset, which includes data related to online food orders in New York. The analysis aims to help FoodHub improve its business operations and enhance customer experience by extracting insights from the data.

## Project Overview

FoodHub is an online food aggregator that connects customers with their favorite restaurants, handling order placement and delivery. With the increasing number of online food orders, this project focuses on understanding customer behavior, restaurant performance, and delivery efficiency.

## Objectives

- Analyze the demand for different restaurants and cuisines.
- Assess the efficiency of delivery times and identify opportunities for optimization.
- Investigate customer spending patterns and ratings to provide actionable recommendations.
- Identify top-performing restaurants for potential promotional offers.

## Key Questions Answered

1. How many orders are not rated?
2. What is the most popular cuisine on weekends?
3. Which restaurants receive the most orders?
4. How does delivery time vary between weekdays and weekends?
5. What percentage of orders take more than 60 minutes from placement to delivery?
6. What are the revenue-generating patterns for orders costing above $20 and between $5 and $20?

## Analysis Summary

- **Top Restaurants:** Shake Shack and The Meatball Shop have the highest number of orders.
- **Popular Cuisine:** American cuisine is the most ordered, especially on weekends.
- **Delivery Time:** The mean delivery time is longer on weekdays compared to weekends.
- **Revenue:** The total revenue generated is $6,166.30 from all orders.

## Recommendations

1. **Improve weekday delivery efficiency** by optimizing routes or adding more delivery personnel.
2. **Promote high-rated restaurants** to drive more traffic and orders.
3. **Target high-spending customers** with loyalty programs.
4. **Address long delivery times** by analyzing patterns and making necessary adjustments.
5. **Expand American cuisine offerings** and capitalize on its popularity.

## Dataset

The dataset includes information about:
- `order_id`: Unique identifier for each order
- `customer_id`: Identifier for the customer who placed the order
- `restaurant_name`: Name of the restaurant
- `cuisine_type`: Type of cuisine ordered
- `cost_of_the_order`: Total cost of the order
- `day_of_the_week`: Day the order was placed (weekday or weekend)
- `rating`: Customer rating out of 5
- `food_preparation_time`: Time taken by the restaurant to prepare the food
- `delivery_time`: Time taken by the delivery person to deliver the food

### Prerequisites

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`
