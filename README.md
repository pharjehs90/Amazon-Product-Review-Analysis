# Amazon-Product-Review-Analysis
This project focus on Amazon Product Review, which involves exploring customer feedback, product performance, and pricing data for products listed on Amazon. The goal is to help sellers and decision-makers gain data-driven insights into what makes a product successful and marketable, where improvements are needed, and how customer sentiment aligns with product ratings and reviews.

## Project Overview
The dataset contains information scraped from Amazon product pages, including:  
•       Product details: name, category, price, discount, and ratings  
•       Customer engagement: user reviews, titles, and content  
•       Each row represents a unique product, with aggregated reviewer data  stored as comma-separated values

## Data Source
Data was scraped from Amazon product pages, which include;
*  Product name, category, price, discount %, actual vs discounted price, ratings, rating count, review count, review text/title
Each row represents a single product, with aggregated reviews and performance data.
*  Records include 1,465 products from 16 columns

## Tools Used
- Microsoft Excel
- Visualizations
- Dashboard creation tool

## Analysis Tasks 
Using pivot tables and calculated columns, the following analysis were visualized
1. Average discount percentage by product category
2. Number of products listed under each category
3. Total number of reviews per category
4. Products that have the highest average ratings
5. The average actual price vs the discounted price by category
6. Products that have the highest number of reviews
7. Number products that have a discount of 50% or more
8. The distribution of product ratings
9. The total potential revenue (actual_price × rating_count) by category 
10. The number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)
11. How the rating relate to the level of discount
12. Number of products that have fewer than 1,000 reviews
13. Categories have products with the highest discounts
14. Identification of top 5 products in terms of rating and number of reviews combined

## Visualized Data
[Amazon case study file](https://github.com/pharjehs90/Amazon-Product-Review-Analysis/blob/main/Amazon%20case%20study%20file.xlsx)

## Insights from Dataset
Electronics had the highest product counts, but often came with lower average ratings.
Products with higher discounts often had more reviews, showing a possible link between discount and consumer engagement.
Most products fell in the ₹200–₹500 price range
Highest potential revenue observed in categories with both high ratings and high review counts.
Some categories offer high discounts, but their average ratings are not necessarily higher. This means price cuts alone don’t always translate to customer satisfaction.

## Recommendation
	Focus marketing efforts on high-performing categories: Electronics and Books
	Monitor and possibly relist low-rated products (<3 stars)
	Leverage discounts strategically, as they don’t always improve ratings
	Invest more in products with high review counts, they are likely to perform better
	Keep price points competitive in the ₹200–₹500 range for volume
