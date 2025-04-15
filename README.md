# Logistics-supply-chain
Identifying trends and patterns in shipment data.

# Shipment Performance Analysis Dashboard
1. Project Overview
Description: This project involves the development of an interactive dashboard using Power BI to analyze shipment performance data. The dashboard provides insights into key metrics such as total shipments, customer and supplier activity, shipment efficiency, delivery times, and delays. The analysis aims to help stakeholders understand shipment trends, identify areas for improvement in logistics operations, and make data-driven decisions to optimize delivery processes.
Purpose: The primary purpose of this project is to:
- Visualize key shipment performance indicators.
- Identify trends and patterns in shipment data.
- Enable users to explore and filter data to gain specific insights.
- Provide a tool for monitoring and improving logistics efficiency.
Target Audience: The dashboard is designed for a broad audience, including:
- Logistics managers
- Supply chain analysts
- Operations personnel
- Decision-makers involved in shipment and delivery processes
2. Skills Demonstrated
This project showcases the following data analyst skills:
- Data Visualization: Creating effective and interactive visualizations using Power BI to communicate complex information clearly.
- Data Analysis: Analyzing shipment data to identify trends, patterns, and areas for improvement.
- DAX (Data Analysis Expressions): Utilizing DAX to create calculated columns and measures for in-depth analysis (e.g., calculating shipment efficiency, average distance, and delay hours).
- Data Interpretation: Interpreting the visualized data to provide meaningful insights and recommendations.
- Dashboard Design: Designing a user-friendly and intuitive dashboard layout for easy navigation and data exploration.
- Data Cleaning and Transformation: (Assumed) Preparing the data for analysis, including cleaning, transforming, and loading it into Power BI.  (If you used Power Query, be sure to document those steps in section 4)
- Problem Solving: Addressing a real-world business problem by providing a data-driven solution.
3. Project Details
Tools Used:
- Power BI Desktop: For data connection, modeling, DAX calculations, and dashboard creation.
- Data Sources: 
Sample shipment data was provided in the form of a Xlxs file.  The data included shipment details such as shipment ID, customer ID, supplier ID, origin and destination, distance, shipment date, delivery date, material shipped, and delay hours.
- Key Metrics Analyzed:
1. Total Shipments
2. Total Customers
3. Total Suppliers
4. Average Distance
5. Shipment Efficiency
6. Customer Repetition
7. Utilization
8. Delay Hours
9. Delivery Time by Material Shipped
10. Total Shipments and Average Delay Hours by Material Shipped

- Visualizations Created: 

KPI cards to display key metrics at a glance (Total shipments, Total customers, Total suppliers, Avg distance)
Bar charts to visualize total shipment by supplier and top routes by shipment.
Line chart to show total shipments and average delay hours by material shipped.
Map visualization to show the total shipments by origin location.
Tables to display customer details.
Column chart to visualize total shipment by booking hour and delivery time by materials supplied
Slicers for filtering data by quarter and shipment type.
Pie chart visualization to highlight the total shipment by delay category

4. Data Preparation 
- Data Cleaning: 
1. Handled missing values in the delay hours column by replacing them with the average delay time for that material type.
2. Ensured data consistency in date formats.
3. Data Transformation: 
- Calculated shipment efficiency by dividing the actual delivery time by the estimated delivery time.
-Calculated customer repetition by counting the number of shipments for each customer.
4. Table separated into facts and dimension table and model was created as shown below.

  ![Star schema for logistics](schema-1.png)

- Data Loading: 
The cleaned and transformed data was loaded into Power BI Desktop using the "Get Data" functionality.

5. Dashboard Highlights
- Interactive Filtering: Slicers allow users to dynamically filter the data by quarter and shipment type, enabling them to focus on specific segments.
- Key Performance Indicators (KPIs): KPI cards provide a high-level overview of shipment performance, highlighting key metrics such as total shipments, efficiency, and delays.
- Trend Analysis: Visualizations such as the line chart  help identify trends in shipment volume and delay hours over time.
- Comparative Analysis: The bar chart enables comparison of delivery times across different materials shipped.
- Geographical Insights: The map visualization provides insights into the average distance covered by shipment routes.
- Customer Analysis: The table displays customer shipment activity.

6. Challenges and Solutions

- Challenge: Handling inconsistencies in the date format across different data sources.
Solution: Used Power Query to standardize the date format to ensure accurate analysis.
- Challenge: Visualizing a large number of shipment routes on a map without overcrowding.
Solution: Used appropriate zoom levels and tooltips to provide detailed information on demand.

7. Future Enhancements

Incorporate predictive analytics to forecast future shipment delays.
Implement real-time data updates for live shipment tracking.
Add more detailed information about shipping costs.
Expand the analysis to include carrier performance.

8. Conclusion

This project demonstrates the ability to develop a comprehensive and interactive dashboard for analyzing shipment performance data. The dashboard provides valuable insights for optimizing logistics operations, reducing delays, and improving overall delivery efficiency.  This project highlights my skills in data visualization, DAX calculations, and dashboard design, making it a valuable addition to my data analytics portfolio.  
