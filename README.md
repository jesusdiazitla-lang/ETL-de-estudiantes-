# 📊 ETL Project – Excel to SQL Integration (SSIS)

## 📌 Project Overview
This project implements an ETL (Extract, Transform, Load) process using SQL Server Integration Services (SSIS).  
The objective is to integrate student data from Excel files into a SQL Server database.

The solution demonstrates data integration, transformation, and loading techniques commonly used in real-world data engineering workflows.

---

## 🛠 Technologies Used
- SQL Server
- SQL Server Integration Services (SSIS)
- Excel Source
- OLE DB Destination
- Data Conversion Transformation
- Union All Transformation

---

## 🔄 ETL Process Flow

1. **Extract**
   - Data is imported from Excel files.
   - Multiple sheets/files can be unified using *Union All*.

2. **Transform**
   - Data type conversions.
   - Metadata standardization.
   - Validation handling.

3. **Load**
   - Data is inserted into a SQL Server table using OLE DB Destination.

Flow Architecture:

Excel → Union All → Data Conversion → SQL Server

---

## 📂 Project Structure

- `Package.dtsx` → Main SSIS package
- `.dtproj` → SSIS project configuration
- `Project.params` → Project-level parameters

---

## 🎯 Objectives

- Practice ETL pipeline development
- Handle structured data integration
- Apply transformation best practices
- Prepare clean data for relational databases

---

## 🚀 Skills Demonstrated

- ETL Development
- Data Integration
- SSIS Package Design
- SQL Server Connectivity
- Data Type Management
- Project Structuring with Git

---

## 👨‍💻 Author
Jesus Diaz  
Data Engineering Enthusiast
