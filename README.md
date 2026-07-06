# E-commerce Funnel & Revenue Analysis with SQL

## Project Overview

This project is a SQL analysis of an e-commerce user journey.

The goal was to understand how users move through the funnel, from page view to purchase, and to identify where performance can be improved.

I used SQL to analyze conversion rates, traffic sources, time to purchase, and revenue metrics.

This project was inspired by a SQL learning tutorial and rebuilt as a structured portfolio project.

## Business Questions

The analysis answers four main questions:

1. How many users move from page view to purchase?
2. Which traffic sources convert the best?
3. How long does it take users to buy after visiting the website?
4. What are the main revenue metrics, such as average order value and revenue per visitor?

## Dataset

The dataset contains e-commerce user events.

Main columns used:

- user_id
- event_type
- event_date
- traffic_source
- amount

Main event types analyzed:

- page_view
- add_to_cart
- checkout_start
- payment_info
- purchase

## Tools Used

- SQL
- PostgreSQL / Supabase
- GitHub

## Analysis Performed

### 1. Global Funnel Analysis

I calculated how many users reached each step of the funnel:

- page view
- add to cart
- checkout start
- payment information
- purchase

I also calculated conversion rates between each step.

### 2. Funnel Analysis by Traffic Source

I compared traffic sources to understand which channels generated the best conversion rates.

This helps identify whether traffic volume actually leads to purchases.

### 3. Time-to-Conversion Analysis

I calculated the average time between:

- page view and add to cart
- add to cart and purchase
- page view and purchase

This helps understand how quickly converted users make a buying decision.

### 4. Revenue Analysis

I calculated key revenue metrics:

- total visitors
- total buyers
- total revenue
- total orders
- average order value
- revenue per buyer
- revenue per visitor

## Key Learnings

This project helped me practice:

- using CASE WHEN inside aggregate functions
- building funnel metrics with COUNT DISTINCT
- grouping results by traffic source
- using WITH queries to structure SQL logic
- calculating time differences between events
- translating SQL outputs into business recommendations

## Business Recommendations

The analysis can be used to make recommendations on:

- which funnel steps need optimization
- which traffic sources deserve more budget
- whether acquisition costs are sustainable compared with average order value
- whether users need retargeting or email follow-up before purchasing

## Project Status

Completed as a SQL learning and portfolio project.
