# Sales-Performance-Dashboard-PowerBI

**Project Overview**

This project presents an interactive Sales Performance Dashboard developed in Power BI to analyse sales performance across products, regions, and sales representatives.

The dashboard transforms raw sales data into meaningful business insights through data cleaning, data modelling, DAX calculations, KPI development, and interactive visualisations.

The goal of this project is to help stakeholders monitor sales performance, identify top-performing products and representatives, track revenue trends, and make data-driven business decisions.


**Business Objectives**

This dashboard answers key business questions:

- How much total revenue has been generated?

- How many orders have been successfully closed?

- What is the average value per order?

- How much revenue is currently pending?

- How has sales performance changed month over month?

- Which products contribute the most to total revenue?

- Which sales representatives are the top performers?

- How does revenue performance vary across different regions?



**Tools & Technologies**

- Power BI Desktop

- Power Query

- DAX (Data Analysis Expressions)

- Data Modelling

- Excel Dataset



**Data Preparation**

Data was cleaned and transformed using Power Query:

- Removed duplicate and unnecessary records

- Corrected inconsistent data values

- Standardised text formatting

- Created date-related fields for analysis

- Prepared a clean dataset for reporting



**Data Model**

Implemented a star-schema style model with a dedicated Date Table to enable accurate time-based analysis.



**Key relationships:**

Date Table → Sales Data

One-to-many relationship

Single-direction filtering



**Dashboard Features**

KPI Summary Cards

The dashboard provides an executive overview of:

- Closed Revenue: **$3.39M**

- Closed Orders:**787**

- Average Order Value: **$5.53K**

- Pending Revenue: **$610.86K**



**Sales Trend Analysis**

Track monthly revenue performance to identify:

- Sales growth trends

- Seasonal patterns

- High and low-performing periods



**Product Performance Analysis**

Analyse product contribution by:

- Total revenue generated

- Product ranking

- Percentage contribution to overall revenue

Top products identified:

**Product	Revenue	Contribution**

PRO-PACK	$1.36M	40%

GADGET-Y	$878K	26%

GADGET-X	$551K	16%



**Month-over-Month (MoM) Analysis**

Created DAX measures to compare monthly performance:

- Previous Month Revenue

- Month-over-Month Growth %

- Conditional formatting highlighting positive and negative trends



**Regional Performance Insights**

Interactive analysis of sales trends across:

- East

- North

- South

- West


Users can filter the dashboard using region and month slicers.


**Sales Representative Performance**

Ranked representatives based on closed revenue to identify top performers and support performance management.


**Key DAX Measures**

The dashboard includes custom DAX calculations such as:

- Total Closed Revenue

- Total Closed Orders

- Average Order Value (AOV)

- Previous Month Revenue

- Month-over-Month % Change

- Product Revenue Contribution %

- Sales Representative Rank


**Dashboard Preview**
**Sales Performance Dashboard**

<img width="1429" height="789" alt="image" src="https://github.com/user-attachments/assets/392c012f-9461-4630-b350-441c9f8cea22" />





**Key Skills Demonstrated**

- Data Cleaning & Transformation

- Power Query ETL

- Data Modelling

- DAX Calculations

- KPI Development

- Time Intelligence Analysis

- Conditional Formatting

- Interactive Dashboard Design

- Business Performance Analysis

- Data Storytelling



**Business Insights**

- PRO-PACK is the highest revenue-generating product, contributing approximately 40% of total revenue.
- Revenue peaked during October and November, indicating stronger sales performance during this period.
- Month-over-Month analysis highlights periods of both strong growth and revenue decline.
- Sales representative rankings help identify top-performing team members and potential coaching opportunities.


**Author**

**Pravalika Annem**

Aspiring Data Analyst | Power BI & Reporting Specialist
