# Sales Data Analysis

## Overview
In this project, I analyzed the sales data of an electronics store. The data consisted of 12 CSV files, each for every month. I joined all the files and performed data cleaning to remove NaN values. I also split the address and added new columns for street, city, state, and zip code.

## Questions Answered
### Q1: Which month had the highest sales?
To answer this question, I extracted the month from the 'Purchase Order Date' column, grouped by month, and calculated the total sales in each month. I also created a 'Sale' column by multiplying the 'Quantity Ordered' and 'Unit Price' columns.

### Q2: Which city sold the most products?
I grouped by the 'City' column and analyzed the revenue for each city to determine the city with the highest sales.

### Q3: What is the best time to advertise for maximum sales?
To answer this question, I converted the 'Order Date' column to datetime format, extracted the hour and minute into separate columns, and analyzed the data with a line chart to determine the best time for advertising.

### Q4: What products are most often sold together?
For this analysis, I identified duplicate order IDs (indicating multiple items bought together), created a list of items in the same order ID, and used itertools' combinations and collections' Counter to find the most frequent combinations. This is a use case of market basket analysis.

### Q5: What is the highest selling product?
I calculated the total quantity sold for each product to determine the highest selling product.

Feel free to explore the repository for detailed code and analysis.
