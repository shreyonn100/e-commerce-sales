# E-Commerce Sales-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/e502ac54-7b7d-4b43-bbf7-bdc82415d8f7/ReportSection?experience=power-bi

## Problem Statement

This dashboard aids the e-commerce company in gaining deeper insights into their sales performance. It enables the company to assess the ongoing status of their sales throughout the year. By leveraging various KPIs, they can pinpoint areas for enhancement, thereby enhancing their sales performance. Additionally, it provides valuable metrics such as average order value and quarterly sales, empowering them to address gaps in their sales process effectively. Through the utilization of this dashboard, they can proactively tackle issues contributing to sales discrepancies.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : For calculating average order value, amount values were divided by the number of orders for each customer. 
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Since the data contains various KPI's, thus in order to represent those, visual was added using the "card visual" in the visualizations pane in report view. 
- Step 7 : Visual filters (Slicers) were added for four quarters for tracking quarterly sales respectively.
- Step 8: Another slicer was added to reflect sales in respective states to understand the regional demography.
- Step 9: To visualize the sum of amount varying in each state, a clustered bar chart was added.
- Step 10: Another clustered bar chart was added to visualize the profit with respect to sub-category of the the products.
- Step 11: A donut chart was added to visualize quantity of sales with respect to each category.
- Step 12: To visualize the sum of amount order by each cutomer, a stacked column chart was added.
- Step 13: Another stacked column chart was added to visualize the profit with respect to each month of the year.

Visuals to represent different KPI's are mentioned below:

  (a) Sum of Amount

  (b) Sum of Profit
  
  (c) Sum of Quantity
  
  (d) Sum of Average Order Value
         
 - Step 14 : The report was then published to Power BI Service.
 
# Report Snapshot (Power BI Desktop)

![dashboard_snapo](https://github.com/shreyonn100/e-commerce-sales/assets/162843480/8f8b4a41-6a91-4eae-acb1-3a4642a17131)

# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://github.com/shreyonn100/e-commerce-sales/assets/162843480/6c899721-e809-4f48-a8e8-6f7ebbbd0cde)

# Snapshot of OrderID column

![Snap 1](https://github.com/shreyonn100/e-commerce-sales/assets/162843480/0d829ab1-e61c-48cd-ba78-5e9126419f48)

# Snapshot of Tiles

![Snap 2](https://github.com/shreyonn100/e-commerce-sales/assets/162843480/8ae49599-aa07-4a32-8805-4d92dab6e315)

![Snap 3](https://github.com/shreyonn100/e-commerce-sales/assets/162843480/d9d46670-a50e-467a-b74e-b9eb8d5efad9)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Customers = 500

   Number of states = 19

   Number of cities = 25

   Number of payment modes = 5

   Number of category = 3
   
   Number of sub-category = 17


 ### [2] KPIs

  (a) Sum of Amount- 438,000 

  (b) Sum of Profit- 37,000
  
  (c) Sum of Quantity- 5,615
  
  (d) Sum of Average Order Value- 121,000
  
  These KPIs will change if different visual filters will be applied.  
