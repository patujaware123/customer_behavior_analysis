# Customer Shopping Behavior Analysis

## 📌 Project Overview

Customer Behavior Analysis is an end-to-end data analytics project focused on understanding customer shopping patterns and purchasing behavior.

The project analyzes customer demographics, products, purchase amounts, ratings, discounts, subscriptions, shipping methods, previous purchases, and purchase frequency to identify meaningful business patterns.

---

## 🎯 Business Problem

The objective of the project is to analyze customer shopping data and understand:

- Customer purchasing behavior
- Spending and revenue patterns
- Product and category performance
- Discount and promotional behavior
- Subscription patterns
- Repeat and loyal customer behavior
- Purchasing behavior across different age groups
- Shipping preferences and their relationship with spending

---

## 📂 Dataset

The dataset contains **3,900 customer purchase records** with **18 columns**.

The dataset includes information about:

- Customer demographics
- Products and categories
- Purchase amounts
- Customer ratings
- Discounts and promotions
- Subscription status
- Shipping methods
- Previous purchases
- Payment methods
- Purchase frequency

---

## 🐍 Python Data Analysis

Python and Pandas were used to clean, transform, and prepare the data for further analysis.

### Data Cleaning

- Checked the dataset structure and data types
- Identified missing values
- Handled missing review ratings using category-wise median values
- Standardized column names
- Renamed the purchase amount column
- Checked consistency between discount and promotional fields
- Removed redundant data where required

### Feature Engineering

Two important features were created:

**Age Group**

Customers were categorized into:

- Young Adult
- Adult
- Middle-aged
- Senior

**Purchase Frequency Days**

Purchase frequency was converted into numerical days to support analysis.

---

## 🗄️ PostgreSQL Analysis

The cleaned dataset was loaded into a PostgreSQL database for structured storage and SQL analysis.

**Database:** `customer_behavior`  
**Table:** `customer`

Python was used to connect the dataset with PostgreSQL using SQLAlchemy.

---

## 🔎 SQL Business Analysis

SQL was used to analyze customer behavior and answer business-related questions.

The analysis includes:

- Revenue by gender
- Above-average spending among discounted purchases
- Top products based on review ratings
- Average purchase amount by shipping type
- Subscriber vs. non-subscriber spending and revenue
- Products with the highest discount rates
- Customer segmentation based on previous purchases
- Top products within each category
- Subscription behavior of repeat buyers
- Revenue contribution by age group

SQL techniques used include:

- Aggregate Functions
- `GROUP BY`
- `ORDER BY`
- `CASE`
- Subqueries
- CTEs
- Window Functions
- `ROW_NUMBER()`

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize customer shopping behavior.

### KPIs

- Number of Customers
- Average Purchase Amount
- Average Review Rating

### Filters

- Subscription Status
- Gender
- Category
- Shipping Type

### Visualizations

- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Customer and Subscription Analysis

---

## 💡 Project Outcome

The project transforms raw customer shopping data into structured analysis and interactive visualizations.

The analysis provides insights into customer spending, product performance, discounts, subscriptions, customer segments, purchase behavior, and revenue contribution across different customer groups.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **PostgreSQL**
- **SQL**
- **Power BI**
- **Jupyter Notebook**
