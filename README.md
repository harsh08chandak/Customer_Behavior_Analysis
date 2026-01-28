# Customer Shopping Behavior Analysis
## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. The objective is to uncover insights related to spending patterns, customer segmentation, product performance, and subscription behavior to support data-driven business decisions.

Tools used: **Python (Pandas), SQL (MySQL), and Power BI**.

---

## 📊 Dataset Summary

* **Rows:** 3,900
* **Columns:** 18
* **Key Features:**

  * Customer Demographics: Age, Gender, Location, Subscription Status
  * Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
  * Shopping Behavior: Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type
* **Missing Values:** 37 missing values in the *Review Rating* column

---

## 🧹 Data Cleaning & Feature Engineering (Python)

* Loaded dataset using Pandas
* Performed initial exploration using `.info()` and `.describe()`
* Handled missing values by imputing median ratings per product category
* Renamed columns to snake_case for consistency
* Created new features:

  * `age_group` by binning age values
  * `purchase_frequency_days` from purchase frequency
* Removed redundant columns after consistency checks
* Loaded cleaned data into PostgreSQL database for SQL analysis

---

## 🗄️ SQL Analysis (MySQL)

Key business questions answered:

1. Revenue comparison by gender
2. High-spending customers using discounts
3. Top 5 products by average rating
4. Average purchase amount by shipping type
5. Subscriber vs non-subscriber revenue comparison
6. Products with highest discount dependency
7. Customer segmentation (New, Returning, Loyal)
8. Top 3 products in each category
9. Subscription behavior of repeat buyers
10. Revenue contribution by age group

---

## 📈 Power BI Dashboard

An interactive dashboard was created to visualize:

* Revenue trends
* Customer segmentation
* Product performance
* Subscription insights
* Shipping behavior

This helps stakeholders quickly understand business performance and customer behavior.

---

## 💡 Business Recommendations

* Promote subscription benefits to increase loyalty
* Implement reward programs for repeat customers
* Optimize discount strategy to protect profit margins
* Highlight best-selling and highly rated products
* Target marketing campaigns based on age group and shipping preferences

---

## 🛠️ Technologies Used

* Python (Pandas, NumPy)
* SQL (MySQL)
* Power BI
* Jupyter Notebook

---

## 🚀 How to Run

1. Clone this repository
2. Install required Python libraries
3. Run the notebook for data cleaning and analysis
4. Load processed data into PostgreSQL
5. Open Power BI dashboard file to explore insights

---

## 📬 Author

**Harsh**
Aspiring Data Scientist | Continuous Learner

