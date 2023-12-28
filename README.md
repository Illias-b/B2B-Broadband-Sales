# B2B Broadband Sales Analysis Dashboard

## Overview
This repository showcases the B2B Broadband Sales Analysis Dashboard, tracking broadband sales (5G and 4G) by week since September 2022. The dashboard provides insights split by sales channels (telesales, medium, retail) and city-wise sales distribution, aiming to assess the impact of regional marketing campaigns.

## Goal
The goal of the dashboard is to offer a comprehensive view of business broadband sales, highlighting trends in 5G and 4G product sales across different sales channels and cities.

## Approach and Tools
The project involved multiple stages of data processing, visualization, and analysis:

- **Data Aggregation and Processing**:
  - Utilized SQL for initial data querying and table creation in the legacy database.
  - Employed Alteryx for transferring data to the Snowflake data warehouse.
  - Alteryx Workflow Integration: Combined legacy and new world data using Alteryx, scheduled for daily updates.

- **Dashboard Development**:
  - Developed an interactive Tableau dashboard to visualize broadband sales over time, by product type, sales channel, and city.
  - **Map Visualization**: Incorporated a map view to geographically represent sales data, making it easier to visualize regional sales distribution and identify areas with high market penetration or potential for growth.
  - **Bar Graph Breakdown**: Added a bar graph to present city-wise sales data, allowing for a quick comparative analysis of sales performance across different cities.

## Results
The dashboard effectively captures and presents broadband sales data, providing key insights for business decision-making. The inclusion of city-wise sales data and geographical representation allows for a granular analysis of market penetration and campaign effectiveness.

## Visualization and Code Snippets
- Tableau Dashboard Screenshot:
  - ![Tableau Dashboard for Broadband Sales](link-to-tableau-dashboard.jpg)
- Alteryx Workflow Screenshot:
  - ![Alteryx Workflow for Data Processing](link-to-alteryx-workflow.jpg)
- Map Visualization Screenshot:
  - ![Map Visualization of Sales](link-to-map-visualization.jpg)
- Bar Graph Breakdown Screenshot:
  - ![Bar Graph of City-wise Sales](link-to-bar-graph.jpg)

(Note: Replace the image links with actual URLs to the Tableau dashboard, Alteryx workflow, map visualization, and bar graph breakdown screenshots.)

This format offers a detailed view of the project, emphasizing the role of Alteryx in the data processing stage and showcasing the final dashboard output, including the map and bar graph visualizations for enhanced analysis.
