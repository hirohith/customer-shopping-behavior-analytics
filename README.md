# 🛍️ Customer Shopping Behavior Analytics

An end-to-end retail data analytics project that analyzes customer purchasing behavior to uncover spending patterns, customer segments, discount dependency, and subscription trends using **Python, SQL, MySQL, and Power BI**.

---

## 📖 Project Overview

Retail businesses generate large amounts of customer transaction data every day. This project analyzes **3,900 customer transactions** to identify purchasing trends and customer behavior that can help improve business decisions.

The project covers the complete analytics workflow—from data cleaning and preprocessing to SQL-based business analysis and interactive Power BI dashboards.

---

## 🎯 Business Objective

The primary objective of this project is to analyze customer purchasing behavior and identify how factors such as:

* Customer demographics
* Purchase history
* Discounts
* Shipping preferences
* Subscription status

influence revenue, repeat purchases, and product performance, ultimately providing actionable business recommendations.

---

## 📂 Dataset Information

| Attribute      | Details            |
| -------------- | ------------------ |
| Dataset Size   | 3,900 Transactions |
| Features       | 18 Columns         |
| Missing Values | 37 (Review Rating) |
| Database       | MySQL              |

### Dataset Includes

* Customer Demographics

  * Age
  * Gender
  * Location
  * Subscription Status

* Purchase Information

  * Product
  * Category
  * Purchase Amount
  * Season
  * Size
  * Color

* Customer Behavior

  * Discount Applied
  * Purchase Frequency
  * Review Rating
  * Shipping Type

---

## ⚙️ Data Preparation (Python)

The dataset was cleaned and preprocessed using **Pandas**.

### Tasks Performed

* Removed inconsistencies
* Treated missing values using category-wise median imputation
* Performed data validation and consistency checks
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Removed redundant columns
* Loaded the cleaned dataset into **MySQL** for SQL analysis

---

## 🗄️ SQL Business Analysis

Business questions answered include:

* Revenue contribution by gender
* Revenue contribution by age group
* High-spending customers using discounts
* Subscribers vs Non-subscribers revenue comparison
* Customer segmentation (New, Returning, Loyal)
* Top-rated products
* Best-selling products within each category
* Discount-dependent products
* Impact of shipping type on spending
* Repeat buyers vs subscription likelihood

---

## 📊 Key Insights

* Male customers contribute nearly **2× more revenue** than female customers.
* **Young Adults** generate the highest overall revenue.
* **Loyal customers (3,116)** dominate the customer base.
* Products such as **Hats, Sneakers, Coats, Sweaters, and Pants** are highly discount-dependent (~50% of purchases).
* Customers choosing **Express Shipping** spend more per transaction than Standard Shipping users.
* Repeat buyers are not necessarily becoming subscribers, indicating an opportunity to improve subscription benefits.

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize:

* Revenue by product category
* Revenue by gender
* Revenue by age group
* Customer distribution by subscription status
* Sales across product categories
* Shipping preference impact on purchase amount

---

## 💡 Business Recommendations

* Introduce loyalty programs to convert returning customers into loyal customers.
* Re-evaluate pricing strategies for products heavily dependent on discounts.
* Target Express Shipping customers with premium offers and personalized promotions.
* Focus marketing campaigns on high-revenue age groups.
* Enhance the subscription program to improve customer retention and conversion.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* SQL
* MySQL
* Power BI

---

## 📁 Project Structure

```
Customer-Shopping-Behavior-Analytics/
│
├── Dataset/
│   └── shopping_behavior.csv
│
├── Python/
│   └── data_cleaning.ipynb
│
├── SQL/
│   └── business_queries.sql
│
├── PowerBI/
│   └── Customer_Shopping_Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

---

## 🚀 Project Workflow

1. Data Collection
2. Data Cleaning & Preprocessing (Python)
3. Feature Engineering
4. Load Data into MySQL
5. Business Analysis using SQL
6. Dashboard Development in Power BI
7. Business Insights & Recommendations

---

## 📌 Conclusion

This project demonstrates the complete data analytics lifecycle by transforming raw retail transaction data into meaningful business insights. Through Python-based preprocessing, SQL analysis, and Power BI visualization, it showcases practical skills in data cleaning, exploratory analysis, business intelligence, and data-driven decision-making.
