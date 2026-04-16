#E-Commerce Customer Behavior Analytics


📌 Overview
This project analyzes e-commerce transaction data to optimize Express shipping infrastructure and strategically reallocate marketing budgets toward high-revenue demographic groups (young and middle-aged adults). By moving from raw, unstructured data to an interactive executive dashboard, this pipeline provides actionable intelligence for immediate business application.

📂 Dataset
The analysis is built on the customer_shopping_behavior.csv dataset, which contains detailed transaction records including customer demographics, purchase amounts, shipping methods, and subscription statuses.

🛠️ Tools & Tech Stack
Python (Pandas, NumPy): Engineered the ETL (Extract, Transform, Load) pipeline to clean raw CSV files, perform Exploratory Data Analysis (EDA), handle missing values, format data types, and automate data ingestion.

SQL (MySQL / PostgreSQL): Authored complex queries to extract targeted business metrics and answer core operational questions.

Power BI: Integrated the SQL data pipeline to calculate Key Performance Indicators (KPIs) and design an interactive executive dashboard.

Gamma: Leveraged for rapid, professional presentation design to translate data findings into a high-level executive slide deck.

🚀 Steps & Workflow
Data Extraction & Cleaning (Python): Loaded raw data, identified anomalies, standardized categorical variables, and handled null values to ensure data integrity.

Database Ingestion (Python/SQL): Automated the transfer of clean pandas DataFrames directly into a relational database system.

Data Modeling & Querying (SQL): Executed a series of analytical queries to segment customers (New vs. Returning vs. Loyal), evaluate subscription value, and calculate average purchase amounts across different shipping methods.

Interactive Visualization (Power BI): Connected Power BI directly to the SQL database to build a dynamic, user-friendly interface for stakeholders.

Reporting (Gamma): Summarized the key metrics, technical workflow, and final business recommendations into a structured pitch deck.

📊 The Dashboard
The Power BI dashboard serves as the final analytical product, featuring:

Revenue Demographics: Visual breakdowns of total revenue and average spend segmented by age groups.

Shipping Performance: Comparative analysis of standard vs. express shipping utilization and profitability.

Customer Loyalty Tracking: Interactive filtering between subscribed and non-subscribed user behavior.

💡 Key Results & Business Recommendations
Logistics Optimization: Express shipping demonstrates significantly higher average usage and profitability compared to standard shipping. Recommendation: Increase capital investment in expanding Express shipping infrastructure.

Targeted Marketing Reallocation: Young adult and middle-aged demographics drive the vast majority of total platform revenue. Recommendation: Shift top-of-funnel marketing budgets away from lower-performing age groups and aggressively target these high-value cohorts to increase overall ROAS (Return on Ad Spend).
