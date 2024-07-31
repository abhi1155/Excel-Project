# Store Sales Data Analysis Using Microsoft Excel


### Note - For Data Refer Store Data Sheet from Excel file.
# Problem Statement

The objective of this project is to perform a comprehensive analysis of store sales data using Excel to identify trends and patterns in sales, understand customer behavior, and generate actionable insights for future decision-making. This involves leveraging pivot tables, slicers, and dynamic charts to transform and clean the data, ensuring it is accurate and ready for in-depth analysis. By examining monthly sales, order counts, sales distribution by gender, average orders across different age groups, order statuses, and orders received from various enterprise channels, the project aims to provide a data-driven foundation for strategic business planning and optimization.


# Objectives

1. Trend Identification: Analyze monthly sales data to identify significant trends and seasonal patterns, enabling the store to anticipate demand fluctuations and optimize inventory management.

2. Customer Behavior Analysis: Examine sales distribution across different customer demographics such as gender and age groups to understand purchasing behaviors and tailor marketing strategies accordingly.

3. Performance Metrics Evaluation: Assess key performance indicators, including order counts and order statuses, to evaluate the efficiency of sales processes and identify areas for improvement in order fulfillment and customer satisfaction.

4. Channel Performance Analysis: Investigate the performance of various enterprise channels through which orders are received, providing insights into the most effective sales channels and guiding future investments in marketing and distribution.

# Steps followed 

- Step 1 : Data Cleaning - Ensure all data field have proper values, ensure data has no missing values.
- Step 2 : It was observed that in none of the columns errors & empty values were present.
- Step 3 : Data Modification - it is Observed that gender Column has different values for men i.e Men & M same applied for women so we modified it.
- Step 4 : Data Modification - it is observed that in Qty column has different value for count i.e 1 & one same in case of 2 so we modified it.
- Step 5 : Data Processing - We created Extra column Age group to summerise age in catagories (Teenager, Adult, Senior)
- Step 6 : Data Processing - We created month column to extract only month from date column for this we used (=text(cellno,"mmm")) formula.
- Step 7 : for Data Analysis we performed following steps
- Step 8 : We used Clustered Column Chart to show Sales based on Gender & Age for this we have created pivot table using age,gender & Count of order id field.
- Step 9 : We used Pie chart to show order status (Delivered, Cancelled, Returned, Refunded). for this we created pivot table using status column &  Order id field from sheet
- Step 10 : Secondly we have used Bar Chart to show top contributing states in Total sales by using State column & taking sum of Amount from sheet.
- Step 11 : we used pie chart to show performance of various enterprise channels through which orders are received. for this we used channel & order id column from sheet.
- step 12 : we used pie chart to show sales based on gender
- step 13 : To Get the data based on our requirement we created Slicers for Month, Channel & Category.

# Report Snapshots

<img width="694" alt="Screenshot 2024-07-31 095827" src="https://github.com/user-attachments/assets/bcc182d8-e8b8-479c-976f-efb38741e847">

# Conclusion & Insights
1) Women are more likely to buy compared to men (~65%)
2) Maharashtra, Karnataka and Uttar Pradesh are the top 3
3) Adult age group (30-49 yrs) is max contributing (~50%)
4) Amazon, Flipkart and Myntra channels are max contributors.

Final Conclusion -- To improve Store sales: Target women customers of age group (30-49 yrs) living in Maharashtra, Karnataka and Uttar Pradesh by showing ads/offers/coupons available on Amazon, Flipkart and Myntra


  
