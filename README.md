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

 # KPIs:
## KPI Development
Once the schema is built, compute core performance indicators:
Basic KPIs
•	Total Orders
•	Total Revenue (INR Million)
•	Average Dish Price
•	Average Rating
Deep-Dive Business Analysis
Date-Based Analysis
•	Monthly order trends
•	Quarterly order trends
•	Year-wise growth
•	Day-of-week patterns
Location-Based Analysis
•	Top 10 cities by order volume
•	Revenue contribution by states
Food Performance
•	Top 10 restaurants by orders
•	Top categories (Indian, Chinese, etc.)
•	Most ordered dishes
•	Cuisine performance → Orders + Avg Rating
Customer Spending Insights
Buckets of customer spend:
•	Under 100
•	100–199
•	200–299
•	300–499
•	500+
With total order distribution across these ranges.
Ratings Analysis
Distribution of dish ratings from 1–5.







