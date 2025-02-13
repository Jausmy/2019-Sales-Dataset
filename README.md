# Data Portfolio: 2019 Sales Dashboard

![Project-Main-Image](Assets/Images/2019%20Sales%20Project%20Main%20Image.jpg)

## Overview
This report presents a comprehensive analysis of sales data for the year 2019, with a focus on identifying key trends, understanding product performance, and providing actionable insights to optimize sales strategies and maximize revenue. By examining monthly sales patterns, regional variations, and product-level performance, we aim to provide a data-driven foundation for informed decision-making and business growth.

## Executive Summary
This analysis was conducted to provide a comprehensive overview of sales performance in 2019. By examining key metrics such as total revenue, average order value, monthly sales trends, and product-level performance, we identified key trends and opportunities for improvement. A key insight from the analysis is that December emerged as the top-performing month with the highest revenue, while January had the lowest [(see Analysis of Monthly Sales Trends)](#Analysis-of-Monthly-Sales-Trends). Based on the analysis, we recommend capitalizing on peak sales seasons by implementing targeted marketing campaigns and promotions during high-revenue months like December, while exploring strategies to boost sales during slower months like January. By implementing these recommendations, the company can potentially increase overall sales by 15% and improve profitability [(see Potential Impact of Recommendations)](#Potential-Impact-of-Recommendations).

## Methodology
### Data Sources
The primary data source for this analysis is a sales database comprising 12 tables, each representing sales information for a corresponding month of 2019. Each table contains the following columns:
-	Order_ID
-	Product
-	Quantity_Ordered
-	Price_Each
-	Order_Date
-	Purchase_Address

### Tools Used
The following tools were used for data analysis and visualization:
-	Microsoft SQL Server Management Studio – Used to restore the database from a backup file and for data familiarization.
-	Microsoft PowerBI – Data visualization
-	Microsoft Power Query – Data cleaning and transformation

### Data Cleaning and Preparation
The following data cleaning and preparation steps were performed using Power Query:
-	Appended all monthly tables into a single table.
-	Removed rows with null values in the "Quantity_Ordered" column.
-	Corrected the format of the "Order_Date" column.
-	Split the "Purchase_Address" column into separate columns for street address, city, state, and zip code.
-	Created a calendar table with unique date values and added columns for year, month, day, and day name.

### Data Exploration
Initial data exploration involved familiarizing ourselves with the dataset and identifying key variables. This included examining the distribution of sales across different products, months, and cities.

### Data Analysis Techniques
The following data analysis techniques were employed:
-	Trend Analysis: We analyzed monthly sales trends to identify peak seasons and potential areas for improvement. This involved aggregating sales data by month and visualizing the trends to identify any seasonal patterns or significant fluctuations in sales performance.
-	Comparative Analysis: We compared sales performance across different cities and product categories to identify top-performing regions and products. This involved grouping data by city and product and calculating relevant metrics such as total revenue and average order value.
-	Diagnostic Analysis: This analysis was used to identify the root cause of the significant sales fluctuations observed throughout the year. By examining various factors such as seasonality, promotional campaigns, and product launches, we aimed to understand the underlying reasons for these fluctuations.

## Future Considerations for Data Analysis
In the future, we can leverage additional data analysis techniques to further refine our understanding of sales patterns and optimize sales strategies. These techniques include:
-	Customer Segmentation: This technique can be used to group customers based on their purchasing behavior (such as whether a sale enticed their purchase or not, are they a repeat customer or not), demographics, or other relevant characteristics. By understanding the unique needs and preferences of different customer segments, we can tailor marketing campaigns, personalize product recommendations, and improve customer satisfaction.
-	Predictive Modeling: This technique can be used to forecast future sales, predict demand for specific products, and optimize inventory management. By building statistical models based on historical sales data and relevant factors, we can anticipate future trends and make proactive decisions to improve sales performance.

## Analysis of Sales Performance
### Overall KPIs
The overall sales performance for 2019 is summarized by the following KPIs:

|KPI|Value|
|---|---|
|Total Revenue|$34.5M|
|Total Orders|186k|
|Average Order Value|$185|
|Total Products Sold|19|
|Month-over-Month Sales Change|44.2%|

### Analysis of Monthly Sales Trends
December emerged as the top-performing month with the highest revenue ($4.6M), while January had the lowest revenue ($1.8M). This highlights a potential peak sales season during the holiday period (extended black Friday sales and Christmas sales) in December and a slower period in January due to spending fatigue.

#### Top and Bottom Performing Months
Top 3 Months by Revenue

|Month|Revenue|
|---|---|
|December|$4.6M|
|October|$3.7M|
|April|$3.4M|

Bottom 3 Months by Revenue

|Month|Revenue|
|---|---|
|January|$1.8M|
|September|$2.1M|
|February|$2.2M|

This further emphasizes the need to capitalize on peak seasons and develop strategies to improve sales during slower months.

### Analysis of Sales by City
San Francisco generated the highest revenue ($8.3M), followed by Los Angeles ($5.5M) and New York City ($4.7M). Austin had the lowest revenue ($1.8M), followed by Portland ($2.3M) and Seattle ($2.7M). This suggests that San Francisco, Los Angeles, and New York City are key markets for the company, while sales in Austin, Portland, and Seattle may require further attention.

#### Top and Bottom Performing Cities
Top 3 Cities by Revenue

|City|Revenue|
|---|---|
|San Francisco|$8.3M|
|Los Angeles|$5.5M|
|New York City|$4.7M|

Bottom 3 Cities by Revenue

|City|Revenue|
|---|---|
|Austin|$1.8M|
|Portland|$2.3M|
|Seattle|$2.7M|

This highlights the importance of focusing on high-performing cities while exploring strategies to improve sales in underperforming regions.

### Analysis of Product Performance
The top 5 selling products were Macbook Pro Laptop, iPhone, Thinkpad Laptop, Google Phone, and 27in 4K Gaming Monitor, accounting for 65.9% of total revenue. The bottom 5 selling products were AAA Batteries (4-pack), AA Batteries (4-pack), Wired Headphones, USB-C Charging Cable, and Lightning Charging Cable, accounting for only 2.1% of total revenue. This indicates a significant concentration of sales in a few high-value products, while sales of lower-priced accessories are relatively low.

#### Top and Bottom Selling Products
Top 5 Selling Products by Revenue

|Product|Revenue|
|---|---|
|Macbook Pro Laptop|$8,037,600|
|iPhone|$4,794,300|
|Thinkpad Laptop|$4,129,958.70|
|Google Phone|$3,319,200|
|27in 4K Gaming Monitor|$2,435,097.56|

Bottom 5 Selling Products by Revenue

|Product|Revenue|
|---|---|
|AAA Batteries (4-pack)|$92,740.83|
|AA Batteries (4-pack)|$106,118.40|
|Wired Headphones|$246,478.43|
|USB-C Charging Cable|$286,501.25|
|Lightning Charging Cable|$347,095.15|

This highlights the importance of understanding product-level performance and developing strategies to optimize sales across the product portfolio.

## Recommendations
Based on the analysis of sales data, the following recommendations are proposed:
- Capitalize on Peak Seasons: Implement targeted marketing campaigns and promotions during high-revenue months like December to maximize sales during peak seasons. This could involve offering holiday discounts, bundling products, or running seasonal advertising campaigns.
-	Boost Sales During Slower Months: Explore strategies to increase sales during slower months like January. This could involve offering promotions, introducing new products, or targeting specific customer segments with tailored marketing campaigns.
-	Focus on High-Performing Cities: Allocate marketing resources strategically to focus on high-performing cities like San Francisco, Los Angeles, and New York City. This could involve opening new stores in these areas, increasing advertising spend, or partnering with local businesses.
-	Optimize Product Portfolio: Analyze product-level performance and develop strategies to optimize sales across the product portfolio. This could involve discontinuing or removing low-performing products, bundling products, or offering promotions on specific items.
-	Enhance Customer Experience: Improve the customer experience by providing excellent customer service, offering convenient payment and delivery options, and creating a positive brand image.

## Potential Impact of Recommendations
By implementing these recommendations, the company can anticipate the following positive outcomes:
-	Increased Sales: Capitalizing on peak seasons, boosting sales during slower months, and optimizing the product portfolio can potentially lead to a 15% increase in overall sales.
-	Improved Profitability: By effectively managing inventory, optimizing marketing spend, and enhancing the customer experience, the company can improve profitability and achieve sustainable growth.
-	Enhanced Customer Satisfaction: Focusing on customer needs and preferences can lead to increased customer satisfaction and loyalty.

## Limitations and Future Considerations
While this analysis provides valuable insights and recommendations, it's important to acknowledge certain limitations:
-	Limited Data: The analysis is limited to sales data for the year 2019. Analyzing sales data over a longer period would provide a more comprehensive understanding of sales trends and seasonality.
-	External Factors: External factors such as economic conditions, competitor actions, city populations, and changes in consumer behavior can influence sales performance and should be considered in future analyses.

## Key Takeaways
This analysis provides valuable insights into sales performance and product trends. Here are the key takeaways:
- December is a peak sales month: December generated the highest revenue, highlighting the importance of the holiday season for the company's sales performance.
-	San Francisco is a key market: San Francisco generated the highest revenue among all cities, indicating its importance as a target market.
-	Top-selling products drive a significant portion of revenue: The top 5 selling products accounted for 65.9% of total revenue, highlighting the importance of these products to the company's success.
-	Opportunities exist to improve sales in slower months and underperforming cities: By implementing targeted strategies, the company can potentially boost sales during slower periods and in underperforming regions.

By implementing the recommendations outlined in this report and continuously monitoring key performance indicators, the company can optimize its sales strategies, maximize revenue, and achieve sustainable growth.
