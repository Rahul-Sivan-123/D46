# D46
Power BI Assignment-1 submission

# Power BI Assignment-1
Assignment-1 is about data transformation using Power Query.

# Steps Done
1. Changed the headers of the uploaded file (orders,people,Returns).
2. Removed blank rows.
3. Removed duplicates.
4. Sorted rows("row ID" in ascending order)
5. Splitted column by delimiter (product name to  product name.1 & product name.2)
   
# Power BI Assignment-2
Assignment-2 is about data visualization and sales report creation using power BI. 
# Steps Done
  # 1. Pre-processing of data
1. Changed the headers of the uploaded file (orders,people,Returns).
2. Removed blank rows.
3. Removed duplicates.
4. Removed postal column(as it was 80% empty).
  # 2. Calculated Total Shipping Percentage based on Ship mode using DAX
     1 . Total Shipping Percentage based on shipping mode="DIVIDE(SUM(Orders[Shipping Cost]),CALCULATE(SUM(Orders[Shipping Cost]),ALL(Orders[Ship Mode])))"
  # 3. Data visualization and Report 
 1. Added slicers based on country,region and market for visualization.
 2. Plotted Stacked Column Chart on Total Shipping Percentage vs Category & shipping mode.
 3. Plotted Stacked Bar Chart on Total Sales over City.
 4. Plotted Aerial Map View on Total Sales over Region.
 5. Plotted Line Chart on Total Sales over State.
 6. Plotted Pie Chart on Total Sales over Market.
  # 4. Table Creation for Visualization  
1. Created Tables projecting sum of sales across city,region,state and market.   
2. Created Table showing ship mode,sum of shipping cost and total shipping percentage.
  # 5. Card Creation for showing Total shipping Percentage based on ship mode.
1. Created separate card to show Total shipping Percentage based on Ship mode.
  # 6. Created a video explaining the visualizations.   
