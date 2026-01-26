### Inventory Management Reporting System using Power BI
## Project Overview

Power BI is a Microsoft business intelligence and data visualization tool that enables users to connect to multiple data sources, transform raw data, and build interactive dashboards and reports. It is widely used by organizations to convert operational data into meaningful insights for decision-making.

This project focuses on building an Inventory Management Reporting System using Power BI. The dashboard provides insights into inventory movement, stock levels, sales performance, profitability, and demand trends, helping stakeholders monitor inventory health and make data-driven decisions.

## Objectives

Monitor inventory levels and stock movement over time

Track sales, receipts, and net inventory movement

Analyze revenue, cost of goods sold (COGS), and gross margin

Identify inventory value and demand patterns

Enable interactive analysis using filters and slicers

Present insights through a professional Power BI dashboard

## Dataset Description

The project uses a sample inventory dataset consisting of multiple related tables, including:

Products: Product details and standard cost

Transactions: Sales and receipt transactions with quantity, price, and cost

Suppliers: Supplier-level information

Calendar: Date dimension for time-based analysis

The data is modeled using proper relationships to support accurate aggregation and filtering.

## Data Preparation and Modeling

Data is loaded into Power BI Desktop from external files

Power Query Editor is used to validate and prepare fields such as dates and text columns

A star-schema–style data model is created using one-to-many relationships

Single-direction cross filtering is applied to ensure correct calculations

This structured model enables efficient DAX calculations and scalable reporting.

## Core DAX Measures

Key business metrics are created using DAX (Data Analysis Expressions), including:

Sales Quantity and Receipt Quantity

Net Inventory Movement

Inventory On Hand (running total)

Revenue and Cost of Goods Sold (COGS)

Gross Margin and Gross Margin Percentage

Inventory Value

Sales Quantity (last 30 days)

Average Daily Demand (last 30 days)

These measures form the foundation for all visual analysis and KPIs in the report.

## Report and Dashboard Design

The report is built using a combination of Power BI visuals to communicate insights effectively:

Cards for key KPIs such as total sales, inventory value, and gross margin

Charts (line, bar, column, pie, and donut) to analyze trends, comparisons, and proportions

Tables to display detailed product-level information

Matrix visuals for multi-dimensional analysis across products and time

Slicers to enable interactive filtering by date, category, supplier, or other dimensions

The dashboard layout is designed for clarity, usability, and executive-level reporting.

## Key Insights

Inventory movement patterns help identify fast-moving and slow-moving products

Gross margin analysis highlights profitable and low-margin items

Inventory value tracking supports better stock planning

Demand trends assist in forecasting and replenishment decisions

## Tools and Technologies Used

Microsoft Power BI Desktop

Power Query Editor

DAX (Data Analysis Expressions)

Data modeling and relationships

Interactive visualizations and dashboards

Conclusion

This project demonstrates how Power BI can be effectively used to build a complete inventory management reporting solution. By combining clean data modeling, powerful DAX measures, and interactive visualizations, the dashboard delivers actionable insights that support operational efficiency and strategic decision-making.
