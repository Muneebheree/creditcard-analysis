# Credit Card Financial Data Dashboard

## Overview

This project analyzes credit card customer and transaction data to visualize key insights about customer spending patterns, transaction volumes, and overall financial trends. The data was preprocessed using SQL, and the visualizations were created in PowerBI, offering a dynamic, interactive dashboard to explore credit card usage behaviors.

## Project Structure

- **SQL Preprocessing:** The raw data was cleaned and transformed using SQL before analysis in PowerBI. Key SQL operations included:
  - Handling missing values.
  - Aggregating transaction data to uncover patterns.
  - Joining customer and transaction data into a unified dataset for analysis.

- **PowerBI Visualizations:** The cleaned data was imported into PowerBI to create a dashboard that highlights:
  - **Transaction Volume:** Total and average transaction amounts segmented by time and customer.
  - **Customer Segmentation:** Distribution of customers by transaction frequency and spending habits.
  - **Monthly Trends:** Identifying seasonal patterns in credit card spending.
  - **Customer Loyalty:** Analysis of customer retention and loyalty.

## Key Insights

1. **Customer Spending Patterns:** A clear segment of high spenders is visible, with transaction peaks in certain months, likely due to promotions or seasonal events.
2. **Transaction Distribution:** Most transactions fall within a specific range, with high-value transactions concentrated among a small group of customers.
3. **Monthly Trends:** Peaks in transactions occur during certain months, highlighting seasonal spending trends.
4. **Customer Retention:** Repeat customers account for a significant portion of overall transactions, indicating strong customer loyalty.

## Data Preprocessing

The project used two primary datasets:
- **Customer Data:** Contains demographic details of credit card holders.
- **Transaction Data:** Logs individual transactions, including transaction amount, date, and category.

### SQL Processing Steps:
1. **Data Cleaning:** Handled missing values, removed duplicates, and standardized columns.
2. **Data Aggregation:** Aggregated transaction data by customer, calculating total spend, frequency, and average transaction amount.
3. **Data Joins:** Merged customer and transaction data into a single dataset for visualization in PowerBI.

## Visualizations in PowerBI

The PowerBI dashboard includes:
- **Customer Overview:** Demographic analysis of credit card holders.
- **Transaction Trends:** Time-series analysis of transaction volume and spending, segmented by customer type and category.
- **Top Spenders:** Insights into the top 10% of high-value customers.
- **Spending by Category:** Breakdown of spending across key categories (e.g., travel, retail, dining).

## How to Use

1. **Run the provided SQL scripts** to preprocess the data.
2. **Import the cleaned data into PowerBI.**
3. **Explore the interactive dashboard** for insights into credit card spending patterns and trends.

## Technologies Used

- **SQL**: For data preprocessing.
- **PowerBI**: For creating the dashboard.
- **Python (optional)**: For extended analysis and potential machine learning integrations.

## Project Files

- `SQL_Scripts/`: Contains SQL scripts for data preprocessing.
- `PowerBI_Dashboard.pbix`: The PowerBI dashboard file.

---

### Author

This project was created as part of a data analysis initiative to explore customer behavior in the financial services sector.
