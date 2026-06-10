# DESKIFY PERFORMANCE ANALYSIS

## Leveraging Power BI's Advanced Analytics for Product Profitability and Customer Segmentation Analysis at Deskify

***Disclaimer⚠️:** All datasets, slides and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual mention. All info are dummy and design to demonstrate my capabilities of using PowerBI to perform advance analysis on healthcare dataset*

## PROBLEM STATEMENT
The organization currently depends on Excel for compiling, analyzing, and reporting its monthly sales and transaction data. It has become increasingly cumbersome and time-consuming due
to the complexity of the data and the high volume of transactions processed each month. Reporting process involves manual data entry, consolidation from multiple sources which introduces 
errors and inconsistencies.


## AIM OF THE PROJECT
- To build a data model using Deskify OfficeSupply Co.’s sales and transaction reporting by using Power BI. This solution will
centralize data sources and streamline datacleaning. By reducing manual processes, the project will improve reporting accuracy and efficiency.

- Build an interactive dashboards that will enable faster, data-driven decisions.


## Methodology 

Before building visuals, I had to clean and model the data to ensure the insights were reliable.

### Step 1: Data Cleaning & Preparation


### Step 2: Modelling & DAX

The data modeling for this project follows a clean Star Schema configuration, where the central Fact Table (Orders) links out to primary Dimension Tables (Customers, Location, Products, and a programmatic Calendar Table) through unique system identifiers.

![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/deskify%20data%20model.JPG?raw=true)


I wrote DAX measures for:

- Total Revenue
  
![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/TR-deskify.JPG?raw=true)


- Total profit
  
![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/TP-deskify.JPG?raw=true)


- Total Orders
  
![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/TO-deskify.JPG?raw=true)


- Total Customers
  
![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/TC-deskify.JPG?raw=true)


- Profit Margin
  
![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/PM-deskify.JPG?raw=true)


To support robust time-series calculations across the complete 2009–2012 matrix, a custom, standalone time dimension was generated directly inside the Power BI data model using DAX.


![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/images/calenderdim.JPG?raw=true)



### Step3: Dashboard Pages

I designed two interactive pages:

1️⃣ Product Insights

Key KPIs, Total Profit by Product Category, Total Orders by Ship Mode, Top 10 Best Performing States by Profit, Total Profit by Product Name, and Total Profit by Month.

![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/Product%20Analysis.JPG?raw=true)



2️⃣ Customer Insights

Key KPIs, Profitability by Customer Segment, Profitability by Product Sub-Category, Profitability by Customer, Profitability by Region 
and Customer Segment.

![image](https://github.com/joel-adusei/DeskifyOfficeSupply-PowerBI-CaseStudy/blob/main/Customer%20Analysis.JPG?raw=true)
