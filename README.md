
# Bright Motors Car Sales Analysis

## Project Overview

This project was completed as part of the BrightLearn Data Analytics Case Study for Bright Motors. The objective was to analyze historical car sales data and provide actionable business insights to support the newly appointed Head of Sales in making informed decisions regarding sales growth, inventory optimization, dealership expansion, and profitability improvement.

The project follows a complete data analytics workflow, including data preparation, SQL-based transformation, exploratory data analysis, dashboard development, and business reporting.

---

## Business Problem

Bright Motors requires a better understanding of its historical sales performance in order to:

* Identify the vehicle makes and models that generate the highest revenue.
* Understand the relationship between vehicle price, mileage, and year of manufacture.
* Evaluate sales performance across different regions.
* Identify customer purchasing trends and preferences.
* Improve dealership profitability and operational efficiency.

The analysis provides data-driven recommendations that can assist management in improving sales strategies and inventory planning.

---

## Project Objectives

The primary objectives of this project were to:

1. Analyze historical vehicle sales data.
2. Calculate revenue and profitability metrics.
3. Identify top-performing car makes and models.
4. Examine sales trends over time.
5. Evaluate regional sales performance.
6. Explore customer preferences based on vehicle characteristics.
7. Develop an interactive dashboard for business users.
8. Present findings and recommendations to management.

---

## Dataset Description

The dataset contains transactional vehicle sales information, including:

* Vehicle Make
* Vehicle Model
* Selling Price
* Cost Price
* Vehicle Year
* Mileage
* Fuel Type
* Body Type
* State / Region
* Sale Date
* Units Sold

The dataset was provided in CSV format and processed for analysis.

---

## Project Architecture

The project follows a standard data analytics pipeline:

### 1. Data Source

* Bright Motors Car Sales Dataset (CSV)

### 2. Data Processing (ETL)

* Data cleaning
* Removal of duplicates
* Handling missing values
* Data type conversion
* Revenue calculations
* Profit margin calculations
* Time-based transformations

### 3. Data Storage

* SQL Database / Snowflake Environment

### 4. Data Analysis

* SQL Queries
* Pivot Tables
* Aggregation and Trend Analysis

### 5. Data Visualization

* Microsoft Excel
* Interactive Dashboard
* Charts and KPIs

### 6. Reporting

* PowerPoint Presentation
* Business Recommendations

---

## Data Cleaning and Transformation

The following preprocessing steps were performed:

### Data Cleaning

* Removed duplicate records.
* Checked for missing values.
* Standardized column naming conventions.
* Converted text-based numerical values to appropriate numeric formats.
* Validated data consistency across fields.

### Calculated Fields

#### Total Revenue

Formula:

Total Revenue = Selling Price × Units Sold

#### Profit Margin

Formula:

Profit Margin = ((Selling Price − Cost Price) ÷ Selling Price) × 100

#### Performance Tier

Vehicles were categorized into:

* High Margin
* Medium Margin
* Low Margin

### Time Intelligence

Sales records were grouped by:

* Month
* Quarter
* Year

to support trend analysis.

---

## Analytical Approach

The project focused on answering the following business questions:

### Revenue Analysis

* Which car makes generate the highest revenue?
* Which car models contribute most to sales?

### Regional Analysis

* Which states or regions achieve the highest sales volume?
* Which locations generate the most revenue?

### Customer Preference Analysis

* Which body types are most popular?
* Which fuel types dominate customer purchases?

### Trend Analysis

* How do sales fluctuate throughout the year?
* What seasonal patterns exist?

### Profitability Analysis

* Which products deliver the highest profit margins?
* Which segments should receive greater inventory allocation?

---

## Dashboard Components

The dashboard was designed to provide an interactive view of key performance indicators.

### KPIs

* Total Revenue
* Total Sales Transactions
* Average Selling Price
* Total Units Sold

### Visualizations

* Revenue by Car Make
* Revenue by Vehicle Model
* Revenue Trend by Month
* Sales by Region
* Quantity Sold by Body Type
* Profit Margin Distribution
* Sales Breakdown by Fuel Type

### Filters (Slicers)

* Year
* State / Region
* Fuel Type
* Vehicle Make

---

## Key Findings

### Revenue Performance

* Ford generated the highest proportion of total sales among all manufacturers.
* Chevrolet, Nissan, and Toyota also contributed significantly to overall revenue.

### Vehicle Demand

* Sedans were the most frequently purchased vehicle type.
* SUVs represented the second-largest sales category.

### Regional Performance

* Sales activity was concentrated in a limited number of high-performing regions.
* Certain states contributed substantially more revenue than others.

### Seasonal Trends

* Monthly sales patterns revealed fluctuations throughout the year.
* Several months consistently outperformed others in both revenue and transaction volume.

### Customer Preferences

* Customers showed strong demand for practical vehicle categories such as sedans and SUVs.
* Popular models generated significantly higher revenue than niche vehicle segments.

---

## Business Recommendations

Based on the analysis, the following recommendations were proposed:

### 1. Focus on High-Performing Brands

Increase inventory allocation for manufacturers that consistently generate strong sales and revenue.

### 2. Expand Successful Product Lines

Maintain adequate stock levels for high-demand body types such as Sedans and SUVs.

### 3. Regional Growth Strategy

Investigate opportunities to expand dealership operations in top-performing regions.

### 4. Improve Inventory Optimization

Use historical sales trends to align stock levels with expected demand.

### 5. Strengthen Profit Margin Management

Prioritize vehicles that generate higher profit margins while reducing exposure to low-margin inventory.

### 6. Data-Driven Decision Making

Implement ongoing dashboard monitoring to support future sales and operational decisions.

---

## Deliverables

The following project deliverables were produced:

### 1. Architecture Diagram

* Data flow and analytics pipeline design.

### 2. Processed Dataset

* Cleaned and transformed sales dataset.

### 3. SQL Scripts

* Data cleaning queries.
* Transformation logic.
* Revenue and profitability calculations.

### 4. Dashboard

* Interactive Excel dashboard with KPIs and visualizations.

### 5. Presentation

* Executive summary and business recommendations for management.

---

## Technologies Used

### Data Processing

* SQL
* Snowflake (or equivalent SQL platform)

### Analysis

* Microsoft Excel
* Pivot Tables

### Visualization

* Excel Dashboard

### Reporting

* Microsoft PowerPoint

---

## Conclusion

This project demonstrates how historical sales data can be transformed into actionable business intelligence. Through data cleaning, SQL transformations, dashboard creation, and business analysis, Bright Motors gains valuable insights into revenue drivers, customer purchasing behavior, regional performance, and profitability. These findings provide a strong foundation for strategic decision-making and future business growth.
