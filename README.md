# Sales-Data-Analysis

This project analyzes 12 months of sales data from Best Buy (United States, 2019). The code processes raw retail data to identify seasonal trends, geographical hotspots, and consumer purchasing patterns using Python and Pandas.

## Features
* Data Aggregation: Automatically merges 12 separate monthly CSV files from the `sales_data` folder into a single master dataset (`all_data.csv`).
* Data Cleaning: Removes rows with missing values (NaN), filters out erroneous text from date columns, and converts data types to numeric for accurate calculation.
* Feature Engineering: Adds custom columns for 'Month', 'City', and 'Total Sales' to enable deep-dive reporting.
* Time Optimization: Analyzes order timestamps to determine the most effective hours for advertisement placement.
* Market Basket Analysis: Uses grouping and counting logic to find the most frequent product pairings purchased in single orders.

## Installation
1. Clone the repository.
2. Place your 12 monthly CSV files into a folder named `sales_data` in the root directory.
3. Install the required libraries:
```bash
pip install -r requirements.txt
