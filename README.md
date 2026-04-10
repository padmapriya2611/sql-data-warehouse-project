# sql-data-warehouse-project
Building a modern data warehouse with SQL server, including ETL processes, data modeling, and analytics.
# 📊 SQL Data Warehouse Project

## 🔷 Project Overview

This project demonstrates the implementation of a Data Warehouse using SQL by following an end-to-end ETL process. The project is inspired by a guided tutorial and focuses on transforming raw data into business-ready insights using a layered architecture.

---

## 🧱 Architecture

This project follows the **Medallion Architecture**:

* **Bronze Layer**: Raw data ingestion from source systems
* **Silver Layer**: Data cleaning, transformation, and integration
* **Gold Layer**: Aggregated data for business reporting

---

## 🔄 ETL Process

### 🔹 Extract (Bronze)

* Loaded raw data from CSV files
* Stored data without any transformation

### 🔹 Transform (Silver)

* Removed duplicates
* Handled missing values
* Joined multiple tables
* Applied business logic using CASE statements
* Standardized data formats

### 🔹 Load (Gold)

* Created aggregated tables
* Calculated key metrics like total sales
* Prepared final dataset for reporting

---

## 🧠 Key Concepts Implemented

* ETL (Extract, Transform, Load)
* Data Cleaning & Transformation
* Joins (INNER JOIN, LEFT JOIN)
* Aggregations (SUM, COUNT, GROUP BY)
* CASE statements for business logic
* Medallion Architecture (Bronze, Silver, Gold)

---

## 📂 Project Structure

```
├── datasets/        # Raw data (Bronze layer)
├── scripts/         # SQL scripts (ETL process)
├── docs/            # Architecture and notes
```

---

## 📊 Sample Use Cases

* Customer segmentation
* Sales categorization
* Aggregated sales analysis

---

## 🛠️ Tools Used

* SQL Server
* SSMS
* CSV datasets

---

## 🚀 Learning Outcome

* Understood how to design a Data Warehouse
* Learned how to build ETL pipelines
* Practiced writing SQL for real-world scenarios
* Gained experience with layered data architecture

---

## 🙌 Conclusion

This project demonstrates practical understanding of Data Warehouse concepts, ETL processes, and SQL-based data transformation.
