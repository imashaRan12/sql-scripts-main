# SQL Mastery: End-to-End Database Operations

This repository contains a comprehensive collection of SQL scripts designed to demonstrate proficiency in querying, manipulating, and managing relational data. Using a multi-table schema, these scripts cover the full spectrum of SQL operations—from fundamental CRUD tasks to advanced analytical queries.

---

## 📂 Dataset Overview

The project utilizes five interconnected datasets (provided in CSV format):

- **Customers:** Client demographic and contact information.
- **Employees:** Staff hierarchy, roles, and organizational structure.
- **Orders:** Active transaction records and shipping details.
- **OrdersArchive:** Historical transaction data used for auditing and long-term trend analysis.
- **Products:** Inventory details, pricing, and category management.

---

## 🚀 Key SQL Concepts Covered

The scripts are organized to demonstrate a logical progression of database engineering skills:

1.  **Data Definition (DDL):** Creating robust table structures, defining primary/foreign keys, and enforcing data integrity.
2.  **Advanced Retrieval:** Utilizing `SELECT`, `WHERE`, `LIKE`, and `ORDER BY` for precise data filtering.
3.  **Relational Joins:** Connecting multiple tables using `INNER`, `LEFT`, `RIGHT`, and `FULL` joins to extract holistic insights.
4.  **Aggregations & Grouping:** Calculating business metrics using `COUNT`, `SUM`, `AVG`, and `GROUP BY/HAVING`.
5.  **Data Manipulation (DML):** Standard `INSERT`, `UPDATE`, and `DELETE` operations, including archiving logic.
6.  **Conditional Logic:** Using `CASE` statements and `UNION` operators for customized data reporting.

---

## 🛠️ Important Links & Tools:

Everything is for Free!

- **[Datasets](datasets/):** Access to the course dataset (csv files).
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI for managing and interacting with databases.

---

## 📂 Repository Structure

```
sql-ultimate-course/
│
├── datasets/                           # Raw datasets
│
├── docs/                               # diagram
│
└── scripts/                            # All codes
```

---

## 🛠️ Getting Started

1.  **Cloning the Repository:**
    ```bash
    git clone https://github.com/imashaRan12/sql-scripts-main.git
    cd sql-scripts-main
    ```
2.  **Import Data:** Load the provided `.csv` files into your SQL environment (e.g., PostgreSQL, MySQL, or SQL Server).
3.  **Schema Setup:** Execute the initialization scripts to create the tables and relationships.
4.  **Run Queries:** Explore the script folders to run specific analysis or maintenance queries.

---
