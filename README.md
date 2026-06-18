🛍️Customer Shopping Behavior Analytics

End-to-end retail data analytics project uncovering customer segments, spending patterns, discount dependency, and subscription behavior using Python, SQL, MYSQL, and Power BI.

📌 Business Objective

Analyze 3,900 retail transactions to understand how customer demographics, purchasing behavior, discounts, shipping preferences, and subscription status influence revenue, repeat purchases, and product performance — and translate these findings into actionable business recommendations.

🗂️ Dataset Overview

Rows: 3,900 transactions

Columns: 18 features

Data Includes:

Customer demographics (Age, Gender, Location, Subscription)

Purchase details (Item, Category, Amount, Season, Size, Color)

Behavioral data (Discounts, Frequency, Ratings, Shipping Type)

Missing Values: 37 in review_rating (handled using category median)

⚙️ Data Preparation (Python)

Data cleaning and preprocessing using pandas

Missing value treatment using category-wise median imputation

Feature engineering:

age_group

purchase_frequency_days

Removed redundant columns after consistency checks

Loaded cleaned data into PostgreSQL for business query analysis

🧠 Business Questions Answered (SQL)

Revenue contribution by gender

High-spending customers who use discounts

Top-rated products by customer reviews

Impact of shipping type on purchase amount

Subscribers vs Non-subscribers revenue comparison

Discount-dependent products

Customer segmentation: New, Returning, Loyal

Top products within each category

Repeat buyers vs subscription likelihood

Revenue contribution by age group

📊 Key Insights

Male customers contribute nearly 2× more revenue than female customers.

Loyal customers dominate the dataset (3116 customers).

Products like Hats, Sneakers, Coats, Sweaters, Pants are highly discount-dependent (≈50%).

Customers using Express shipping spend more per transaction than Standard shipping users.

Young Adults generate the highest total revenue among all age groups.

Repeat buyers are not automatically becoming subscribers — indicating an opportunity to improve subscription value.

📈 Power BI Dashboard

An interactive dashboard was built to visualize:

Revenue by category, gender, and age group

Customer distribution by subscription status

Sales trends across product categories

Shipping preference impact on spending

💡 Business Recommendations

Convert Returning customers → Loyal through loyalty programs

Re-evaluate pricing strategy for discount-dependent products

Target Express shipping users with premium offers

Focus marketing on high-revenue age groups

Strengthen the subscription value proposition

🛠️ Tools & Technologies

Python (pandas, NumPy)

SQL

MYSQL

Power BI
