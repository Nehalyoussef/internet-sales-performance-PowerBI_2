# Sales Performance Dashboard (Power BI) Part 2
## Project Overview

This project is an advanced Power BI dashboard developed as part of the **365 Data Science** Power BI course, focusing on analyzing Internet Sales performance using the AdventureWorks dataset.

The dashboard provides a comprehensive, interactive view of sales performance across time, products, customers, currencies, and global sales territories. It emphasizes business-oriented analytics, time intelligence, and professional UX design using advanced Power BI features rather than basic slicers alone.

The goal of this project is to transform raw transactional data into clear, actionable insights that support strategic decision-making at both executive and operational levels.

## Dataset Description

The dataset is based on the AdventureWorks Internet Sales data model, a widely used sample dataset for learning business intelligence, data modeling, and analytics.

It simulates a real-world international retail scenario where an online company sells products across multiple regions, currencies, and customer segments.

### Tables Used

The data follows a fact and dimension model:

### Fact Table

### fact_InternetSales

* Contains transactional sales data such as sales amount, order quantity, customer, product, date, and territory references.

### Dimension Tables

### dim_ProductCategory

* High-level product categories (e.g., Bikes, Accessories).

### dim_ProductSubCategory

* Subcategories linked to product categories.

### dim_Product

* Detailed product information.

### dim_SalesTerritory

* Sales regions and countries.

### dim_Currency

* Currency information for sales transactions.

### dim_Customer

* Customer demographic data including gender and location.

This structure makes the dataset ideal for Power BI modeling, DAX calculations, and business reporting.

## Dashboard Description

The dashboard presents a global overview of Internet Sales performance, combining KPIs, time-based analysis, currency comparisons, and geographic insights.

At a high level, it highlights key metrics such as total sales amount, products sold worldwide, and recent sales performance. The dashboard allows users to dynamically explore trends over time, compare currencies, analyze regional sales performance, and evaluate changes across multiple historical periods.

By integrating time intelligence, currency logic, and geographic analysis, the dashboard delivers a holistic view of business performance across multiple dimensions.

## Dashboard Features

### Executive-level KPI cards for:

* Total Sales Amount

* Total Sales Last Month

* Sales Amount in Selected Currency

### Time intelligence analysis:

* Monthly timeline slicer covering 2011–2014

* Comparison with previous 1, 3, and 6 months

### Currency comparison analysis:

* Sales Amount in CAD vs All Currencies

* Dynamic updates based on selected currency

### Global sales analysis:

* Interactive world map showing total products sold worldwide

* Detailed country-level sales table

### Advanced conditional formatting:

* Sales performance percentages

* Historical comparisons for trend evaluation

## Dashboard Design & Interactivity

This dashboard demonstrates professional-level UX design using advanced Power BI interactivity features beyond standard slicers:

### Bookmark-Based Buttons

* Clear Filters

* Users ON / OFF

* Currency ON / OFF

* Sales Territory ON / OFF

These buttons allow users to control dashboard behavior dynamically, creating a clean and intuitive analytical experience.

### Interactive Elements

* Monthly timeline slicer for dynamic time analysis

* Currency toggle affecting all related visuals

* Map visual synchronized with detailed country-level tables

* Conditional formatting to highlight performance trends and changes over time

The design prioritizes clarity, consistency, and usability, enabling users to explore insights effortlessly.

## Tools & Technologies

* Power BI Desktop

* DAX (Data Analysis Expressions)

* Power BI Bookmarks & Buttons

* Star Schema Data Modeling

* Time Intelligence Functions
