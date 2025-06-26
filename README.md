# Elist E-commerce Analysis

# Project Overview
## Company Background
Elist, founded in 2018, is a global e-commerce company that sells popular electronics products through their online website and mobile app. They use a variety of marketing channels to reach customers, including Email campaigns, SEO, and affiliate links. Over the last few years, their more popular products have been products from Apple, Samsung, and ThinkPad.

## Data Structure
The database structure consists of four tables: orders, customers, geo_lookup, and order_status, with a total row count of 108,128 records.
![Alt Text](images/Elist_ERD.png)

## Project Goals
This project aims to provide insights and recommendations to inform sales and marketing strategies on the following key areas:
* Sales Metrics - Focused on Revenue, Average Order Value (AOV), and Order Count
* Product Performance - Analysis of sales metrics across products
* Global Reach - Analysis of sales metrics across global regions
* Loyalty Program Performance - Assessment of loyalty program's effectiveness
  
# Summary of Insights
## Seasonality
Regular spikes in December of every year, averaging 29.17% increase in revenue and 29.96% increase in number of orders from previous month.
Worst performing months are October, averaging 19.54% decrease in revenue and 20.48% decrease in order count, and February, averaging 13.13% decrease in revenue and 16.56% decrease in order count. 
## Products
By revenue, top 4 performing products are the 27 in gaming monitor, apple airpod headphones, macbook air laptop, and thinkpad laptop. They comprise 96.37% of all revenue. 
By number of orders placed, top 4 performing products are apple airpod headphones, 27 in gaming monitor, samsung charging cable pack, and samsung webcam. They comprise 93.35% of all orders
Across these two metrics, the top 2 products are the 27 in monitor and apple airpod headphones. They comprise 62.56% of all revenue and 66.41% of all orders (move down to recommendations)
## Region
In both revenue and number of orders, NA contributes the most (51.69% of all revenue, 51.8% all orders), followed by EMEA (29.45% revenue, 29.24% orders), APAC (12.14% revenue, 13% orders), and LATAM (6.73% revenue, 5.96% orders). 
However, in terms of AOV, APAC has the highest average AOV across all 4 years (7.07% higher than average across all regions). LATAM has the lowest (11.33% lower than average, 28.48% lower in 2022 and 14.74% lower in 2021)  
## Loyalty Program
Across all metrics, until 2021, non-loyalty members perform better than loyalty members by far. 
Starting from 2021, loyalty members contribute more across all metrics compared to non-loyalty members until late 2022, where their performance dipped below non-loyalty members again. 
Looking across 4 years, revenue, AOV,and order count have increased for loyalty members, but decreased for non-loyalty members. 
Loyalty program is worth keeping around for longer to continue to monitor trends. 


# Recommendations
