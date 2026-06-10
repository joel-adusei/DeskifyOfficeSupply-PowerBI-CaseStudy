# DESKIFY PERFORMANCE ANALYSIS

## Leveraging Power BI's Advanced Analytics for Product Profitability and Customer Segmentation Analysis at Deskify

***Disclaimer⚠️:** All datasets, slides and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual mention. All info are dummy and design to demonstrate my capabilities of using PowerBI to perform advance analysis on healthcare dataset*

## PROBLEM STATEMENT
The organization currently depends on Excel for compiling, analyzing, and reporting its monthly sales and transaction data. It has become increasingly cumbersome and time-consuming due
to the complexity of the data and the high volume of transactions processed each month. Reporting process involves manual data entry, consolidation from multiple sources which introduces 
errors and inconsistencies.


## AIM OF THE PROJECT
- To build a data model using Deskify OfficeSupply Co.’s sales and transaction reportingby using Power BI. This solution will
centralize data sources and streamline datacleaning. By reducing manual processes, the project will improve reporting accuracy and efficiency.

- Build an interactive dashboards that will enable faster, data-driven decisions.


## Methodology

- Business Understanding: I defined project objectives to analyze trends in NHS hospital component issues and wastage.

- Data Understanding: I explored the dataset to identify key features and relationships for analysis.

- ETL Process: I extracted, transformed, and loaded the data into Power BI for compatibility and analysis.

- Data Modeling: I created relationships between fact and dimension tables for structured analysis.

- Analysis & Visualization: I developed interactive dashboards and advanced visualizations to uncover trends in revenue, profit margins, shipping mode fulfillment, and regional customer segment distributions etc.


## MODELLING

The data modeling for this project follows a clean Star Schema configuration, where the central Fact Table (Orders) links out to primary Dimension Tables (Customers, Location, Products, and a programmatic Calendar Table) through unique system identifiers.

![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/deskify%20data%20model.JPG?raw=true)


To support robust time-series calculations across the complete 2009–2012 matrix, a custom, standalone time dimension was generated directly inside the Power BI data model using DAX.


![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/calenderdim.JPG?raw=true)
