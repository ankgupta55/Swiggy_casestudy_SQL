# Swiggy_casestudy_SQL
<img width="259" height="194" alt="image" src="https://github.com/user-attachments/assets/e412c455-1aa2-46b1-b448-c86e3416de5c" />


📊 Swiggy Sales Analysis Using SQL (Star Schema Implementation)
Project Overview

Designed and implemented an end-to-end Swiggy Sales Analysis solution using SQL by building a star schema data model consisting of fact and dimension tables. The project involved transforming raw CSV data into structured analytical tables to enable scalable, high-performance querying and business insights.

## Data Modelling and Table Design:
- Created a Fact Table (fact_swiggy_orders) to store order-level transactional metrics such as price, rating, and rating count.
- Designed and populated Dimension Tables:
- dim_date (date hierarchy: year, month, quarter, week)
- dim_location (state, city, area)
- dim_restaurant (restaurant details)
- dim_category (food category)
- dim_dish (dish-level details)


✅ Resume Bullets (4–5 Strong & ATS-Friendly)

Designed and implemented a star schema data model by creating fact and dimension tables (date, location, restaurant, category, dish) using SQL.
Performed ETL operations by importing large CSV datasets into MySQL and transforming raw data into analytics-ready tables.
Loaded data into the fact table using optimized INSERT…SELECT queries with multiple joins, ensuring referential integrity.
Improved query performance by eliminating duplicate dimension records, adding indexes, and batching inserts.
Analyzed sales trends, top restaurants, popular dishes, and customer ratings using advanced SQL aggregations.
 
## Analysis and Insights:
- Performed time-based analysis (daily, monthly, quarterly sales trends).
- Analyzed location-wise demand across cities and areas.
- Identified top restaurants and dishes based on revenue and ratings.
- Evaluated category contribution to overall sales.
- Assessed customer satisfaction using ratings and rating counts.









