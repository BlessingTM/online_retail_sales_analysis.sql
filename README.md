# Online Retail Sales Analysis

This project analyzes an **online retail transaction dataset** using SQL. The goal is to explore sales performance, identify top customers and products, and uncover business insights through data cleaning and aggregation.

## Dataset Source

The dataset used in this project is the **Online Retail Dataset**, which contains transactional data for an online store.

Source:
https://archive.ics.uci.edu/ml/datasets/online+retail

---

## Project Objectives

The analysis answers several business questions:

- How many transactions exist in the dataset?
- Are there missing values or invalid records?
- How much revenue does the business generate?
- Which products generate the most revenue?
- Which customers contribute the most sales?
- What is the average order value?
- Which countries generate the most sales?
- How do sales change over time?

---

## Data Cleaning

Before performing the analysis, the dataset was cleaned to remove invalid transactions.

Cleaning steps included:

- Removing cancelled invoices (`InvoiceNo` starting with **C**)
- Removing returned items (**negative quantities**)
- Removing rows with **missing values**
- Removing transactions with **zero price or quantity**

A cleaned dataset was created using a SQL **view** called:

`clean_retail_sales`

---

## Key Analyses

The SQL analysis includes:

### Revenue Analysis
- Total revenue
- Average transaction revenue
- Average order value

### Product Analysis
- Top products by revenue
- Top products by quantity sold

### Customer Analysis
- Top customers by revenue
- Customers with the most orders
- Customers with the highest average order value

### Geographic Analysis
- Countries generating the most sales

### Time Analysis
- Monthly revenue trends

---

## SQL Skills Demonstrated

This project demonstrates several core SQL skills:

- Data exploration
- Data cleaning
- Aggregate functions (`SUM`, `AVG`, `COUNT`)
- Filtering and conditional logic
- Grouping with `GROUP BY`
- Sorting and ranking results
- Creating views
- Business-focused analytical queries

---

## Dataset

The dataset used is the **Online Retail dataset**, which contains transactional data for an online store including:

- Invoice numbers
- Product descriptions
- Quantities
- Unit prices
- Customer IDs
- Countries
- Invoice timestamps

---

## Tools Used

- SQL
- SQLite
- DBeaver

---

## Business Insight

The analysis shows that a small number of customers generate a large portion of revenue, highlighting the importance of high-value customers to the business.

---

## Project Structure
