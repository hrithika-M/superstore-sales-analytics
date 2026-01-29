# superstore-sales-analytics
This project performs exploratory data analysis (EDA) and time-series analysis on a global superstore retail dataset spanning four years. The goal is to uncover sales trends, customer behavior, and shipping patterns, and to build a foundation for sales forecasting using historical order data.


->Phase 1: Dataset Collection

Used the Global Superstore Sales Dataset containing 4 years of retail transaction data.

Dataset includes order details, customer information, shipping modes, and sales values.

Source: Kaggle (licensed under GPL 2).


->Phase 2: Data Cleaning & Preprocessing

Loaded raw sales data using Pandas

Converted date columns (Order Date, Ship Date) into proper datetime format

Removed duplicate records

Handled missing values

Saved a cleaned and reusable dataset for downstream analysis
