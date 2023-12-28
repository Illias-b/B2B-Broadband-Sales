# B2B Broadband Sales Analysis Dashboard

## Overview
This repository showcases the B2B Broadband Sales Analysis Dashboard, which tracks broadband sales (5G and 4G) by week since September 2022. The dashboard provides insights split by sales channels (telesales, medium, retail) and city, aiming to assess the impact of regional marketing campaigns.

## Goal
The goal of the dashboard is to provide a comprehensive view of business broadband sales, highlighting trends in 5G and 4G product sales, and understanding the distribution across different sales channels and cities.

## Approach and Tools
The project involved multiple stages of data processing, visualization, and analysis:

- **Data Aggregation and Processing**:
  - Utilized SQL for initial data querying and table creation in the legacy database.
  - Employed Alteryx for transferring data to the Snowflake data warehouse, ensuring efficient data handling and preparation.
  - Alteryx Workflow Integration: The legacy data was combined with new world data using an Alteryx workflow, scheduled for daily updates to maintain data freshness and accuracy.

- **Dashboard Development**:
  - Developed an interactive dashboard in Tableau to visualize broadband sales over time, by product type, sales channel, and city.
  - The dashboard builds upon an existing report, adding a new dimension of city-wise sales data to gauge the impact of marketing efforts regionally.

## Results
The dashboard effectively captures and presents broadband sales data, providing key insights for business decision-making. The addition of city-wise sales data allows for a more granular analysis of market penetration and campaign effectiveness.

## Visualization and Code Snippets
- Tableau Dashboard Screenshot:
  - ![Tableau Dashboard for Broadband Sales](link-to-tableau-dashboard.jpg)
- Alteryx Workflow Screenshot:
  - ![Alteryx Workflow for Data Processing](link-to-alteryx-workflow.jpg)

(Note: Replace the image links with actual URLs to the Tableau dashboard and Alteryx workflow screenshots.)

This format offers a detailed view of the project, emphasizing the role of Alteryx in the data processing stage and showcasing the final dashboard output.
