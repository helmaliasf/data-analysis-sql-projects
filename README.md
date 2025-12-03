# Supermarket Transactions Analysis

## Overview
This project provides a comprehensive analysis of supermarket transactions using SQL. The dataset includes transactions, products, branches, and customers. The analysis aims to provide insights into sales performance, customer behavior, and product trends across branches and cities.

---

## Dataset / Tables
The project uses **four main tables**:

- **supermarket_transactions**: transactional data (invoice ID, customer type, product category, quantity, unit price, payment method, branch, city)
- **branches**: branch details (branch ID, branch name, city, manager)
- **products**: product details (product ID, product name, category, unit cost, unit price)
- **customers**: customer demographics (customer type, gender, age)

---

## SQL Queries & Analysis
The project includes SQL queries for:

1. **Transactions and Revenue**
   - Total transactions and total revenue
   - Revenue per city and per branch
   - Revenue per product category
   - Revenue per customer type and gender

2. **Branch Analysis**
   - Number of branches per city
   - Branches with highest revenue
   - Branch managers per city

3. **Product Analysis**
   - Number of products per category
   - Products with highest margin and revenue
   - Top-selling products

4. **Customer Analysis**
   - Distribution of customers by type and gender
   - Customers with most transactions
   - Average age per customer type

5. **Combined Analysis (JOIN)**
   - Revenue per city, branch, and product category
   - Customer type revenue per branch
   - Top products by revenue and margin
   - Payment method trends by customer type

---

## Example Insight
- Top 3 product categories generate more than 50% of total revenue.
- Branches in **City A** have higher average transaction value than others.
- **Members** spend more per transaction than non-members.
- **Credit card payments** are the most common method for high-value transactions.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/your-repo.git
