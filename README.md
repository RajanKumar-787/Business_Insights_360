# Business Insights 360

## Link

[Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiOTIwZWFmMjMtYTA4NC00ZWE4LWFiZWQtMjc0ZDIxNzRiZjUxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Project Overview

AtliQ Hardware, a rapidly growing global consumer electronics company, has faced challenges with Excel-based data analytics, resulting in significant losses in Latin America. To overcome these issues and gain a competitive advantage, AtliQ is implementing Power BI for the first time. This strategic 
initiative aims to provide actionable insights across finance, sales, marketing, executive operations, and supply chain management, empowering stakeholders with the data needed to make informed decisions and drive continued growth.

## Tech Stack

**Data Sources:** MySQL, Excel

**ETL Tool:** Power Query

**Data Model:** Snowflake Schema

**DAX Functions:** CALCULATE, SWITCH, SAMEPERIODLASTYEAR, SELECTEDVALUE, HASONEVALUE etc.

**Visualizations:** Waterfall chart, Scatter chart, Area chart, Table, Matrix, KPI, Donut Chart, Pie chart, Column Chart, Bar chart, etc.

**Optimization Tool:** DAX Studio

**Power BI Tools:** Power BI Desktop, Power BI Service

**Project Documentation:** Project Charter File (**Mural**)


## Solution

**Multi-View Power BI Dashboard:** Developed a multi-view Power BI dashboard for five key departments (Finance, Sales, Marketing, Supply Chain, and Executive) at AtliQ Hardware.This dashboard provided in-depth business insights, driving data-driven decision-making and streamlining business processes.

## Power BI Skill Acquired

**Project Planning:** Defined key questions and objectives to ensure project alignment and success.

**Data Loading:** Imported data from MySQL databases and Excel files to consolidate information.

**ETL Processes:** Performed Extract-Transform-Load (ETL) operations in Power Query, including creating date tables using M language.

**Data Modeling:** Developed and optimized data models by defining relationships between tables to ensure integrated and accurate data analysis.

**Visualization Creation:** Designed and implemented various visualizations to represent data effectively.

**Calculated Columns:** Added new data insights by creating calculated columns within tables.

**DAX Measures:** Developed sophisticated calculations using DAX measures for advanced data analysis.

**Bookmarks:** Utilized bookmarks to enable seamless transitions and interactions between different visuals.

**Page Navigation:** Implemented page navigation buttons for easy movement between report pages.

**Dynamic Titles:** Created dynamic titles that automatically update based on applied filters.

**KPI Indicators:** Incorporated Key Performance Indicators (KPIs) to track and display key metrics.

**Conditional Formatting:** Applied conditional formatting to visuals, using icons and colors to highlight significant data points.

**Power BI Service:** Managed report publishing, set up data refresh schedules, and utilized Power BI Service for report sharing.

**Collaboration:** Facilitated team collaboration through workspace management and access control in Power BI.

## Business Related Terms

- Gross Sales
- Pre-Invoice Deductions
- Net Invoice Sales
- Post-Invoice Deductions
- Net Sales
- COGS (Cost of Goods Sold)
- Gross Margin
- Gross Margin %
- Gross Margin per Unit (GM/Unit)
- Operating Expenses
- Net Profit
- Net Profit %
- YTD (Year to Date)
- YTG (Year to Go)
- Brick-and-Mortar
- E-Commerce
- Direct Sales
- Retailers
- Distributors
- Consumers

## Data Model Overview

The screenshot below showcases the Snowflake Schema data model used in this project for streamlined data integration and analysis.

![0](https://github.com/user-attachments/assets/06de1d3a-5580-4661-b2e7-d6db80411f39)

## Power BI Dashboards

### 1. Finance View

![1](https://github.com/user-attachments/assets/033f1edf-c104-4b3f-a511-79386a51c22a)

**Profit & Loss Statement Visual**
- This visual represents the company's revenues and expenses for the selected year, providing a clear view of overall financial performance.
- Additionally, this visual compares the profit and loss statement for the selected year with benchmark figures, such as previous year’s performance or target goals, enabling a comprehensive evaluation of financial progress.

**Net Sales Performance Over Time Visual**
- This visual compares the net sales for the selected year with benchmark figures, such as previous year's performance or target goals, allowing for a detailed analysis of sales trends over time.
- Furthermore, it can be customized to replace net sales with other line items, such as gross margin percentage, net profit percentage, and more, providing flexibility for in-depth analysis.

**Top & Bottom customers By revenue Visual**
- This visual represents the top and bottom customers based on net sales, offering valuable insights into customer performance and helping to identify key areas for strategic focus and improvement.

**Top & Bottom Products By revenue Visual**
- This visual represents the top and bottom products based on net sales, offering insights into product performance.

### 2. Sales View

![2](https://github.com/user-attachments/assets/85685d67-5ca5-49d9-8204-0f72ddc7d2a2)

**Customer Performance Visual**
- This visual analyzes customer performance by examining net sales, gross margin, and gross margin percentage.

**Product Performance Visual**
- This visual analyzes product performance by examining net sales, gross margin, and gross margin percentage.

**Performance Matrix Visual**
- This matrix visualizes markets or customers by plotting net sales on one axis and gross margin percentage on the otheroffering a clear comparison of revenue generation and profitability.

**Unit Economics Visual**
- This visual shows that to generate this amount of net sales, nearly the same amount was spent on discounts.It then divides net sales into Cost of Goods Sold (COGS) and gross margin to provide further insights.

### 3. Marketing View

![3](https://github.com/user-attachments/assets/5352119a-6935-46fc-9d71-f04c64cc9c94)

**product performance Visual**
- This visual analyzes product performance by evaluating net sales, gross margin, gross margin percentage, net profit, and net profit percentage.

**region/market/customers performance Visual**
- This visual analyzes the performance of regions, markets, or customers by evaluating net sales, gross margin, gross margin percentage, net profit, and net profit percentage.

**performance matrix Visual**
- This matrix analyzes products by plotting net sales on one axis and net profit percentage on the other. 
- It also allows for switching between gross margin percentage and net profit percentage to gain different perspectives on product performance.

**unit economics Visual**
- This visual compares COGS, gross margin, operational expenses, and net profit, providing a detailed breakdown of how each component affects the company’s bottom line.

### 4. Supply Chain View

![4](https://github.com/user-attachments/assets/98617754-2938-4dd9-ac77-8be6d14f7a08)

**Forecast Accuracy KPI Visual**
- This KPI visual compares forecast accuracy for the selected year with the previous year, showing how accurate our forecasts are.

**Net Error KPI Visual**
- This KPI visual compares the net error for the selected year against the previous year.

**ABS Error KPI Visual**
- This KPI visual compares the absolute error for the selected year with the previous year.

**Key Metrics By Customer Visual**
- This visual analyzes customer performance using key metrics such as forecast accuracy percentage, forecast accuracy percentage from the previous year, net error, net error percentage, and risk.

**Accuracy/Net Error Trend Visual**
- This visual analyzes net error, forecast accuracy percentage, and forecast accuracy percentage from the previous year over time, providing insights into trends and changes in forecasting performance.

**Key Metrics By Product Visual**
- This visual evaluates product performance by examining key metrics such as forecast accuracy percentage, forecast accuracy from the previous year, net error, net error percentage, and risk.

### 5. Executive View

![5](https://github.com/user-attachments/assets/e6171b1e-1ddd-47d8-9ef9-b184aaf42db7)

**Key Insights By Subzone Visual**
- This visual evaluates subzone performance by analyzing key metrics including net sales, revenue contributions, gross margin percentage, net profit percentage, Atliq market share percentage, net error percentage, and risk.

**PC Market Share Trend - Atliq & Competitors Visual**
- This visual represents the PC market share trend, comparing AtliQ's position with other manufacturers such as BP, Dale, Innovo, and Pacer.

**Revenue BY Division Visual**
- This visual shows the revenue distribution by division, providing insights into each division's contribution to overall earnings.

**Revenue By Channel Visual**
- This visual shows the revenue distribution by channel, providing a clear view of how each channel contributes to the company's total earnings.

**Yearly Trend By Revenue, GM%, Net Profit%, Pc Market Share % Visual**
- This visual represents annual trends in net sales, gross margin percentage, net profit percentage, and AtliQ's market share percentage, providing a detailed analysis of these key performance metrics over time.

**Top 5 Product By Revenue Visual**
- This visual displays the top 5 products by revenue, along with their revenue contribution percentages and gross margin percentages.

**Top 5 Customers By Revenue Visual**
- This visual shows the top 5 customers by revenue, along with their revenue contribution percentages and gross margin percentages.

## Conclusion

Thank you for exploring the Business Insights 360 project. This Power BI implementation for AtliQ Hardware delivers a robust set of dashboards designed to enhance data-driven decision-making across critical departments including Finance, Sales, Marketing, Supply Chain, and Executive operations.

For further details or to explore the interactive reports, please refer to the [Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiOTIwZWFmMjMtYTA4NC00ZWE4LWFiZWQtMjc0ZDIxNzRiZjUxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9) Link.

If you have any questions, feedback feel, or wish to connect, free to reach out:\
Contact: rajaninranchi787@gmail.com\
GitHub Profile: https://github.com/RajanKumar-787 \
LinkedIn: https://www.linkedin.com/in/rajankumar787/

Your engagement is greatly appreciated. If you find this project valuable, please consider starring it on GitHub.
