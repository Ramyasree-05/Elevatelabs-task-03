# 📦 E-commerce Product Data Analysis using MySQL

## 📝 Overview

This project involves analyzing product-related data from an e-commerce platform using **MySQL Workbench**. The dataset is provided in CSV format and processed using SQL queries for data exploration, cleaning, and analysis.

---

## 📁 Project Files

### 1. `output.csv`
A CSV file containing raw e-commerce product data. Columns include:
- `Unnamed: 0`: Row index (can be ignored).
- `_id`: Unique product ID.
- `actual_price`: The product's original price (may contain commas).
- `average_rating`: Average customer rating.
- `brand`: Product brand.
- `description`: Discount or product summary.
- `seller`: Name of the seller or store.

### 2. `outputtask03.sql`
A SQL script that:
- Drops and recreates the `ecommerceoutput` database.
- Creates a table `output` matching the structure of `output.csv`.
- Performs several queries and transformations for analysis.

---
 Use Cases
Product pricing insights

Identifying top-rated brands

Finding high-value sellers

Creating dashboards or reports based on views and aggregated metrics

Requirements
MySQL Workbench

A running MySQL server

Dataset file output.csv

 Notes
Make sure to clean the actual_price column (remove commas) before applying numeric filters.

The view high_rated_products simplifies analysis of top-performing products.

Indexing the brand column improves performance for filter and search operation

## 🔧 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/Ramyasree-05/Elevatelabs-task-03/edit/main/README.md
