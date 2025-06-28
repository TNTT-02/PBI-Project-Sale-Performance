#  PBI-Project-Sale-Performance

## Project Overview

**Project Title**:  PBI-Project-Sale-Performance

**Database**: [Finance Data](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download)

**Data capacity**: Includes 1 files, total 701 rows of data

**Project Objective**
Designed an interactive Power BI dashboard to monitor sales performance by country, product, time period, and customer segment—supporting data-driven business decisions.

## Project Structure

### 1. Data Preparation (ETL)

Basic data cleaning: Use Power Query to removed duplicates, standardized column names, ensured correct data types

### 2. DAX Calculations

**Calculated Columns:**
- `Short Month`: Extracted 3-letter month abbreviation
- `WeekdayName`: Extracted full weekday name

**Calculated Table:**
`Weekday Table`: Custom table created in DAX for weekday sorting logic

**Measures:**
- `Revenue`, `Profit`, `Total Cost`
- `Profit Margin`, `Average Revenue`, `Quantity Sold`

### 3. Dashboard Design

**Visualizations:**
- Bar charts: Revenue, Profit, Cost by Month and Product
- Map: Revenue distribution by Country
- Cards: Key KPIs

**Interactivity:**
- Slicers: Product, Year, Customer Segment, Discount Band
- Drill-down features for deeper product and regional analysis

### 4. Insights & Findings
- The **USA** generated the highest revenue, mainly from the **Small Business** segment
- **Mexico** had the lowest sales overall
- **Paseo** was the top-selling product, generating **~$8M**, mostly from Mexico
- **December 2014** was the peak month for Paseo, with **$4.9M** in sales
