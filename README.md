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
  # 5. Card Creation for showing Total sum of Sales.
1. Created separate card to show sum of Total sum of Sales.
  # 6. Created a video explaining the visualizations.   

# Power BI Assignment-3
Assignment-3 provides a comprehensive analysis of Airbnb data,such as pricing analysis, occupancy rates, host performance, and customer reviews.The insights derived from this data aim to help optimize pricing strategies, improve customer experiences, and support decision-making for both hosts and Airbnb management.
# Steps Done
# 1. Data pre-processing
1. Promoted Headers of the uploaded file.
2. Renamed "name" column to "Apartment Name".
3. Removed empty rows from Apartment name column.
4. Filtered "Apartment Name" column to hide null and empty columns.
5. Removed column named "last review".
6. Removed errors from id column.
# 2. Airbnb Listing Analysis:Overview,Top 5 Apartment,Room Type Distribution
1. Plotted stacked Bar Chart showing no: of airbnb listings in neighbourhood.
2. Plotted stacked column chart showing Top 5 apartments by review.
3. Plotted pie-chart showing count of id by room type.
4. Plotted table showing details of host_name,neighbourhood, Sum of Reviews per Month and Apartment name.
5. Included necessary slicers like room_type, id, apartment, neighbourhood.
6. Created Cards showing separate count of apartment, average number of reviews and count of no: of days available.
7. Created Bookmark for Top 5 apartments. (Shown as separate button for easy selesction).
# 3.  Dynamic Pricing Insights by Room Type & Property
1. Plotted Coloumn Chart showing Average price variation by Room_type.
2. Plotted linechart showing Average price variation of apartment.
3. Created Card for Sum of Price and No: of reviews.
4. Added necessary slicers including price,apartment name and room_type.
5. Added navigation button.
# 4.  Geographical Distribution of Air bnb Listings
1. Plotted map view of no: of listings in neighbourhood and average price distribution by room_type, lattitude, longitude.
2. Created Card for Average of Price,Count of apartment and availability.
3. Plotted pie-chart showing count of apartment by neighbourhood_group.
4. Plotted scatterplot showing count of availability and average price.
5.  Added necessary slicers including price,neighbourhood and room_type.
     5. New York City-Airbnb Analysis Report
Created New york city airbnb analysis report incorperating necessary details like visualisations,tables,charts,cards,background images etc.

   # Key Insights Derived
 # 1. Price Trends:
   Identified the areas with the most expensive listings and how the prices vary across neighborhoods and by room_type.
 # 2. Availability:
   Analyzed the distribution of listings that are highly available throughout the year (No: of days available).
 # 3. Geographical Distribution:
   Identified the geographical distribution of proprties in neighbourhood and it's variation by price,room_type,availability etc.
 # 4. Review and Rating Analysis:
   Identified the average review rating,review frequency and the relationship with price and quality.
 # 5. Top 5 Listings:
    Identified top 5 apartments by review (Added bookmark for easy navigation).

  

