# Jean-Darius_Portfolio

Project: Sales Performance

SUMMARY 

This project aimed to evaluate and improve the sales performance of Coffee Shop by analyzing historical sales data. The primary objectives were to identify sales trends, assess the effectiveness of sales strategies, and uncover key factors influencing sales outcomes.

RESEARCH QUESTIONS

Which types of coffee have the highest sales volume?

Which types of coffee generate the highest profit margins?

During which time periods does the company experience peak sales?

DATA SOURCES

Data from various sources sales transactions were collected and cleaned for analysis. The original data contains variables such as date (3/1/2024), datetime (3/1/2024  10:15:51 AM), cash_type (card/cash), card (te number of the card used to purchase), money (how much the customer paaid when ordered a type coffee), coffee_name (the specific coffee the customer purchased).

DATA PREPARATION

The raw data contains has been imported to Microsot Power BI for analyis. It contains some inconsitencies that muust be handled to make it suitable for the analyis. 

Features engineering

We created new feature called Time by spliting the original column datetime (3/1/2024  10:15:51 AM) into Column (Date) → 3/1/2024 and Column 2 (Time) → 10:15:51 AM.  The Column (Time) → 10:15:51 AM is also splitted into Column  (Time) → 10:15:51 and Column (Time Period) → AM/PM. This will enable us to identify the period that the company experience peak sales.

Data Cleaning (missing values, duplicate values)

Data profiling technique has been implemented to analyze the data to better understand its structure, quality, and content. 9% of the variable card are empty. However, this variable will not conttribute to our analyis we can remove it from the data.

Data conversion



