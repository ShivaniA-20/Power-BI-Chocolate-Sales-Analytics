# Chocolate Sales Analytics - Power BI Project

## Summary

This project analyzes the sales performance of Chocolate Alchemy, a fictional chocolate company. The objective is to assess the performance of salespersons, products, and geographies while identifying trends and key metrics such as Total Sales, Total Profit, and Low Box Shipments. Month-on-month and year-on-year changes in metrics are also explored to support data-driven decision-making.

## Dataset
The dataset consists of five tables modeled in a star schema:

- __Fact Table__: Shipments
- __Dimension Tables__:
  1. Sales Person
  2. Product
  3. Geography
  4. Date


Each shipment represents chocolates sold by a salesperson for a specific product to a geography on a particular date.

## Objectives
1. Create an *star schema* model for Chocolate Sales using Power BI.

[Data Modelling.png](https://github.com/ShivaniA-20/Power-BI-Chocolate-Sales-Analytics/blob/4c5c357f6af241447403600c79673abb9b015501/Data%20Modelling.png)

2. Calculate and analyze key metrics, including:
   - Total Sales
   - Total Boxes
   - Total Shipments
   - Total Cost
   - Total Profit
   - Profit Percentage
   - Low Box Shipments and their percentage
   - Month-on-month changes in sales and profit
3. Build dynamic, interactive dashboards to uncover actionable insights.

## Steps
1. __Data Preparation__:
- Loaded the data into Power BI and created a star schema model.
- Built relationships between the Fact table and Dimension tables.

2. __Data Transformation__:
- Cleaned and transformed the data using Power Query Editor.
- Created measures for KPIs like Total Sales, Profit Percentage, and Month-on-Month Changes.
  
3. __Visualization__:
- Developed interactive dashboards with visuals like Stacked Bar Charts, Line Graphs, Cards, and TreeMaps to analyze data comprehensively.


## Visualizations
1. __Profit Analysis by Product__:
- Displayed profit across products using a Stacked Bar Chart. Peanut Butter Cubes were the most profitable product, while Bakers Choco Chips underperformed.

[  Profit Analysis by Product.png](https://github.com/ShivaniA-20/Power-BI-Chocolate-Sales-Analytics/blob/78fead952d03673b779341b617dc19d98bb12ea3/Profit%20Analysis%20by%20Product.png)
 
2. __Low Box Shipments__:
- Created a KPI to track shipments with fewer than 50 boxes, revealing inefficiencies in operations. Milk Bars had the highest Low Box Shipments (LBS).

[  Profit Analysis by Product.png](https://github.com/ShivaniA-20/Power-BI-Chocolate-Sales-Analytics/blob/78fead952d03673b779341b617dc19d98bb12ea3/Low%20Box%20Shipments.png)
 
3. __Month-on-Month Trends__:
- Analyzed changes in Total Sales and Profit using Line Graphs to detect seasonal trends and performance patterns.

  https://github.com/ShivaniA-20/Power-BI-Chocolate-Sales-Analytics/blob/78fead952d03673b779341b617dc19d98bb12ea3/Month-on-Month%20Trends.png

4. __Salesperson Performance__:
- Visualized individual performance using Bar Charts to identify top-performing salespersons.

https://github.com/ShivaniA-20/Power-BI-Chocolate-Sales-Analytics/blob/78fead952d03673b779341b617dc19d98bb12ea3/Salesperson%20Performance.jpg

## Analysis and Findings
__Product Performance Analysis__
- __Top Products by Profit__: Identified that Peanut Butter Cubes generate the highest profit, while Bakers Choco Chips exhibit lower profit margins.
- __Low Box Shipment Count__: Analyzed shipments with fewer than 50 boxes, revealing 624 such shipments out of a total of 6,113.

__Shipment Volume Analysis__
- __Low Box Shipment (LBS) by Product__: Visualized LBS across products, showing Milk Bars lead in shipments with fewer than 50 boxes.

__Month-on-Month and Year-on-Year Trends__
- __Total Sales and Profit Trends__: Tracked month-on-month and year-on-year changes in Total Sales and Total Profit, identifying seasonal spikes and steady growth in specific months.
- __Profit Percentage Analysis__: Calculated the profit percentage to evaluate overall profitability across geographies and products.

__Geography and Salesperson Analysis__
- __Top Performing Salespersons__: Analyzed individual performance metrics for salespersons, highlighting key contributors to Total Sales and Total Profit.
- __Geography-wise Insights__: Explored regional variations in shipments and profit to identify high-performing geographies for strategic focus.

__Cost and Efficiency Analysis__
- __Total Cost and Profit Correlation__: Evaluated the relationship between Total Cost and Profit to ensure operational efficiency.
- __Low Box Shipment Percentage__: Assessed the percentage of shipments with fewer than 50 boxes to address inefficiencies in logistics.

## Conclusion
This project provided a comprehensive analysis of Chocolate Alchemy’s sales data. Insights such as high-profit products, low-box shipment inefficiencies, and month-on-month trends help drive better business decisions. The dashboards deliver actionable insights for improving sales strategies and operational efficiency.
