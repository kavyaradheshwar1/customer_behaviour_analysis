# customer_behaviour_analysis
Customer Shopping Behavior — End-to-End Data Analytics Project
🔍 Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The objective is to understand:

spending patterns

product preferences

subscription behavior

customer segments

and translate these insights into clear business recommendations.

The project follows a full analytics pipeline — from raw data to dashboard and presentation.

📁 Dataset

Rows: 3,900
Columns: 18

Key features include:

Demographics: Age, Gender, Location, Subscription Status

Purchases: Item, Category, Amount, Season, Size, Color

Behavior: Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type

Missing data: 37 values in Review Rating (handled during cleaning)

🛠️ Tools & Technologies

Python (Pandas, NumPy, Matplotlib/Seaborn) – EDA, cleaning, feature engineering

 MySQL – structured business queries

Power BI – interactive dashboard

Gamma – presentation & storytelling


🧭 Project Steps
1️⃣ Load & Explore Data (Python)

Imported data using pandas

Reviewed structure with info() and describe()

Checked duplicates and missing values

2️⃣ Data Cleaning & Preparation

Imputed missing review ratings (median per category)

Standardized column names (snake_case)

Dropped redundant fields (promo_code_used)

Ensured datatype consistency

3️⃣ Feature Engineering

Created age_group (binned age ranges)

Created purchase_frequency_days

Prepared a clean dataset for SQL analysis

4️⃣ SQL Analysis (MySQL)

Loaded the dataset into the database and answered key business questions such as:

Revenue by gender

High-spending discount users

Top products by rating

Standard vs express shipping spend

Subscriber vs non-subscriber value

Discount-dependent products

Customer segmentation (New, Returning, Loyal)

Top products per category

Subscription likelihood among repeat buyers

Revenue by age group

5️⃣ Dashboard (Power BI)

Designed an interactive dashboard to visualize:

KPIs and revenue trends

Customer segments

Product performance

Subscription & discount behavior

6️⃣ Reporting & Presentation

Wrote a concise insights report

Built a Gamma presentation summarizing findings and recommendations


📈 Key Results & Insights

Discounts boost sales — but high spenders still purchase without deep discounts.

Loyal and returning customers generate significantly higher lifetime value.

Certain product categories rely heavily on discounts.

Express shipping customers tend to spend more.

Specific age groups contribute the majority of revenue.

🎯 Business Recommendations

Promote subscription benefits to increase recurring revenue

Introduce loyalty rewards for repeat buyers

Optimize discount strategy to protect margins

Highlight top-rated and best-selling products in campaigns

Target high-value segments with focused marketing

▶️ How to Run This Project
Requirements

Python 3.x

MySQL 

Power BI Desktop

Gamma account (for presentation)

Steps

Clone this repository

Open the Python notebook and run the EDA/cleaning workflow

Load the cleaned dataset into MySQL

Run the SQL queries provided

Open the Power BI file and refresh the data

View the final report and presentation

⭐ What This Project Demonstrates

✔ End-to-end analytics workflow
✔ Strong EDA and data cleaning
✔ SQL for business-driven questions
✔ Dashboard storytelling
✔ Clear communication of insights and recommendations
