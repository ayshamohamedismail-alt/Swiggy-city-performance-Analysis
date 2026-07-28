# Swiggy-city-performance-Analysis
This project focuses on analyzing Swiggy food delivery data to evaluate city-wise performance, customer behavior, and restaurant trends using Power BI. The dashboard provides actionable insights to help understand operational efficiency and support data-driven decision-making.

3 Objectives
Analyze city-level performance

Identify top & low performing restaurants

Understand customer rating behavior

Evaluate delivery time impact

Compare price range vs popularity

# Tools Used

Power BI

Power Query

Excel / CSV Dataset

# DATA SOURCE

Source Description and Timeline: GIGASHEETS/SWIGGY DATASET

Domain: Performance/ City-wise/ Sales / Price / Customer Analysis

# PROBLEM STATEMENT

To analyze city-wise performance of orders, ratings, and restaurant distribution on the platform.

To identify customer preferences by examining food types, pricing trends, and rating satisfaction levels.

To evaluate delivery efficiency across cities using delivery time and speed metrics.

To support data-driven decision-making by highlighting high-performing areas and improvement opportunities.

# TOOLS AND TECHNOLOGIES

Excel: Data cleaning, transformation, and Pivot Tables.

Power BI: Data modelling, DAX calculations, visualization, and interactive dashboard creation.

# DATA PRE-PROCESSING(POWER QUERY)

Data Cleaning & Transformation: Removed duplicates, handled missing values, standardized formats, and created conditional columns.

Filtering & Sorting: Organized data to focus on relevant records.

Convert the data into Fact and Dimension Table 

# DATA MODELLING AND DAX (POWER BI)

DATA MODEL : Established relationships between tables, defined cardinality AS ONE TO MANY

DAX MEASURE:Implemented DAX formulas for key metrics, 

Total Orders =  COUNT('Swiggy Restuarants dataset COPY'[ID])

Total Number of Rating =  SUM('Swiggy Restuarants dataset COPY (2)'[Total ratings])

Total Number of Restaurant = COUNT('Swiggy Restuarants dataset COPY (2)'[Restaurant])

Average Price  = MEDIAN('Swiggy Restuarants dataset COPY (2)'[Price])

Average Delivery Time = AVERAGE('Swiggy Restuarants dataset COPY'[Delivery time])

Average Rating =   AVERAGE('Swiggy Restuarants dataset COPY (2)'[Avg ratings])


# ANALYSIS AND VISUALISATIONS

## KPI Cards (Top Section)

Total Orders, Ratings, and Restaurants show strong platform scale, with consistent average pricing (~₹300) across cities.
Average ratings (~3.6–3.7) indicate moderate customer satisfaction, leaving room for service improvement.
Delivery time varies significantly (48–58 mins), directly impacting user experience across cities.

## Order by Area

Orders are highly concentrated in a few key areas, while other regions show lower activity.
This indicates demand clustering, suggesting targeted expansion opportunities in low-performing areas.

## Orders by Food Type

Chinese and North Indian cuisines dominate across cities.
Lower-performing categories like desserts and beverages indicate niche demand segments.
This helps in menu optimization and promotion strategies.

## Delivery Speed

Majority of deliveries fall under “Moderate” and “Slow” categories rather than “Fast.”
This suggests operational inefficiencies and scope for improving delivery logistics.

## Max & Min Delivery Time by City

Significant gap between minimum and maximum delivery times within cities.
Indicates inconsistency in delivery operations depending on area or traffic conditions.

## Min & Max Price by Area

Price variation across areas is noticeable, but not extreme.
Premium areas maintain slightly higher pricing, showing location-based pricing strategy.

## Rating Satisfaction

“Good” ratings dominate but “Bad” and “Moderate” are still substantial.
Indicates that while overall satisfaction is decent, customer experience is inconsistent.

## Restaurant Popularity by Area (Map)

Restaurant density and popularity are concentrated in urban hubs.
Less dense areas show untapped growth potential.

## Total Ratings & Avg Ratings by Area

Some areas have high total ratings but only average scores.
This suggests high traffic but inconsistent quality/service.

## Order by Rating Satisfaction

“Good” rated restaurants receive the highest number of orders.
However, a notable number of orders still come from “Bad” and “Moderate” categories, indicating brand dependency or lack of alternatives.

## Overall Insight 

The platform’s growth is driven more by location and cuisine demand than pricing.
Improving delivery speed and consistency is the biggest opportunity to boost customer satisfaction and retention. 

## CONCLUSION
This report successfully analyzes the dataset to uncover key trends and performance insights, presenting them through clear and structured visualizations. The findings enable informed decision-making by highlighting actionable opportunities for improvement and strategic growth.


