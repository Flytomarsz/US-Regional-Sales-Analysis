# US Regional Sales Analysis 📊

## Project Background
Analyzing factors in sales trend fluctuations during December 2020. This project aiming to give some actionable insights which useful for strategic decision-making in order to increase product sales.

Factors causing the decline and increase in sales across various states:
- **Marketing Analysis:** Sales team performance across different sales channels, including In-Store, Online, Distributor, and Wholesale.
- **Geography Factors:** Climate and weather influences on product sales, uneven population distribution on each different country, household income differences on each country.
- **Product Performance:** Price rate every product is not align with product demand.
- **Company Services:** The delivery time is too slow.

Issue Tree, SMART Analysis, and DARCI can be access here [https://whimsical.com/milestone-1-QDj4xuQHMEJwJcfjP1PP14]

ERD Diagram can be access here [https://dbdiagram.io/d/US-Regional-Sales-ERD-6798a274263d6cf9a044336a]

US Regional Sales Dataset on Kaggle [https://www.kaggle.com/datasets/talhabu/us-regional-sales-data/data]

## Tools
- Google Sheets
- Google Bigquery, MySQL Workbench
- Microsoft Power BI

# Data Structure & Initial Checks
Table description:
- **Sales_Order:** Information for each order.
- **Customers:** Customers detail information.
- **Store_Location:** Information of store location with different types of income and geography informations.
- **Product:** Detail of products information.
- **Region:** Detail of area in region.
- **Sales_team:** Sales team information.

![alt text](image.png)

# Executive Summary
### Overview of Findings
In 2020 California achieved the highest overall sales approaching 3.000. While other states had sales under than 1.500, even many states  are under 500. An analysis reveals significant drop in December 2020 with many states has reported zero sales, aside the other 5 states has maintained stable performance. The company want to investigate the factors affecting these sales spikes and declines.

Dashboard overview 
![alt text](image-1.png)

### Business Insight Overview
![alt text](image-2.png)
1. Total Order Quantity: 13.3K and total Revenue: $26.6M, suggesting strong revenue from these orders. The average revenue per order = $26.6M / 13.3K ≈ $2,000 per order. This implies a high-value product/service or bulk purchases.
2. Total Profit: $8M and total Unit Cost: $4.2M. Profit Margin = (Profit / Revenue) × 100 = (8M / 26.6M) × 100 ≈ 30%. The 30% profit margin is generally strong, indicating healthy pricing strategies and cost management.
3. Total Population: 892.1M and total Household Income: $320.5M. Average Household Income per Person = $320.5M / 892.1M ≈ $359 per person. This suggests a market with moderate spending power, meaning pricing strategies should align with customer affordability.

### Delivery Time Analysis
![alt text](image-3.png)
1. The dots on the scatter plot are randomly distributed without any clear pattern & relatively flat, indicating that the land area size does not influence delivery time.
2. Showing average delivery time between 15 to 25 days.

![alt text](image-4.png)
1. With this bar chart, it shows that majority of delivery time take more than 30 days (1,478 deliveries), while the fastest delivery time 0-5 days tracked for only 72 deliveries.

### Price and Demand Analysis
![alt text](image-5.png)
1. Based on the scatter plot, price influences order volume, but it is not the primary factor.
2. As order quantity increases, the unit price tends to rise, although with significant variation.

### Product Performance
![alt text](image-6.png)
1. This chart shows that order quantity impacts the revenue. 
2. The higher order quantity per product = the higher chance revenue per peroduct.

### Sales Team Performance
![alt text](image-7.png)
1. The number of orders impacts total revenue and average revenue for each state.
2. This chart shows that the sales with the highest orders do not necessarily generate the highest revenue

### Population & Household Income Analysis
![alt text](image-8.png)
1. The population and household income in each state affect both demand of orders and revenue in that state.

### Demography by Population Analysis
![alt text](image-9.png)
![alt text](image-10.png)
1. The Geomap shows that show that areas with large populations have larger circles. Example, California: Population 180 million with household income 58 million, order quantity 2,945 and revenue 5.74 million.
2. It shows Positive Correlation: The higher the population and household income, the greater the transaction and income opportunities.


## Recommendations:
Based on the insights and findings above, I would recommend the Marketing & Sales Team to consider the following: 
1. **Delivery Time**: Build multi-warehouses in the states and understanding the state's regional areas to better identify the suitable types of shipping for each region.
2. **Revenue**: Countries with lower sales compared to those with higher sales for the same product should adopt the sales strategies of the countries with higher sales.
3. **Product & Demand**: The most popular items will be produced in larger quantities, while the less popular items will be discounted for clearance.
4. **Population & Household Income**: Partnering with local supermarkets, distributors, or online shops to increase product recognition with consument behavior approaches.
5. **Sales Performance**: Top-performing salesman can receive bonuses, while lower performers get benefit for training and sharing sessions with high-revenue achievers.


## Conclutions:
1. Delivery time is not affected by area size or climate, highlighting the need for optimized logistics & customized delivery methods for different regions.
2. The volume of order directly affects revenue; Therefore, the low-performing regions can adopt strategies from high-performing regions to improve their results.
3. Population size & household income both are influence  the demand of orders also revenue.
4. The higher product prices do not significantly affect demand of orders.
5. Build multiple warehouses, effective sales strategies, and local partnerships are crucial for improving sales in low-performing regions.