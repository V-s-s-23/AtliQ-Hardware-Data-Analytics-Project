# AtliQ-Hardware-Data-Analytics-Project


## Overview
This project involves analyzing a dataset of over 1 million rows, using **SQL** for data exploration and Power BI for modeling, data cleansing, and visualization. The primary goal is to provide insights into different business areas through a comprehensive data model and KPIs built in Power BI.

## Project Structure
- **SQL Exploration & Data Cleansing**: Initial exploration and cleaning were done using SQL, connecting to the data source directly and optimizing the dataset for Power BI modeling.
- **Power BI Data Modeling**: Power BI was used to create a robust data model, including calculated columns and measures using DAX and further cleansing using Power Query.
- **Key Views**:
  - **Market View**
  - **Finance View**
  - **Supply Chain View**
  - **Sales View**

## Key Performance Indicators (KPIs)

### Finance View
The following KPIs were created in the **Finance View** to track the financial health of the business:
- **Gross Margin %**: Measures the percentage of revenue remaining after deducting the cost of goods sold.
- **Net Profit %**: Represents the percentage of net income relative to total revenue.
- **Net Sales**: Tracks total revenue from sales after returns, allowances, and discounts.

### Supply Chain View
In the **Supply Chain View**, the KPIs help monitor the efficiency and accuracy of supply chain operations:
- **Forecast Accuracy**: Compares forecasted demand against actual demand to measure prediction accuracy.
- **Net Error**: The difference between actual and forecasted values, showing the deviation.
- **Net Profit**: Also tracked here to understand profitability from a supply chain perspective.

### Data Model
The data model was constructed in Power BI by establishing relationships between key tables.
Power BI’s data model allows for dynamic reporting and the ability to slice and dice the data based on various dimensions like time, region, and product categories.

### Data Cleansing
Data cleansing was performed using:
- **SQL**: To filter and remove anomalies.
- **Power Query**: Further cleansing was performed in Power BI to handle missing values, duplicate records, and transform columns as needed.
- **DAX**: Measures were created using DAX functions to add custom calculations and KPIs to the data model.

## Conclusion
This project showcases the power of combining SQL and Power BI for large-scale data exploration, modeling, and visualization. By organizing data into distinct views and KPIs, we provide actionable insights across multiple business functions.
