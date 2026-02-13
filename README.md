# Task 14 - ETL Mini Pipeline (Python)

## Dataset Used
Online Retail Dataset (2010)

## Objective
Build an ETL pipeline using Python to extract, transform, and load retail data.

## Extract
- Loaded raw CSV dataset.

## Transform
- Removed null CustomerID records.
- Removed cancelled invoices.
- Dropped duplicates.
- Standardized column names.
- Converted data types.
- Created derived column total_amount.

## Load
- Split data into customers, products, and orders tables.
- Exported processed CSV files.
- Loaded data into SQLite database.

## Deliverables
- task14_etl.ipynb
- customers.csv
- products.csv
- orders.csv
- database.sqlite
