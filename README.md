1.🛍️ Customer Shopping Behavior Analysis

📌 Project Overview

<img width="4872" height="2656" alt="Customer Shopping Behavior Analysis" src="https://github.com/user-attachments/assets/6b4f4c8f-811f-48ac-a6be-ed489187b45f" />

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business decisions.

🧩 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer demographics – Age, Gender, Location, Subscription Status

Purchase details – Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping behavior – Discount Applied, Previous Purchases, Review Rating, Shipping Type

Missing Data: 37 missing values in Review_Rating column (imputed using median per category)

🐍 Exploratory Data Analysis (Python)

Data Loading & Cleaning: Handled missing data and standardized column names to snake_case.

Feature Engineering:

Created age_group by binning customer ages.

Derived purchase_frequency_days to measure buying intervals.

Data Validation: Ensured consistency between discount and promo code features.

Database Integration: Cleaned dataset loaded into PostgreSQL for advanced SQL queries.

🧮 SQL Business Analysis

Key insights derived using PostgreSQL:

Revenue comparison by gender.

Identification of high-spending discount users.

Top 5 products based on average review ratings.

Comparison of average purchase amount by shipping type.

Spend and revenue comparison between subscribers and non-subscribers.

Most discount-dependent products.

Customer segmentation (New, Returning, Loyal).

Top 3 products per category.

Correlation between repeat buyers and subscription likelihood.

Revenue contribution by age group.

📊 Power BI Dashboard


An interactive Power BI dashboard visualizes:

Revenue trends by demographics and product category

Customer segments and subscription status

Discounts and shipping impact on spending behavior

Review ratings and product performance

💡 Business Recommendations

Boost Subscriptions: Offer exclusive benefits and personalized deals.

Loyalty Programs: Reward frequent buyers to enhance retention.

Discount Strategy: Optimize discounts to sustain profitability while driving engagement.

🛠️ Tools & Technologies

Languages: Python, SQL

Database: PostgreSQL

Visualization: Power BI

Libraries: Pandas, NumPy, SQLAlchemy, Matplotlib, Seaborn

📈 Outcome

Delivered actionable insights to improve marketing strategies, customer retention, and revenue forecasting.
