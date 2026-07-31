# 🛒 Northwind Sales Analysis (SQL)

## Project Overview

This project analyses the Northwind sample database to simulate the workflow of a Data Analyst in a commercial environment. Using SQL, the project explores customer purchasing behaviour, product performance, and sales trends to answer real business questions and generate actionable insights.

**Skills:** SQL • MySQL • Relational Databases • Data Exploration • Joins • Aggregations • Business Analysis

---

## Part 1 – Database Familiarisation & Exploration

### Objective

Before analysing the data, the database was explored to understand its structure, relationships, and overall data quality.

### Database Summary

| Table | Records |
|:------|--------:|
| Customers | 93 |
| Orders | 830 |
| Products | 77 |
| Order Details | 2,155 |

### Core Database Structure

The project uses a relational database where multiple tables are connected through primary and foreign keys.

```

Customers

    │

    ▼

Orders

    │

    ▼

OrderDetails

    │

    ▼

Products

    ├── Categories

    └── Suppliers

```

### Key Findings

- Identified the primary business tables required for sales analysis.
- Explored table structures using `DESCRIBE`.
- Validated record counts across the core tables.
- Mapped relationships between customers, orders, products and categories.
- Confirmed revenue must be calculated from `UnitPrice × Quantity × (1 - Discount)` rather than using a stored sales column.

### SQL Concepts Applied

- `SHOW TABLES`
- `DESCRIBE`
- `COUNT()`
- Primary Keys
- Foreign Keys
- Relational Database Design

---
