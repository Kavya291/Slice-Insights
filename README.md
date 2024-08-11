# Slice Insights : Pizza Sales Report with SQL and Power BI

This project leverages SQL and Power BI to analyze annual pizza sales data by implementing SQL queries for extracting key performance indicators, identifying daily and monthly trends, and calculating sales percentages by category and size, while utilizing Power BI for data cleaning, visualization, and dashboard creation, including in-depth analysis of top and bottom sellers.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Data Analysis with SQL](#data-analysis-with-sql)
- [Creating Dashboards with Power BI](#creating-dashboards-with-power-bi)
- [Dashboard Overview](#dashboard-overview)
- [How to Use the Dashboard](#how-to-use-the-dashboard)
- [Contributors](#contributors)
- [Feedback and Contributions](#feedback-and-contributions)
- [License](#license)

## Features

- **Daily and Monthly Trends**: Visualize the total number of pizza orders and sales figures on a daily and monthly basis. Gain insights into when the highest sales occurred.

- **Pizza Category Analysis**: Analyze sales by pizza category to understand customer preferences and identify the most popular categories.

- **Pizza Size Analysis**: Examine the distribution of pizza sales by size, enabling you to tailor your menu based on customer choices.

- **Top-Selling Pizzas**: Discover the top-selling pizzas based on revenue, quantity, and total orders. Use this information to optimize your menu and increase profits.

## Getting Started

1. **Data Analysis with SQL**:
   - The initial data analysis was conducted using SQL. The SQL scripts and queries used for data extraction, transformation, and loading can be found in the <a href="slice_insights_analysis.sql">sql_sales_analysis.sql</a> of this repository.

2. **Creating Dashboards with Power BI**:
   - The Power BI project file <a href="slice_insights.pbix">pizza_sales_report.pbix</a> contains the interactive dashboards. You can open and customize it with Power BI Desktop.

3. **Access the Dashboard**:
   - Open the `pizza_sales_report.pbix` file with Power BI Desktop to explore the interactive dashboards.

## Data Analysis with SQL

The SQL analysis involved the extraction and transformation of the data, which includes details of pizza sales, pizza category, size, and featuring various KPI's. The SQL analytics include:
   - Identifying the daily and monthly trends of the pizzas sold and the revenue generated.
   - Identifying the top-selling pizzas based on revenue, quantity, and total orders.
   - Identify the least-selling pizzas based on revenue, quantity, and total orders.
   - Identifying the % of sales by pizza category and orders placed by the customers.

## Creating Dashboards with Power BI

Power BI is used to create interactive dashboards for visualizing the pizza sales data. The Power BI project file (`slice_insights.pbix`) contains the following interactive dashboards:

### Dashboard Overview

The **Pizza Sales Report** dashboards provide a user-friendly interface and offer the following views:

- **Trends**: Daily and monthly sales trends.
- **Pizza Category Analysis**: Sales breakdown by pizza category.
- **Pizza Size Analysis**: Distribution of sales by pizza size.
- **Top-Selling Pizzas**: Identification of top-selling pizzas based on various metrics.
- **Least-Selling Pizzas**: Identification of least-selling pizzas based on various metrics.

### Home Page Report Dashboard
<img src="Dashboards/Home_Page.png">

### Best/Worst Sellers Report Dashboard
<img src="Dashboards/Best_Worst_Sellers.png">

### How to Use the Dashboard

1. **Open Power BI Desktop**:
   - Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) if you haven't already.

2. **Open the Project File**:
   - Launch Power BI Desktop and open the `pizza_sales_report.pbix` file.

3. **Explore the Dashboards**:
   - Navigate between the different views by clicking on the tabs on the left side.

4. **Interact with Visuals**:
   - The visuals are interactive; you can hover, click, and filter the data to gain deeper insights.

## License

This project is licensed under the MIT License.

