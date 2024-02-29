# B2B Monthly Performance Dashboard

## Introduction

The B2B Monthly Performance Dashboard is designed to consolidate and streamline reporting across all functions and products in the B2B sector. This project aims to transition from Excel-based reporting to a more integrated, dynamic dashboard solution. The goal is to provide a one-stop reporting platform that caters to the diverse needs of various teams within the organisation.

## Goals

The primary objective of this dashboard is to offer monthly insights into the performance of B2B functions and products. It encompasses two main dashboards:
1. **High-Level Overview Dashboard:** Offers a broad perspective on performance metrics across different B2B functions and products.
2. **Detailed Sales and MRC Breakdown Dashboard:** Provides granular insights into actual sales figures, MRC (Monthly Recurring Charge) breakdowns, and other detailed metrics.

Key goals include:
- Enhance decision-making processes by providing comprehensive data insights.
- Facilitate cross-functional team access to relevant, up-to-date information.
- Reduce reliance on manual, Excel-based reporting methods.

## Methodology

The dashboard is built upon a complex SQL query that aggregates and transforms data from various sources within the organization's data warehouse. This query is specifically designed to capture the latest actions for all subscribers, their earliest acquisition metrics, and detailed breakdowns of sales and MRC figures.

### Technical Overview

- **Data Sources:** Consolidation of data from multiple B2B-related tables and views.
- **SQL Query:** Utilises CTEs (Common Table Expressions) to structure the data preparation process, ensuring that the final view is optimised for dashboard consumption.
- **Tools Used:** SQL for data querying and extraction; Tableau for dashboard creation and visualisation.

## Dashboards Overview

### High-Level Overview Dashboard
- **Purpose:** To provide a snapshot of overall B2B performance across different functions and products.
- **Features:** Interactive filters, KPI metrics, trend analysis graphs.

- ![image](https://github.com/Illias-b/B2B-Broadband-Sales/assets/33836566/5570bb7a-b7c8-4a32-904f-e919f98e8ae1)


### Detailed Sales and MRC Breakdown Dashboard
- **Purpose:** To offer in-depth analysis of sales performance and Monthly Recurring Charges.
- **Features:** Detailed breakdowns by product, sales figures, MRC analysis, and performance over time.

- ![image](https://github.com/Illias-b/B2B-Broadband-Sales/assets/33836566/a02edc7c-b177-439e-be15-fcb6e856bd00)


## Usage

Teams across the B2B segment are encouraged to utilize these dashboards for:
- Monthly performance tracking.
- Strategic planning and forecasting.
- Identifying trends and opportunities for growth.
- Cross-functional team meetings and reporting.

## Additional Considerations

- **Data Privacy and Compliance:** Ensure all data used complies with GDPR and other relevant data protection regulations.
- **Regular Updates:** The dashboard will be updated regularly to reflect the latest data and insights.
- **Data Integrity:** Continuous monitoring and validation of SQL queries and data sources to maintain accuracy and reliability.

## Conclusion

The B2B Monthly Performance Dashboard represents a significant step forward in our approach to data analytics and reporting. By providing a centralized, dynamic platform for performance analysis, we aim to empower teams with the insights needed to drive strategic decisions and achieve business objectives.
