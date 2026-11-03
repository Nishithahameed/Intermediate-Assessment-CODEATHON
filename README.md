# Intermediate-Assessment-CODEATHON

1.Data Cleaning

Fixed date locale formatting issues in Power Query.
Handled missing text values.
Converted numerical columns (UnitPrice, Sales, Cost, Profit) to decimal numbers.
Removed duplicate rows

2. Visualizations

Pie Chart: Regional distribution of orders.   
Column Chart: Top 5 trending products using a Top N OrderID count filter.
Line Chart: Profit trend over time.   

3. DAX Calculations

Calculated Table (EastRegionOrders)
Filter for East region orders.   
Calculated Column (ProfitCostDifference)
[Profit]-[cost]   
Calculated Measure (TotalProfit)
SUM([Profit]).   
