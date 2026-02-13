Customer Shopping Behavior Analysis

📌 Overview

This project analyzes customer shopping behavior using a retail transaction dataset (~3,900 records) to identify purchasing trends, revenue drivers, discount usage patterns, subscription behavior, and shipping preferences.

The workflow mirrors a practical data analytics pipeline combining Python, SQL, and Power BI to generate business-oriented insights.

📂 Dataset

• Source File: customer_shopping_behavior.csv
• Records: ~3,900 transactions
• Domain: Retail / Customer Behavior Analytics

Key Features:

• Customer demographics (Age, Gender)
• Product information (Item, Category)
• Transaction data (Purchase Amount, Season)
• Customer behavior (Previous Purchases, Frequency)
• Business variables (Discount, Subscription, Shipping)
• Customer feedback (Review Rating)

🛠 Tools & Technologies

• Python (Pandas, NumPy, Matplotlib, Seaborn) — Data loading, EDA, preprocessing, and feature engineering

• SQL (PostgreSQL / MySQL / SQL Server) — Data querying, aggregations, and analytical exploration

• Power BI — Interactive dashboard creation and visual analysis

• Gamma — Presentation and reporting

• GitHub — Version control and project documentation

🚀 Analytical Workflow

1. Data Preparation (Python)
• Loaded dataset and inspected structure
• Validated data types and distributions
• Identified missing values and anomalies

2. Data Cleaning & Transformation
• Standardized column naming conventions
• Handled missing values via median imputation
• Removed redundant or low-impact features

3. Feature Engineering
• Created age group categories
• Built customer segmentation logic (New / Returning / Loyal)
• Generated purchase frequency metrics

4. SQL-Based Analysis
• Evaluated revenue distribution patterns
• Compared subscriber vs non-subscriber behavior
• Analyzed discount usage trends
• Identified high-spending customer segments
• Assessed product & category performance

5. Dashboard Development (Power BI)
• Designed interactive visuals and KPIs
• Built sales and customer behavior views
• Implemented slicers and filters
• Created business-focused insights dashboard

6. Reporting & Presentation
• Documented findings in PDF report
• Created presentation using Gamma

📊 Dashboard

• File: customer service dashboard.pbix
• Tool: Power BI Desktop

Dashboard Highlights:

• Revenue and purchase analysis
• Customer segmentation breakdown
• Shipping preference insights
• Subscription & discount patterns
• Interactive filtering experience

🔍 Key Insights

• Loyal customers generated the majority of transactions
• Faster shipping options correlated with higher purchase amounts
• Discount dependency varied across product categories
• Subscription status influenced purchasing behavior
• Demographic factors impacted revenue contribution

💼 Business Value

This analysis supports data-driven decision making in:

• Customer targeting & marketing strategies
• Discount optimization
• Subscription program evaluation
• Product prioritization
• Revenue performance analysis

▶ How to Run

Python Analysis

jupyter lab


Open:

coustomer_shopping_behaviour.ipynb


SQL Queries

Run:

Customer-Shopping-Behavior-Analysis.sql


Using PostgreSQL / MySQL / SQL Server.

Power BI Dashboard

Open in Power BI Desktop:

customer service dashboard.pbix
<img width="2474" height="1400" alt="image" src="https://github.com/user-attachments/assets/2eb927bd-b9b6-4171-aee2-5597c123d43a" />
