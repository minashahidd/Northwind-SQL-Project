## 📊 Project Overview

### Northwind Sales Analysis (SQL)

An end-to-end SQL analysis project using the Northwind relational database to simulate a real-world Data Analyst workflow.

The objective is to explore customer behaviour, sales performance, and product trends by transforming raw relational data into meaningful business insights.

## 🗄️ Database Overview

The database contains multiple connected tables representing a fictional trading company:

- Customers
- Orders
- Order Details
- Products
- Categories
- Suppliers
- Employees
- Shippers

### Dataset Summary

| Table | Records |
|---|---:|
| Customers | 93 |
| Orders | 830 |
| Products | 77 |
| Order Details | 2,155 |

## 🛠️ Skills Demonstrated

- SQL data exploration
- Relational database analysis
- Joins and table relationships
- Aggregations and business metrics
- Data quality checks
- Customer and product analysis
- Advanced SQL techniques

## 🎯 Business Objective

Analyse sales data to answer key business questions:

- Which products generate the most revenue?
- Who are the highest-value customers?
- Which categories perform best?
- What sales trends can support decision-making?

## 🏗️ Database Structure

The Northwind database follows a relational model where tables are connected through primary and foreign keys.

Key relationships:

Customers → Orders  
- One customer can place multiple orders.

Orders → Order Details  
- One order can contain multiple products.

Products → Categories  
- Products are grouped into categories.

## 🏗️ Database Relationships

The analysis uses a relational database structure:

Customers

→ Orders

→ Order Details

→ Products

→ Categories

Key relationships:

- One customer can place multiple orders.
- One order can contain multiple products.
- Products belong to different categories.
- Revenue is calculated from Unit Price × Quantity × Discount.
