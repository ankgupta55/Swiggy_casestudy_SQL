# Swiggy_casestudy_SQL
<a href="https://github.com/ankgupta55/Swiggy_casestudy_SQL/blob/main/swiggy_images.png">Swiggy</a>

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


  Steps Involved (SQL & ETL Activities):
  - Imported large CSV datasets into MySQL.
  - Cleaned and standardized data (date formats, numeric values, null handling, and removed duplicate data).
  - Created the Dimension table and the fact table.
 
## Analysis and Insights:
- Performed time-based analysis (daily, monthly, quarterly sales trends).
- Analyzed location-wise demand across cities and areas.
- Identified top restaurants and dishes based on revenue and ratings.
- Evaluated category contribution to overall sales.
- Assessed customer satisfaction using ratings and rating counts.






