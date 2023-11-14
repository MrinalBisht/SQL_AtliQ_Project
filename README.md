# AtliQ Hardware Retail Sales Analysis

## Project Overview

AtliQ Hardware is a leading online retailer specializing in electronic products, operating through a variety of sales channels, including direct, distributor, and physical retail stores with a strong online presence. Serving customers across the Asian Pacific, North America, South America, and Europe, AtliQ offers a diverse product catalog consisting of about 400 SKUs across over 10 categories. These products, including mice, processors, laptops, keyboards, etc., are customized for both personal and professional users. Over the course of 5 years, AtliQ has accumulated a vast dataset of over 1 million sales records, prompting business managers to make strategic decisions for the overall health of their global operations.

## Dataset

The dataset comprises two dimension tables for customer and product details, accompanied by five fact tables containing information about actual sales quantity, product price, discounts, and forecasted sales quantities. The sales quantity and discount-related tables contain the largest quantity of data, ranging from 1 to 2 million rows, while other tables vary from about 200 to 2000 rows.

## Tasks

### 1. Gross Sales: [SQL project gross sales.sql].([https://github.com/MrinalBisht/SQL_AtliQ_Project/blob/main/SQL%20Project_gross%20sales.sql])

The primary task involves creating a data table for a yearly sales report, providing gross sales data (gross price * quantity sold) for a specific customer over a customizable period. Additionally, the business manager aims to classify markets into "Gold" and "Silver" categories based on aggregated gross sales. The aggregated data assists in identifying top-performing products and markets within a specified timeframe. The data tables are constructed using MySQL, with an accompanying stored procedure facilitating quick customization based on the interested market, product, or customer for a given period.

### 2. Market Share

Shifting the focus to net sales, this task considers discounts given to customers based on royalty and product. Two types of discounts, pre-invoice discount offers on a fiscal year basis and post-invoice discounts on transactions, require the creation of SQL database views by joining multiple tables. Additional stored procedures enable interactive data table generation. Net sales data, aggregated on customer, market, or product levels, provides valuable insights for understanding top-performing customers and products in terms of net sales, facilitating informed business strategies. The data can be exported to CSV and visualized with tools like Excel.

### 3. Supply Chain

The goal of this task is to identify variances between the forecasted sales quantity and the actual sold quantity. Forecast accuracy data (forecast accuracy = 100% - absolute error%) empowers the supply chain manager to analyze data based on different criteria such as customer, product, or region. This understanding facilitates improvements in the accuracy of demand forecasts.

## SQL Skills Utilized

- **SQL Basics:** SELECT, WHERE, BETWEEN, GROUP BY, ORDER BY, etc.
- **Joins:** LEFT, RIGHT, INNER, FULL, CROSS.
- **Advanced Query Techniques:** Subqueries, CTEs, Views, Temporary Tables.
- **Database Concepts:** Fundamentals of ETL, Data Warehouse, OLAP, OLTP.
- **Data Engineer-Specific Topics:** Indexes, Triggers, Events, User Accounts & Privileges, Kanban Project Management.
- **Procedural Programming:** Proficiency in User Defined Functions and stored Procedures.
- **Window Functions:** Over, ROW_NUMBER, RANK, DENSE_RANK, etc.

## SQL Skills

The project involves various SQL skills, including but not limited to SQL basics, joins, subqueries, CTEs, views, temporary tables, fundamentals of ETL, data warehousing, OLAP, OLTP, data engineering-specific topics such as indexes, triggers, events, user accounts & privileges, and proficiency in user-defined functions, stored procedures, and window functions.
