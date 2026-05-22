                                                          SQL Data Analysis Project
--> Project Overview
This project focuses on SQL Exploratory Data Analysis (EDA) and Advanced Analytics to extract actionable business intelligence from raw datasets. It covers the entire data analysis lifecycle, from initial data exploration to complex analytical reporting, providing critical insights into customer and product performance.

--> Core Analytics Phases
1. Exploratory Data Analysis (EDA)
•	Database Profiling: Comprehensive investigation into data distribution, identification of key dimensions and measures, and thorough checks for data quality issues.
•	Insight Discovery: Uncovering significant business trends, such as top-performing products and customer segments, by combining descriptive dimensions with quantitative metrics.

2. Advanced Data Analytics
•	Advanced SQL Techniques: Utilization of various Window Functions (e.g., RANK(), DENSE_RANK(), LEAD(), LAG(), and SUM() OVER()) to perform sophisticated analyses, including time-series analysis, month-over-month, and year-over-year comparisons.
•	Complex Reporting: Development of consolidated views to address critical business questions and generate insightful reports for stakeholders.

--> Key Technical Skills
•	Window Functions: Expertise in using RANK(), DENSE_RANK(), LEAD(), LAG(), and SUM() OVER() for advanced analytical queries.
•	Advanced Querying: Proficient use of Common Table Expressions (CTEs) and Subqueries to streamline complex logic and enhance query readability.
•	Business Logic Implementation: Applying segmentation, ranking, and trend analysis to drive informed decision-making.

--> Project Structure
. 
├── Scripts/
│   ├── Change_Over_Time_Analysis.sql
│   ├── Cumulative_Analysis.sql
│   ├── Data_Segmentation.sql
│   ├── Magnitude_Analysis.sql
│   ├── Part_To_Whole_Analysis.sql
│   ├── Performance_Analysis.sql
│   ├── Ranking_Analysis.sql
│   ├── Report_Cust.sql
│   └── Report_Products.sql
├── DataWarehouseAnalytics.bak
└── Detailed_Insights

•	Scripts/: Contains all SQL scripts used for various analytical tasks.
•	DataWarehouseAnalytics.bak: Database backup file.
•	Detailed_Insights: A document outlining the key business insights derived from the analysis.

--> Key Business Insights
The analysis yielded several critical insights into customer and product performance:

--> Customer Insights
•	Revenue Distribution: Revenue is broadly distributed across customer segments (New: 38%, VIP: 37%, Regular: 25%), indicating strong acquisition but weak long-term loyalty.
•	Customer Retention: Significant retention issues are present, with 63% one-time buyers and 92% having a lifespan under 6 months. Only 0.6% stay beyond 10 months.
•	Customer Value Behavior: High Average Order Value (AOV) of $911 but low Average Monthly Spend of $452, suggesting infrequent high-value purchases.
•	High-Value Demographic: Customers aged 50+ are primary revenue drivers (66% of total revenue), followed by 30-39 year olds (32%).
•	Revenue Concentration: The top 20% of customers contribute only 34% of total revenue, indicating a broad but less loyal customer base.

--> Product Insights
•	Category Dependency: The business is highly reliant on the 'Bikes' category, which generates 96% of total revenue.
•	Subcategory Concentration: 'Road Bikes' alone contribute 50% of total revenue, posing a dependency risk.
•	Product Performance: A small set of high-performing products accounts for 94% of total revenue, while most others underperform.
•	Order Volume vs. Revenue: 'Accessories' have high order volume (60% of total orders) but contribute relatively low revenue, serving as supporting products.

--> Cross-Functional Insights
•	Customer-Product Dependency: High-value customers predominantly contribute revenue through bike purchases, reinforcing the single-category dependency.
•	Business Model: The business model is characterized by high-value, low-frequency purchases rather than consistent repeat buying.

--> Overall Conclusion
The project highlights the business's strong revenue generation capabilities but also identifies critical areas for improvement, particularly in customer retention and reducing dependency on specific product categories/segments to mitigate risk and foster sustainable growth.

