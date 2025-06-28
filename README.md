# 🛍️ E-Commerce Product & User Analysis with Reviews

## 📌 Project Overview

This project explores and analyzes customer behavior, product performance, and review trends from an e-commerce dataset (Olist). It focuses on uncovering the top-selling products, most active users, and patterns in customer reviews using data visualization and preprocessing techniques.

---

## 🎯 Objectives

- Identify the top 10 best-selling products based on quantity.
- Identify the top 10 most active users by purchase quantity.
- Analyze review distribution and top-rated products.
- Visualize customer satisfaction through review scores.
- Observe purchase quantity trends over time.

---

## 🗂️ Dataset Used

Multiple CSV datasets from the Olist e-commerce database:

- `olist_order_items_dataset.csv`
- `olist_orders_dataset.csv`
- `olist_order_reviews_dataset.csv`

These datasets were merged and cleaned to form a single DataFrame with the following key columns:
- `Product` (product_id)
- `User` (customer_id)
- `Order_Quantity` (number of units per order)
- `Review` (review score)

---

## 🔧 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib
- Jupyter Notebook

---

## 📊 Key Visualizations & Insights

### 1. Top 10 Selling Products
- Visualized using a bar chart.
- Identifies products with the highest total quantities sold.
- Helps in inventory prioritization and marketing.
![image](https://github.com/LAXMAN7795/E-Commerce-Data-Insights/blob/0bf91cd6e5e8dac18c6a90a1dbc11e632165cd12/output/top_products.png)

### 2. Top 10 Users by Quantity Ordered
- Highlights high-volume customers, useful for loyalty programs or targeted marketing.
![image](https://github.com/LAXMAN7795/E-Commerce-Data-Insights/blob/5fe7857307cdfc91fe287832e0c688f09049cd8a/output/top_users.png)

### 3. Top 10 Products by Average Review Score
- All top products have a perfect 5.0 average rating.
- Indicates strong customer satisfaction and reliability.
![image](https://github.com/LAXMAN7795/E-Commerce-Data-Insights/blob/34add5ff252ba9511c60a04383e41f38285dbf38/output/avg_reviews.png)

### 4. Review Score Distribution
- Pie chart shows that:
  - ~57% of reviews are 5 stars
  - ~19% are 4 stars
  - ~13% are 1 star
- Majority satisfaction with some room for quality improvements.
![image]()

### 5. Order Quantity Trend Over Time
- Line chart shows most orders are small in quantity.
- Occasional large-quantity spikes may indicate bulk or business orders.

---

## 🧼 Data Cleaning Steps

- Merged datasets on `order_id`.
- Dropped irrelevant columns.
- Renamed columns for clarity.
- Handled missing values in review scores using median imputation.

---

## 📁 Output Files

- `top_products.png`
- `top_users.png`
- `top_reviews.png`
- `review_distribution.png`
- `quantity_trend.png`

These are automatically saved when the notebook is executed.

---

## 🚀 How to Run

1. Clone this repository.
2. Place the dataset CSV files in the root directory.
3. Run the Jupyter Notebook step-by-step.
4. Visual outputs will be displayed and saved.

---

## 📌 Conclusion

This analysis helps businesses:
- Understand customer satisfaction
- Identify key products and users
- Plan product recommendations and inventory
- Enhance customer retention with data-driven strategies

---

## 🙌 Acknowledgments

Data source: [Olist e-commerce public dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
