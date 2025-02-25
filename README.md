Data Cleaning and Preparation Steps
1. Standardized Column Names
Ensured uniform column naming conventions to prevent errors in formulas and references.
2. Handled Missing Values
Checked for missing values in Customer Email, Loyalty Card, and Address.
Missing emails were left blank instead of being imputed.
3. Corrected Data Types
Ensured Order Date was formatted as a date type.
Converted Quantity, Unit Price, and Sales to numerical data types for calculations.
4. Standardized Coffee and Roast Type Names
Created new readable columns:
Coffee Type Name → Mapped codes like "Ara" to "Arabica".
Roast Type Name → Mapped "M" to "Medium", "L" to "Light", etc.
5. Created New Calculated Fields
Sales = Quantity × Unit Price
Price per 100g = Unit Price / Size × 100
Profit = Estimated based on pricing strategy
Pivot Tables and Their Purpose
Several pivot tables were created to summarize key insights dynamically:

1. Total Sales by Country
Purpose: Identifies sales distribution across different countries.
Key Insight: The United States and Ireland contribute the most to sales revenue.
2. Top 5 Customers by Sales
Purpose: Highlights the highest-spending customers.
Key Insight: A few customers make up a large portion of total revenue, suggesting high-value customers who may be targeted for loyalty programs.
3. Product Performance (Sales by Coffee Type & Roast Type)
Purpose: Determines the best-selling coffee types and roasts.
Key Insight:
Arabica and Robusta are the best-selling coffee types.
Medium and Light roasts are the most preferred.
4. Monthly Sales Trend Analysis
Purpose: Tracks sales trends over time.
Key Insight: Helps identify seasonal trends, which can be used to optimize inventory and marketing efforts.
5. Customer Loyalty Analysis
Purpose: Compares sales between customers with and without a loyalty card.
Key Insight: Loyalty card holders tend to make larger purchases, reinforcing the need to promote loyalty programs.
Slicers and Their Purpose
Slicers were added to improve interactivity in the pivot tables and dashboards:

1. Date Slicer (Order Date)
Allows filtering of sales data by specific timeframes (Year, Quarter, Month).
Useful for trend analysis and identifying peak sales periods.
2. Country Slicer
Enables filtering of sales and customer data by country.
Helps analyze regional sales performance.
3. Coffee Type Slicer
Filters sales by Arabica, Robusta, Excelsa, etc.
Helps in identifying the most popular coffee types per region or time period.
4. Roast Type Slicer
Filters data based on roast preferences (Light, Medium, Dark).
Assists in understanding customer taste preferences.
5. Loyalty Card Slicer
Filters sales based on loyalty membership status.
Helps analyze how customer loyalty impacts sales and repeat purchases.
Key Business Insights from the Analysis
United States and Ireland drive the majority of sales, making them key markets.
Arabica and Robusta coffees are the most popular choices, indicating strong customer preference.
Medium and Light roasts outperform Dark roasts, suggesting customer taste preferences.
Loyalty members purchase more per transaction, reinforcing the importance of a customer retention strategy.
Sales fluctuate across months, indicating potential seasonal demand trends for coffee.
