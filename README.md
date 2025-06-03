# Visualization Using PowerBI
## Overview:
In this task, I have taken a dataset Superstore_sales.csv from kaggle and performed visualizations on the data using the PowerBI software.

## Implementation Steps:
1. **Load The Dataset into PowerBI**:
   - Click "Get Data" → Choose CSV → Load Superstore_sales.csv file.
   - Check the data in Data View and make sure column types (like Date, Number) are correct.
2. **Clean and Prepare the Data**:
   - Ensure dates are parsed correctly.
   - Remove unnecessary columns if needed.
   - Create calculated columns or measures.
3. **Build Your Visual Story**:
   - Card Visuals for:
     - Total Sales
     - Total Profit
     - Number of Orders
   - Line Chart: Sales over time (use Order Date)
   - Pie Chart: Sales by Segment
4. **Shipping and Delivering**:
   - A new column is created in the data, DaysToShip = DATEDIFF('Table'[Order Date], 'Table'[Ship Date], DAY)
   - Scatter Chart is used to visualize Sum of Sales, Count of Order ID by Product Name.
5. **Customer Segment Analysis**:
   - Stacked Column Chart: Sales by ShipMode and SumofDaystoShip.
   - Histogram: DaysToShip by Count of Order ID



