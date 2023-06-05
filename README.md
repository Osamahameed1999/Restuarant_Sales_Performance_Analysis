# Restaurant Industry - Sales Data Analytics Project

This repository contains the code and analysis for a data analytics project related to the restaurant industry. The goal of this project was to analyze sales data and provide insights and recommendations to improve gender balance at the executive management level.

## Background

This project aims to analyze and improve the sales performance within the restaurant industry. By leveraging data-driven insights and advanced analytics, we seek to identify key factors impacting sales, optimize pricing strategies, and enhance overall revenue generation.

## Project Objectives
- Identify trends and patterns in sales data to gain a comprehensive understanding of the restaurant industry landscape.
- Analyze customer preferences, behavior, and demographics to develop targeted marketing strategies and increase customer acquisition.
- Optimize pricing strategies to maximize revenue while maintaining competitive pricing within the market.
- Implement data-driven forecasting models to predict future sales and optimize inventory management.
- Explore opportunities for upselling and cross-selling to increase average order value and customer satisfaction.
- Enhance operational efficiency by identifying areas for process improvement and automation.
- Leverage customer feedback and sentiment analysis to improve overall dining experiences and increase customer loyalty.

## Expected Impact
Increased sales revenue through targeted marketing campaigns and pricing optimization.
Improved customer satisfaction and loyalty resulting from enhanced dining experiences.
Enhanced operational efficiency and cost savings through process improvements and automation.
Data-driven decision-making to drive business growth and maintain a competitive edge within the restaurant industry.

## Task Description

The task involved analyzing daily sales data and division information provided in two Excel sheets. The first sheet contained the daily sales table, including dates, location IDs, daily actual sales, covers, budget sales, and delivery sales. The second sheet contained the location IDs and divisions.

## Process

The following steps were followed to complete the data analytics task:

1. Data Exploration: The data was explored to gain an understanding of its structure and identify any potential issues or anomalies.

2. Data Transformation and Cleaning: The data was transformed and cleaned by removing duplicates, standardizing data formats, and mapping essential attributes required for analysis.

3. Build Relationship: A relationship was established between the daily sales table and the division table using the location ID as the primary key in the division table and the foreign key in the daily sales table.

4. KPI Building: Key performance indicators (KPIs) were defined based on stakeholder needs and a comprehensive understanding of the data.

5. Calculating Measures: Measures were calculated using Data Analysis Expressions (DAX) in Power BI to support the defined KPIs.

6. Visualization: Four dashboards were created, including three KPI visualizations and a welcome page providing a summary of the KPIs. The dashboards included line graphs, tables, ribbon charts, and other relevant visual representations.

## Insights

The analysis of the data provided the following insights:

![1](https://github.com/Osamahameed1999/Restuarant_Sales_Performance_Analysis/assets/129226747/f739d403-fff4-447a-8009-acfce5800c75)

### KPI #1: Sales Trend by Division
- Japanese division had the highest sales, followed by the American, Indian, and English divisions.
- The sales trend for each division followed a similar pattern, with a slight decline observed in May.

![2](https://github.com/Osamahameed1999/Restuarant_Sales_Performance_Analysis/assets/129226747/50347d99-6e03-4184-9552-e4242b7d4e78)

### KPI #2: Sales Comparison by Time
- The Japanese division consistently had the highest sales compared to the other divisions across different time periods.

### KPI #3: Sales vs Budget
- Actual sales and budgeted sales were generally aligned across months and divisions.

![3](https://github.com/Osamahameed1999/Restuarant_Sales_Performance_Analysis/assets/129226747/7e48aa34-14b1-496f-8cf3-2b162de3ab66)

### KPI #4: Top Performers vs Worst Performers
- The Japanese division was the top performer, contributing the highest share of actual sales.

### KPI #5: Delivery Sales Trend
- The delivery sales trend declined from March to May, with the Japanese division having the highest delivery sales.

![4](https://github.com/Osamahameed1999/Restuarant_Sales_Performance_Analysis/assets/129226747/376fde69-62e9-4a76-a13c-3b00072f1f7e)

## Recommendations

Based on the insights gained from the data analysis, the following recommendations are provided:

1. Focus on the Japanese division to learn from its successful strategies and practices.

2. Investigate the decline in sales during May to identify potential causes and address any underlying issues.

3. Analyze the worst-performing divisions to identify root causes and develop strategies for improvement.

4. Investigate the decline in delivery sales from March to May and implement strategies to reverse the trend.

5. Evaluate the budgeting process and ensure better alignment with actual sales.

6. Promote cross-division knowledge sharing to foster best practices and innovation.

7. Continuously monitor and track progress towards diversity and inclusion goals.

8. Foster an inclusive company culture through awareness, education, and training programs.

## Conclusion

The Restaurant Industry Data Analytics Project provided valuable insights into the performance of different divisions and identified areas for improvement. The recommendations aim to address the root causes of slow progress in achieving gender balance at the executive management level and promote a more inclusive and successful organization.

## Usage Instructions

- Access the raw dataset file, "task_data_set.xlsx", this file contains the original dataset used for analysis.
- Review the project description document, "project_description.docx," located in the root folder. This document provides an overview of the project, its objectives, and the analysis performed.
- Open the main dashboard in Power BI by accessing the "main_Dashboard.pbix" file located in the root folder. This Power BI file contains the visualizations and insights generated from the analysis.
- Alternatively, you can refer to the "dashboard_pdf" file located in the root folder. This PDF file contains snapshots of the main dashboard visualizations for reference.

