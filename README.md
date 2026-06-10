# Swiggy Instamart Operational & Customer Insights Dashboard

##  Project Overview

This project presents an interactive Power BI dashboard designed to analyze the operational performance and customer purchasing behavior of a quick-commerce business. The dashboard consolidates sales, delivery, inventory, and customer data to provide actionable insights for business decision-making.

The solution enables stakeholders to monitor revenue trends, evaluate delivery efficiency, understand customer preferences, identify inventory risks, and track overall business performance through a centralized reporting interface.


##  Business Objective

The objective of this dashboard is to provide a comprehensive view of business operations by analyzing:

* Sales Performance
* Customer Purchasing Behavior
* Order Fulfillment Efficiency
* Delivery Operations
* Inventory Availability
* City-Wise Revenue Performance

The dashboard helps decision-makers identify business opportunities, operational bottlenecks, and customer demand patterns.


##  Tools & Technologies

* Power BI
* DAX
* SQL
* Microsoft Excel


##  Dataset Overview

The dashboard utilizes four interconnected datasets:

### Orders

* Order ID
* Customer ID
* Product ID
* Order Amount
* Quantity
* Order Status
* Order Date
* City
* Customer Rating

### Products

* Product ID
* Category
* Brand
* MRP
* Selling Price

### Delivery

* Rider ID
* Delivery Distance
* Delivery Time
* Delay Status

### Inventory

* Stock Quantity
* Reorder Level
* Out-of-Stock Status


##  Data Modeling

Relationships were established between:

* Orders ↔ Products
* Orders ↔ Delivery
* Inventory ↔ Products

A dedicated Measures Table was created to organize DAX calculations and improve model maintainability.


##  KPIs Developed

### Sales KPIs

* Total Revenue
* Total Orders
* Average Sales
* Items Sold
* Average Basket Size

### Delivery KPIs

* Orders Delivered
* Orders Delayed
* Orders Cancelled
* On-Time Delivery Percentage

### Inventory KPIs

* Out-of-Stock Products

### Customer KPIs

* Reorder Analysis
* Product Category Preferences


##  Dashboard Features

### Sales Analytics

* Revenue Monitoring
* City-Wise Revenue Analysis
* Average Sales Tracking

### Customer Analytics

* Quarterly Order Trend Analysis
* Product Category Preference Analysis
* Customer Reorder Insights

### Delivery Analytics

* On-Time Delivery Monitoring
* Delayed Order Tracking
* Cancelled Order Analysis

### Inventory Analytics

* Stock Availability Monitoring
* Inventory Risk Identification

### Interactive Reporting

* KPI Cards
* Donut Charts
* Gauge Charts
* Treemaps
* Line Charts
* Bar Charts
* Interactive Filters and Slicers


##  Key Business Insights

* Identified top-performing cities contributing the highest revenue.
* Evaluated delivery efficiency using On-Time Delivery Percentage metrics.
* Analyzed customer purchasing patterns across multiple product categories.
* Monitored operational performance through delayed and cancelled order tracking.
* Identified inventory shortages that may impact order fulfillment and customer satisfaction.
* Compared brand-wise sales performance to understand product demand trends.


##  Skills Demonstrated

### Power BI

* Dashboard Design
* Interactive Reporting
* Data Modeling
* KPI Development

### DAX

* SUM
* COUNT
* DISTINCTCOUNT
* CALCULATE
* DIVIDE

### Analytics

* Business Analytics
* Customer Analytics
* Sales Analytics
* Inventory Analytics
* Operational Analytics

### Data Visualization

* KPI Cards
* Gauge Charts
* Donut Charts
* Treemaps
* Trend Analysis
* Comparative Analysis


##  Dashboard Preview

<img width="900" alt="Swiggy Instamart Dashboard" src=""C:\Users\ELCOT\Pictures\Screenshots\Screenshot 2026-06-10 231637.png"">


##  Project Outcome

The dashboard provides a unified view of sales performance, customer behavior, delivery efficiency, and inventory management. By transforming raw operational data into meaningful insights, the solution supports data-driven decision-making and demonstrates practical applications of Business Intelligence and Data Analytics in a quick-commerce environment.


