# Sales_Data_Analysis_Excel
## Overview
In this project, I analyzed e-commerce sales data using Excel to extract key insights that could help improve business decisions. The analysis focused on identifying trends, product performance, customer distribution, payment methods, and the relationship between quantity sold and total sales. I utilized various Excel features, including PivotTables, formulas, and charts, to answer the business questions and generate insights.
## Project Questions
1. What is the overall trend of sales over time?
   
2. Which product category generates the highest revenue, and how does it compare to other categories?
   
3. Which cities have the highest number of orders, and what percentage of total orders do they represent?
   
4. What is the average order value (AOV) across different payment methods?
   
5. What is the correlation between quantity sold and total sales across different product categories?

# Question 1: What is the overall trend of sales over time?
### Results
I found that sales exhibited an upward trend, with noticeable peaks in January and April, suggesting these months had higher customer activity.

### Analysis Process
+ I extracted the month from the order date using the TEXT function.
+ Then, I created a PivotTable to summarize total sales by month.
+ I used a line chart to visualize the sales trend over time.
### Insights
The upward sales trend, especially during certain months, indicates seasonality or the impact of specific marketing campaigns. This insight could be useful for planning inventory and promotions during peak periods.

# Question 2: Which product category generates the highest revenue, and how does it compare to other categories?
### Results
The Electronics category brought in the highest revenue, followed by Clothing, while categories like Books and Home & Kitchen contributed less overall.

### Analysis Process
+ I created a PivotTable to sum total sales by product category.
+ I then used a bar chart to compare revenue across the different categories.

### Insights
Electronics clearly leads in revenue, suggesting strong demand and possibly higher-priced items. Focusing on this category could be beneficial, while exploring reasons for the underperformance of other categories like Books might offer further opportunities.

# Question 3: Which cities have the highest number of orders, and what percentage of total orders do they represent?
### Results
I discovered that New York and London accounted for the highest number of orders, making up a large portion of the total. Other cities, such as Paris and Tokyo, contributed but were less significant in terms of volume.

### Analysis Process
+ I used a PivotTable to count orders by city.
+ I applied percentage formatting to show each city’s share of total orders.
+ To visualize the data, I created a pie chart.

### Insights
With New York and London dominating the order volume, it's clear these cities are crucial markets. This could reflect the company's strong presence or effective marketing in those areas. Optimizing for smaller markets could lead to further growth.

# Question 4: What is the average order value (AOV) across different payment methods?
### Results
I found that Bank Transfer had the highest AOV, followed by Credit Card payments. PayPal, on the other hand, had a lower AOV.

### Analysis Process
+ I built a PivotTable to sum total sales and count the number of orders by payment method.
+ Then, I manually calculated the AOV by dividing total sales by the number of orders for each payment method.
+ I used a comparison chart to display the differences in AOV across the payment methods.

### Insights
The higher AOV for Bank Transfer could indicate that customers using this method tend to place larger orders. Investigating why PayPal orders are smaller might lead to insights on how to increase order value for this payment method.

# Question 5: What is the correlation between quantity sold and total sales across different product categories?
### Results
The correlation between Quantity Sold and Total Sales in the dataset was close to 0, indicating a weak relationship between the two variables.

### Analysis Process
+ I used a PivotTable to summarize quantity sold and total sales by product category.
+ I then applied the CORREL function to calculate the correlation between the two columns.

### Insights
The weak correlation between quantity sold and total sales implies that selling more units doesn’t necessarily result in significantly higher revenue in this dataset. This is likely because the quantity sold is mostly constant across categories, while total sales vary widely due to product pricing. It suggests that increasing revenue may rely more on optimizing pricing strategies rather than just increasing the number of units sold.

# Conclusion
This project allowed me to dive into real-world business data and derive meaningful insights using Excel. Through answering these questions, I gained a deeper understanding of product performance, customer distribution, payment methods, and the dynamics between sales quantity and total revenue. These insights can be useful in shaping business strategies, optimizing pricing and targeting high-revenue product categories. I also uncovered valuable insights that can help drive business decisions, such as focusing on high-revenue product categories and optimizing marketing efforts in high-performing cities.
