# Amazon-Product-Sales-Analysis-Power-BI-n-Excel
Sales Analysis of Amazon Product using Power BI and Excel


# Sales Analysis Dashboard with Power BI

## Overview

This repository contains a Power BI dashboard aimed at providing comprehensive insights into sales performance and product analysis for a company. The dashboard utilizes various functions and techniques such as data cleaning, modeling, processing, Power Query, DAX functions, time intelligence functions, and more.


![Screenshot 2024-03-26 225643](https://github.com/rahulmaurya255/Student-Scores-Machine-learning/assets/155320538/1793f2ad-6717-40d9-b035-9e19234f1bc2)


## Problem Statement

The dashboard addresses the need to monitor sales performance, track product movement, and analyze customer feedback. By utilizing various KPIs and charts, the dashboard aims to provide actionable insights to improve business strategies and decision-making processes.

## Functions Used

- Data cleaning
- Data modeling
- Data processing
- Power Query
- Data tables
- Time intelligence functions
- DAX functions
- Date functions
- Text functions
- Filter functions
- Calculations (e.g., YTD, QTD)
- Custom sorting
- Formatting
- Conditional formatting
- Creating new visualizations
- Creating functions
- Navigations

## Key Performance Indicators (KPIs) Requirement

### KPIs Tracked

- YTD Sales: Monitors year-to-date sales to assess overall revenue performance over time.
- QTD Sales: Tracks quarterly sales figures to identify sales trends and fluctuations.
- YTD Products Sold: Analyzes the total number of products sold throughout the year to understand product movement.
- YTD Reviews: Keeps tabs on year-to-date product reviews to assess customer feedback and satisfaction.

## Charts Requirement

### Charts Included

- YTD Sales by Month (Area Chart): Visualizes sales trends over time on a monthly basis to identify seasonal patterns and growth trends.
  
![image](https://github.com/rahulmaurya255/PowerBI-Intellipaat-Assignments/assets/155320538/bfeb949b-9e47-47f9-9658-86c0429d9bab)



- YTD Sales by Week (Column Chart): Displays sales data on a weekly basis to pinpoint shorter-term fluctuations and performance insights.
  
![image](https://github.com/rahulmaurya255/PowerBI-Intellipaat-Assignments/assets/155320538/7a7f2bcf-2331-4f35-99dd-340d932c5866)







- Sales by Product Category (Matrix)
  
![image](https://github.com/rahulmaurya255/PowerBI-Intellipaat-Assignments/assets/155320538/3ea38226-f92c-4233-bcc7-40be3ad68fd7)






 

- Top 5 Products by YTD Sales (Stacked Bar Chart): Highlights the top-performing products based on year-to-date sales to focus on key revenue generators.
  
![image](https://github.com/rahulmaurya255/PowerBI-Intellipaat-Assignments/assets/155320538/ac3bb8c0-aa2c-45ae-8e35-7aa78801bcca)










- Top 5 Products by YTD Reviews (Stacked Bar Chart): Identifies the top-rated products by year-to-date reviews to understand customer preferences.
  
![image](https://github.com/rahulmaurya255/PowerBI-Intellipaat-Assignments/assets/155320538/86ec3041-b259-4105-9425-78d62e16115f)








 

## Steps Taken

1. Loaded data into Power BI.
2. Checked for null, error, and valid values in the dataset.
3. Created a new date table using the calendar function, defining the min/max order date.
4. Created a month column in the 'order date' table.
5. Joined the 'order date' table with the main data table on the 'order date' and 'date' columns to establish a one-to-many relationship.
6. Created new measures for YTD Sales, QTD Sales, YTD Products Sold, and YTD Total Reviews.
7. Created Card Visuals to display all YTD KPIs.
8. Created an Area Chart of Sales by Month and sorted it in ascending order to analyze monthly sales trends.
9. Created a bar chart to analyze sales by week, utilizing a newly created week number column.
10. Created stacked bar charts for the top 5 products by YTD sales and YTD reviews, using the TOP N filter option.
11. Created a Quarter column to facilitate quarter-based analysis.
12. Implemented slicers for product category and quarter.



## Conclusion

The dashboard provides comprehensive insights into sales performance and product analysis, enabling the company to make informed decisions and improve business strategies.

For visual representations and snapshots of the dashboard, please refer to the images provided in the repository.


