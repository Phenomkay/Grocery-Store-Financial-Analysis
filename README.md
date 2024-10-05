# Grocery Store Analysis

**Subtitle:** Sales and Revenue Performance Overview for the Year 2023

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data Dictionary](#data-dictionary)
3. [Key Metrics](#key-metrics)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
    - Sales Volume by Product Category
    - Monthly Revenue Over Time
    - Total Revenue by Product Category
    - Payment Method Distribution
5. [Conclusion](#conclusion)
6. [Technologies Used](#technologies-used)

## Project Overview

This project analyzes sales and revenue performance at a grocery store for the year 2023. The dataset includes details about transactions, products, categories, and payment methods used by customers. The goal of this analysis is to gain insights into total sales, revenue, product performance, and payment preferences, helping the grocery store make data-driven decisions for inventory management, pricing strategies, and customer service improvements.

## Data Dictionary

The dataset consists of the following columns:

- **transaction_id**: Unique identifier for each transaction.
- **transaction_date**: The date the transaction occurred (YYYY-MM-DD format).
- **product_name**: Name of the product purchased.
- **product_category**: Category of the product (e.g., bakery, meat, dairy).
- **quantity**: The number of units of the product purchased.
- **unit_price**: Price per unit of the product.
- **total_price**: Total price of the transaction (calculated as `quantity * unit_price`).
- **customer_id**: Unique identifier for each customer.
- **payment_method**: Method of payment (e.g., debit card, credit card, cash).
- **transaction_month**: Extracted month from the transaction date for monthly analysis.

NB - This is a sample dataset generated from mockaroo.

## Key Metrics

- **Total Sales**: 1000 transactions.
- **Total Quantity Sold**: 498,370 units of products.
- **Total Revenue**: \$5,094,493.41.
- **Average Revenue Per Transaction**: \$5,094.49.

These metrics offer a quick snapshot of the grocery store's performance over the year, providing valuable insights into sales volume and revenue generation.

## Exploratory Data Analysis (EDA)

### 1. Total Sales Volume by Product Category

We analyzed the total quantity of products sold across different categories. This helps identify which product categories are most in demand and may need more focus in terms of stocking or promotions.

**Visualization**: 
A bar plot showing the total sales volume for each product category, which reveals the categories that contribute the most to sales.

### 2. Monthly Revenue Over Time

The revenue generated each month was plotted to observe trends and seasonality. This analysis helps in identifying months with peak sales and those with lower performance, enabling the store to optimize inventory and marketing strategies.

**Visualization**: 
A line plot showing monthly revenue over the year, with markers for each month.

### 3. Total Revenue by Product Category

Revenue generated by each product category was summed to identify the most lucrative categories. This insight is crucial for pricing strategies and resource allocation.

**Visualization**: 
A bar plot displaying total revenue by product category.

### 4. Payment Method Distribution

We explored the distribution of different payment methods used by customers, which provides insights into customer preferences for payment options. This information can help the store in optimizing payment processes.

**Visualization**: 
A pie chart showing the percentage distribution of payment methods (debit card, credit card, cash, etc.).

## Interpretation and Insights
The analysis of the grocery store data provides key insights into the store's sales performance, revenue generation, and customer behavior during the year 2023. By examining the sales volume, revenue, and payment method distribution across different product categories and months, we can derive meaningful conclusions that can inform strategic decision-making.

### Key Insights:
1. **Product Performance**: 
   - **Top Performers**: The dairy category consistently emerges as the highest contributor in both total sales volume and revenue, signaling its importance to the store's overall success. Meat and pantry items also show strong demand, with significant sales and revenue contributions.
   - **Moderate Performers**: Bakery, beverages, and produce exhibit moderate revenue and sales volume, while snacks and frozen foods perform consistently but generate lower revenues compared to other categories.
   - **Low Performers**: Beverages and bakery items have the lowest sales volume and revenue, indicating potential areas for improvement through targeted marketing or product optimization.

2. **Monthly Revenue Trends**: 
   - **Revenue Peaks**: March and September emerge as high-revenue months, likely driven by seasonal trends or promotions.
   - **Revenue Dips**: June and August see noticeable drops in revenue. Investigating the reasons for these declines and developing marketing strategies could help boost sales during these periods.

3. **Payment Preferences**: 
   - **Mobile Payment Dominance**: Mobile payments account for the largest share of transactions, reflecting a growing trend towards digital payments. Debit cards also hold a substantial share, emphasizing the need for a seamless digital payment experience.
   - **Diverse Preferences**: While cash and credit card usage are lower, they still represent significant portions of transactions, highlighting the importance of offering multiple payment options to cater to various customer preferences.

### Actionable Recommendations:
- **Product Strategy**: Focus marketing efforts on promoting high-performing categories such as dairy and pantry items. Additionally, explore strategies to boost sales for lower-performing categories like bakery and beverages, which could involve discounts, special offers, or improved in-store placement.
  
- **Marketing and Promotions**: Tailor marketing campaigns to address the dips in revenue during June and August. For instance, offering seasonal promotions or discounts could help incentivize purchases during slower months.
  
- **Payment Options**: Ensure that the mobile payment and debit card systems are optimized, as these are the preferred methods among customers. Consider offering promotions or discounts for credit card or cash transactions to balance the payment method distribution.

---

## Conclusion:

This detailed analysis provides actionable insights into optimizing product performance, marketing strategies, and customer payment preferences. For a more in-depth walkthrough of the findings, **check out my YouTube video** where I explain the key points and how to implement these insights effectively:

🔗 [**Watch the full analysis on YouTube**](https://youtu.be/MqSHAoWva3w)

---

## Technologies Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For creating static, interactive, and animated visualizations.
- **Seaborn**: For creating informative and attractive statistical graphics.
- **Python**: The core programming language used for data analysis.
- **Jupyter Notebook**: For creating and sharing live code and visualizations.

---

By providing a detailed analysis of sales and revenue, this project empowers the grocery store with data-driven insights to enhance operational efficiency and maximize profits.

