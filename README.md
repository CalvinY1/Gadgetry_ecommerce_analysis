# Gadgetry E-commerce Analysis

# Project Overview
<p alight="center">
  <img src=images/gadgetrylogo.png>
</p>

## Company Background
Gadgetry, founded in 2018, is a global e-commerce company that sells popular electronics products through their online website and mobile app. They use a variety of marketing channels to reach customers, including Email campaigns, SEO, and affiliate links. Over the last few years, their more popular products have been products from Apple, Samsung, and ThinkPad.

## Data Structure
The database structure consists of four tables: orders, customers, geo_lookup, and order_status, with a total row count of 108,128 records.
![Alt Text](images/Elist_ERD.png)

## Project Goals
This project aims to provide insights and recommendations to inform sales and marketing strategies on the following key areas:
* Sales Metrics - Focused on Revenue, Average Order Value (AOV), and Order Count
* Product Performance - Analysis of sales metrics across products
* Global Reach - Analysis of sales metrics across global regions
* Loyalty Program Performance - Assessment of loyalty program's effectiveness

This analysis focuses on sales data from 2019 to 2022. 
  
# Summary of Insights
## Overall Trends
Sales showed a strong upward trajectory through 2020, peaking in **December with 1.2M in monthly revenue**. The **most significant month-over-month (MoM) growth occurred in March 2020, with a 41.26% increase** in revenue, likely influced by pandemic-driven consumer behavior.

Performance remained strong throughout **2020 and 2021, with both years more than doubling 2019 revenue**. However, **revenue declined in 2022, returning to 2019 levels by year-end**. **October 2022 marked the largest MoM decline, with a 39% decrease** compared to the previous month. While total revenue for 2022 still exceeded that of 2019, the last three months of the year recorded the lowest monthly revenues in the four-year period. 

## Seasonal Sales Trends
![Alt Text](MoM_Revenue_and_Revenue_Growth_Rate.png)

December consistently sees the strongest performance, with an average **29.17% increase in revenue** and **29.96% increase in order volume** compared to the previous month. 

The weakest months are October and February:
* October shows an average **19.54% decrease in revenue and 20.48% decrease in order volume**.
* February follows with an average **13.13% revenue decline and 16.56% drop in order volume**.

## Product Performance
**By revenue**, the top 4 performing products are:
* 27 in Gaming Monitor
* Apple Airpod Headphones
* Macbook Air Laptop
* ThinkPad Laptop

These products account for **96.37% of total revenue**.

**By order volume**, the top 4 products are:
* Apple Airpod Headphones
* 27 in Gaming Monitor
* Samsung Charging Cable Pack
* Samsung Webcam

These products account for **93.35% of all orders**.

Notably, the **27 in Gaming Monitor and Apple Airpod Headphones rank in the top 2 products** across both metrics, contributing:
* **62.56% of total revenue**
* **66.41 of all orders**

## Regional Performance
Revenue and Order Volume Trends:
* NA is the top performing region, contributing the largest share of both **revenue (51.69%) and order volume (51.8%)**.
* EMEA follows with **29.45% of revenue and 29.24% of orders**.
* APAC contributes **12.14% of revenue and 13% of orders**.
* LATAM accounts for the smallest share, with **6.73% of revenue and 5.96% of orders**.

AOV Trends:
* **APAC has the highest AOV**, averaging **7.07% above the global regional average** across all four years.
* **LATAM has the lowest AOV**, at **11.33% below the global average** overall, with significantly lower AOV in:
  * 2021: 14.74% below average
  * 2022: 28.48% below average

## Loyalty Program Performance
From 2019 to 2020, **non-loyalty members were the primary drivers of both revenue (80.16% of revenue) and order volume (75.32% of all orders)**. However, a major shift occurred starting in 2021:
* 2021: Loyalty members surpassed non-loyalty members in both **revenue (52.74%) and order volume (54.49%)**.
* 2022: Loyalty members continued to lead, contributing to **55.44% of revenue and 51.83% of orders**.
* Post September 2022: During the last months of 2022, the trend reversed, with non-loyalty members once again contributing more to **revenue (58.92%) and order volume (59.02%)**.

Looking at the overall 4-year trend:
* Loyalty members have shown an **overall growth in revenue (626.47%), order volume (511.25%), and AOV (18.87%)**.
* Non-loyalty members have declined across the same metrics, decreasing by **32.31% in revenue, 26.33% in order volume, and 8.1% in AOV**.  


# Deeper Dive
## APAC leads all regions in AOV, driven by a higher proportion of premium product sales
Upon closer analysis, we found that a **greater share of APAC's total orders consist of high-value products**, specifically the Macbook Air Laptop, ThinkPad Laptop, Apple iPhone, and 27 in 4K Gaming Monitor. These **four products account for a larger percentage of APAC's orders compared to other regions**, ranging from **9% to 60% higher**. Interestingly, while these products are more prominent in APAC's order mix, their **average selling prices are approximately 5.24% lower than in other regions**. 

**Despite the higher AOV, APAC's overall revenue trails behind NA and EMEA**, largely due to **lower overall order volume**. 

## Higher AOV products tend to have higher refund rates
The **top four products by AOV show notably higher refund rates compared to the overall product average**. In particular, the two highest AOV products stand out with the most significant differences. Across all years:
* **Macbook Air Laptops** had a refund rate of **11.47%**
* **ThinkPad Laptops** had a refund rate of **11.8%**
* **Apple iPhones** had a refund rate of **7.67%**
* **27in 4K Gaming Monitors** had a refund rate of **6.19%**
* In contrast, **all other products combined averaged a 4.03% refund rate**

It is worth nothing that **after July 2021, no additional refunds were recorded in the dataset**. While this may affect overall refund rate calculations, the trend of **higher refund rates among high AOV products remains consistent**. 

## Loyalty members have a lower time between orders compared to non-loyalty
Loyalty program members tend to reorder more frequently, with an average of **124 days** between repeat purchases, compared to **187 days** for non-members.

However, the overall number of repeat customers remains significantly higher among non-loyalty customers (4497) compared to loyalty members (154) across all four years. 

# Recommendations
## Capitalize on December boom, investigate October and February downturns
December's strong performance aligns with the holiday season, indicating an opportunity to further amplify promotional and marketing efforts during this high revenue period. 

Conversely, underperformance in October and February warrants investigation. 
* Are these seasonal trends consistent across the broader e-commerce landscape?
* Were there fewer campaigns or promotions during these months?

Understanding these dips will help identify whether this is an internal issue or part of a wider industry pattern.

## Accelerate growth via top-performing products (27in 4K Gaming Monitor and Apple Airpod Headphones) and strategically bundle items
The 27in 4K Gaming Monitor and Apple Airpod Headphones account for over 60% of total revenue and order volume. These products represent clear revenue drivers.

It is recommended to:
* Introduce product bundles featurng these top sellers to drive higher AOV
* Offer loyalty program incentives, such as loyalty point boosts, to increase visibility of both the products and the loyalty program.
* Explore strategic bundling of high AOV, lower order volume items (Macbook Air Laptop and ThinkPad Laptop) with low AOV, higher order volume items (Samsung Charging Cable Pack and Samsung Webcam) to boost performance across both categories 

## Continue investing in loyalty program, with close monitoring
Despite recent dip, the loyalty program has shown promising growth since 2019 and is positively correlated with repeat purchases. 

It is recommended to:
* Continue supporting the program in the short term while conducitng a cost-benefit analysis to ensure it remains ROI-positive.
* Closely monitor performance trends to determine whether the recent downturn is temporary or indicative of a longer-term shift.

## Opportunities in APAC, reassess strategy in LATAM
The APAC region shows strong AOV driven by purchases of premium products, which are priced more competitively compared to other regions.

It is recommended to:
* Increase marketing investing in APAC to further capture high-value customers.
* Evaluate feasibility of price adjustments in other markets to replicate APAC's success with high-cost products. 

In contrast, LATAM continues to underperform in both revenue, AOV, and order volume. 

It is recommended to:
* Reassess go-to-market strategy for LATAM, including pricing, product-market fit, and promotional tactics to better align with regional demand and customer behavior. 
