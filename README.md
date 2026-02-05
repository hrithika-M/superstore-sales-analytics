# superstore-sales-analytics
This project performs exploratory data analysis (EDA) and time-series analysis on a global superstore retail dataset spanning four years. The goal is to uncover sales trends, customer behavior, and shipping patterns, and to build a foundation for sales forecasting using historical order data.


🔹Phase 1: Dataset Collection

Used the Global Superstore Sales Dataset containing 4 years of retail transaction data.

Dataset includes order details, customer information, shipping modes, and sales values.

Source: Kaggle (licensed under GPL 2).


🔹Phase 2: Data Cleaning & Preprocessing

Loaded raw sales data using Pandas hh

Converted date columns (Order Date, Ship Date) into proper datetime format

Removed duplicate records

Handled missing values

Saved a cleaned and reusable dataset for downstream analysis

🔹 Phase 3: Exploratory Data Analysis (EDA)

Performed in-depth exploratory analysis to understand business patterns and trends:

Analyzed monthly sales trends to identify seasonality

Evaluated sales distribution by customer segment

Identified top-performing cities by total sales

Analyzed shipping mode usage patterns

Visualized insights using clear and interpretable charts

->Key Insights:

Sales exhibit noticeable seasonal trends across years

The Consumer segment contributes the highest share of revenue

Sales are highly concentrated in major metropolitan cities

Standard Class is the most frequently used shipping mode
