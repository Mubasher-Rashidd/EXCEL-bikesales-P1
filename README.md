# EXCEL-sales-P1 - Bike Sales Dashboard

![Dashboard Screenshot](https://github.com/Mubasher-Rashidd/EXCEL-bikesales-P1/blob/main/Dashboard.png?raw=true)

This repository contains the **EXCEL-bikesales-P1** project, an interactive **Bike Sales Dashboard** created using Microsoft Excel. The project follows a structured process of data analysis and includes various stages such as data cleaning, processing, and visualization. It ultimately answers key business questions related to bike sales and customer demographics.

## Project Overview

This Excel-based dashboard analyzes bike sales data to provide insights into customer demographics, sales trends, and purchasing behavior. The dashboard includes:
- **Sales Data Analysis**: Aggregation and breakdown of sales by gender, purchase type, and customer commute.
- **Interactive Dashboard**: Visual representation of data with pivot tables, pivot charts, and slicers for dynamic filtering.
- **Business Questions Answered**: Insights into customer purchase patterns (couples, singles), average income per purchase (male/female), and more.

## Stages of Data Analysis

1. **Data Cleaning**:
   - **Identifying and Removing Duplicates**: Ensured the dataset contains unique records by removing duplicate entries.
   - **Fixing Data Format Issues**: Standardized formats for dates, numeric values, and categories (e.g., ensuring all date fields are in the correct date format).
   - **Handling Missing Data**: Applied find-and-replace techniques to handle missing values or inconsistencies in the dataset.

2. **Data Processing**:
   - **Find and Replace**: Replaced incorrect or inconsistent entries (e.g., replacing "M" with "Male" or "F" with "Female").
   - **Removing Unnecessary Data**: Deleted columns or rows that did not contribute to the analysis (e.g., empty rows, irrelevant information).
   - **Changing Data Format**: Adjusted data types for fields like sales figures and dates to ensure they can be correctly analyzed.

3. **Formulas and Functions**:
   - Applied basic and advanced Excel functions to calculate totals, averages, and other metrics.
   - Utilized **nested IF statements** for advanced conditional logic.

4. **Pivot Tables**:
   - Created **PivotTables** to summarize the sales data by different dimensions such as customer type, gender, and commute.
   - PivotTables enabled quick aggregation and grouping of sales data for in-depth analysis.

5. **Pivot Charts**:
   - Generated **PivotCharts** to visualize sales data in formats like bar charts, pie charts, and line charts.
   - Charts were updated dynamically based on slicer selections, allowing users to interact with the data and explore trends.

6. **Data Visualization**:
   - Created a set of **visualizations** (charts and graphs) to make insights easily understandable at a glance.
   - Visualizations include:
     - Total Sales by Gender and Purchase Type
     - Sales Trends over Time
     - Customer Commute

7. **Slicers**:
   - Added **Slicers** to allow users to filter data dynamically by **Customer Type** (Couples/Singles), **Gender**, **Commute Type**, and **Purchase Date**.
   - Slicers provided an interactive way to drill down into specific data points and gain insights from various perspectives.

8. **Dashboard**:
   - Integrated all the components (PivotTables, PivotCharts, Slicers) into a single, interactive **Dashboard** that allows users to explore sales data visually and answer specific business questions.

## Business Requirements Answered

- **How many couples purchased bikes?**
  - The dashboard includes a calculation that filters purchases based on customer type (Couples) to show the total number of bikes purchased by couples.

- **How many singles purchased bikes?**
  - Similar to the "couples" filter, the dashboard also provides insights into the number of bikes purchased by singles.

- **Average income per purchase (Male/Female)?**
  - The data processing stage includes income data, which is then analyzed to compute the average income per purchase for both male and female customers.

- **Customer commute type ?**
  - The dashboard includes a breakdown of customer commute types (e.g., commuter cyclists vs. recreational users), helping to identify the type of customers purchasing bikes.

- **Other Key Insights**:
  - Average sales per customer by gender, income bracket, and product type.
  - Sales performance over different time periods (monthly, quarterly, etc.).

## How to Use

1. Download and open the **EXCEL-bikesales-P1.xlsx** file in Microsoft Excel.
2. Use the **slicers** to filter the data based on the following dimensions:
   - **Gender** (Male/Female)
   - **Customer Type** (Couples/Singles)
3. Explore the **PivotTables**, **PivotCharts**, and **visualizations** that automatically update based on slicer selections.
4. Review the dashboard for answers to key business questions and insights on sales performance and customer demographics.

## Installation

No installation required. Simply download the **EXCEL-bikesales-P1.xlsx** file and open it in Microsoft Excel.

## Requirements

- Microsoft Excel 2016 or later (to fully utilize PivotTables, PivotCharts, and Slicer functionality).
- Ensure that macros and external content (if used) are enabled.


