Project Overview:
This project analyzes bike purchase trends using Excel, focusing on demographic and financial factors influencing customer decisions. The analysis includes data cleaning, transformation, and visualization, culminating in an interactive dashboard that provides insights into purchasing patterns.

Key Steps & Process
1. Data Cleaning & Preprocessing
Created a Working Sheet to maintain raw data integrity while performing transformations.
Removed duplicate values to ensure data consistency.
Standardized categorical values for Marital Status and Gender (e.g., "M" → "Male", "S" → "Single").
Modified Income column by rounding decimals for clarity.
2. Feature Engineering & Data Categorization
Age Bracket Classification:
Adolescents (≤ 30), Middle Age (31 – 54), Older Adults (≥ 55)
Formula: =IF(D2<=30, "Adolescent", IF(D2<=54, "Middle Age", "Older Adult"))
Income Bracket Categorization:
< 40K, 40K – 80K, 80K – 120K, 120K – 160K, 160K – 200K
Formula: =IFS(D2<40000, "40K-40K", D2<80000, "40K-80K", D2<120000, "80K-120K", D2<160000, "120K-160K", D2>=160000, "160K-200K")
3. Data Analysis & Insights
Gender & Bike Purchases Pivot Table
Analyzed how gender impacts bike purchases using a pivot table and bar charts.
Commute Distance vs. Bike Purchases
Created a pivot table to examine how commuting habits affect bike ownership.
Renamed "10+ Miles" to "More than 10 Miles" for better sorting.
Age Bracket & Bike Purchases Analysis
Developed a Pivot Table & Line Chart to study purchasing behavior across different age groups.
Income Bracket & Gender Analysis
Built a Clustered Bar Chart to explore how income levels influence bike purchases.
Regional Analysis of Bike Sales
Created a Stacked Bar Chart to visualize purchases based on region and income.
Final Dashboard
The interactive Bike Sales Dashboard provides insights into key purchasing trends with slicers for:
✅ Marital Status
✅ Region
✅ Education
✅ Income Brackets
✅ Commute Distance

![image](https://github.com/user-attachments/assets/76443ab8-9872-4d15-8aaf-bf9862e48d15)

Key Business Insights

📌 1. Middle-aged individuals (31-54) purchase the most bikes.

Why? Likely due to higher disposable income and commuting needs.

Evidence: The "Age Group Analysis" chart shows Middle Age has the highest purchase rate.

📌 2. North America has the highest bike purchase rate, particularly in the 40K-80K income bracket.

Why? This group may use bikes for cost-effective commuting or lifestyle purposes.

Evidence: The "Bike Purchase Rate by Region & Income Bracket" chart highlights North America's dominance.

📌 3. Higher-income individuals ($120K+) purchase fewer bikes than expected.

Why? They may prefer other transportation options or luxury purchases.

Evidence: The "Gender & Income Influence on Bike Purchases" chart shows lower purchase percentages for high-income groups.

📌 4. Commute distance impacts bike purchases—those traveling 1-2 miles buy the most.

Why? Shorter distances make biking a convenient alternative to driving.

Evidence: The "Customer Commute" chart reveals higher purchase rates for short-distance commuters.

📌 5. Women in lower-income brackets (10K-40K) purchase bikes at a slightly higher rate than men.

Why? Biking may serve as a cost-effective mode of transport in this group.

Evidence: The "Gender & Income Influence on Bike Purchases" chart shows a small but noticeable difference in this income segment.

Conclusion:
This project demonstrates business analytics skills in Excel, leveraging data transformation, visualization, and dashboard creation to extract meaningful insights about customer purchasing behavior.
