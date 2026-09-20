# Amazon Sales Data Engineering Project

## 📌 Project Overview
An end-to-end Data Engineering pipeline designed to process, transform, and analyze Amazon Sales data. The project extracts raw transactional sales data, cleans and transforms it using Python and Pandas, and loads structured data into a PostgreSQL database for analytical querying and reporting.

---

## 🏗️ Architecture & Data Flow
1. **Source Data:** CSV Dataset containing raw Amazon sales transactions.
2. **Data Transformation (ETL):** Python & Pandas scripts for data cleaning, handling null values, and format standardization.
3. **Data Loading:** Storing transformed records into PostgreSQL database tables.
4. **Data Analytics:** Analytical SQL queries to extract key sales performance insights.

---

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python
* **Data Processing:** Pandas, NumPy
* **Database:** PostgreSQL / SQL
* **Tools & Environment:** Git, VS Code

---

## 📂 Repository Structure
```text
amazon-data-engineering-project/
├── etl/                # ETL processing scripts
├── sql/                # SQL queries & DDL schema files
├── src/                # Core source code and helper functions
├── .gitignore          # Git ignore file
└── README.md           # Project documentation
