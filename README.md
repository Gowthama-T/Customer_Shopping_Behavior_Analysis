# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

<img width="800" alt="Customer Shopping Behavior Analysis" src="https://github.com/user-attachments/assets/6b4f4c8f-811f-48ac-a6be-ed489187b45f" />

This project analyzes **customer shopping behavior** using transactional data from **3,900 purchases** across multiple product categories.
The goal is to uncover insights into **spending patterns, customer segments, product preferences**, and **subscription behavior** to support data-driven business decisions.

---

## 🧩 Dataset Summary

| **Property**     | **Details**                                                              |
| ---------------- | ------------------------------------------------------------------------ |
| **Rows**         | 3,900                                                                    |
| **Columns**      | 18                                                                       |
| **Missing Data** | 37 missing values in `Review_Rating` (imputed using median per category) |

### 🔑 Key Features

* **Customer Demographics:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
* **Shopping Behavior:** Discount Applied, Previous Purchases, Review Rating, Shipping Type

---

## 🐍 Exploratory Data Analysis (Python)

**Steps Performed:**

* 🧹 **Data Loading & Cleaning:** Handled missing values and standardized column names to `snake_case`.
* 🧠 **Feature Engineering:**

  * Created `age_group` by binning customer ages.
  * Derived `purchase_frequency_days` to track buying intervals.
* ✅ **Data Validation:** Checked consistency between `discount_applied` and `promo_code_used`.
* 💾 **Database Integration:** Loaded the cleaned DataFrame into **PostgreSQL** for SQL-based analysis.

---

## 🧮 SQL Business Analysis

Key insights derived using **PostgreSQL**:

1. 💰 **Revenue by Gender** – Compared total revenue by male vs. female customers.
2. 🏷️ **High-Spending Discount Users** – Identified customers using discounts but spending above average.
3. ⭐ **Top 5 Products by Rating** – Products with the highest average review ratings.
4. 🚚 **Shipping Type Comparison** – Compared purchase amounts between Standard and Express shipping.
5. 👥 **Subscribers vs. Non-Subscribers** – Compared spend and revenue differences.
6. 💸 **Discount-Dependent Products** – Found products with the highest discounted purchase ratio.
7. 🔁 **Customer Segmentation** – Classified into *New*, *Returning*, and *Loyal* customers.
8. 🛒 **Top 3 Products per Category** – Listed most purchased products in each category.
9. 📈 **Repeat Buyers & Subscriptions** – Checked correlation between >5 purchases and subscription likelihood.
10. 🎯 **Revenue by Age Group** – Calculated total revenue contribution by each age group.

---

## 📊 Power BI Dashboard
![Uploading Screenshot (135).png…]()


An **interactive Power BI dashboard** visualizes key insights, including:

* Revenue trends by demographics and category
* Customer segments and subscription distribution
* Impact of discounts and shipping on spending
* Product ratings and performance metrics

---

## 💡 Business Recommendations

✅ **Boost Subscriptions:** Offer exclusive benefits and personalized deals to subscribers.
🎁 **Loyalty Programs:** Reward frequent buyers to strengthen customer retention.
⚖️ **Optimize Discount Strategy:** Balance between sales boost and profit margins.

---

## 🛠️ Tools & Technologies

| **Category**      | **Tools Used**                                 |
| ----------------- | ---------------------------------------------- |
| **Languages**     | Python, SQL                                    |
| **Database**      | PostgreSQL                                     |
| **Visualization** | Power BI                                       |
| **Libraries**     | Pandas, NumPy, SQLAlchemy, Matplotlib, Seaborn |

---

## 📈 Outcome

Delivered **actionable insights** to improve marketing strategies, enhance customer retention, and forecast revenue growth.

