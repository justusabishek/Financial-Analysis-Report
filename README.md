# Financial-Analysis-Report-Dashboard

## Dashboard Link : https://app.fabric.microsoft.com/groups/df73a4db-b0f9-4bd7-9cc7-4cd8cef9aac0/reports/b8c63231-bc28-4214-a390-cb5412b72ae3/4de0836d2984ca68b6d4?experience=fabric-developer

## Problem Statement

This dashboard consolidates multiple financial datasets to provide insights into demand, supply, profit, and loss. It enables businesses to identify shortages, track profitability, and monitor daily financial trends. By integrating three datasets into a unified model, the dashboard supports better financial planning and operational optimization.

## Steps followed

 - Step 1 : Connected three datasets to MySQL Server.

 - Step 2 : Performed basic data cleaning in MySQL (handled nulls, standardized column names, removed duplicates).

 - Step 3 : Connected the cleaned datasets to Power BI Service through a Dataflow.

 - Step 4 : Configured the Dataflow for scheduled refresh and transformations.

 - Step 5 : Connected the Dataflow output into Power BI Desktop.

 - Step 6 : Built relationships between the datasets to create a unified data model.

 - Step 7 : Created DAX measures for KPIs such as Average Demand per Day, Average Availability, Supply Shortage, Total Profit, and Total Loss.

 - Step 8 : Designed visuals including card KPIs, line charts for trends, bar charts for product-level comparisons, and pie charts for category-wise distribution.

 - Step 9 : Added slicers for filtering by Product Name, Order Date, and Region.

 - Step 10 : Styled the dashboard with a professional theme and published it to Power BI Service.

## Snapshot of Dashboard (Power BI Service)
<img width="960" height="441" alt="Image" src="https://github.com/user-attachments/assets/f41c2e84-4873-4b74-a755-a3962595ed69" />

<img width="960" height="384" alt="Image" src="https://github.com/user-attachments/assets/01414b4c-3846-41f3-b146-773d966b96c4" />

## Insights
A multi-page report was created in Power BI Desktop and published to Power BI Service.

### [1] Demand & Supply
Average Demand per Day = 48.6

Average Availability per Day = 24.7

Total Supply Shortage = 61.2K  
 Demand consistently exceeds availability, highlighting supply chain inefficiencies.

### [2] Profit & Loss
Total Profit = 300.5K

Total Loss = 7.6M

Average Daily Loss = 3.0K  
 Losses significantly outweigh profits, requiring corrective strategies.

### [3] Trend Analysis
YOY trends show fluctuations in demand and profitability.

Certain product categories contribute disproportionately to losses.
 Suggests targeted interventions in underperforming segments.
