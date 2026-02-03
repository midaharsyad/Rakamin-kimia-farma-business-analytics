# Kimia Farma Business Performance Analytics (2020–2023)

## 📌 Project Overview
This project was developed as part of the **Big Data Analytics Internship Program at Kimia Farma (Rakamin Academy)**.  
The main objective of this project is to analyze Kimia Farma’s business performance during the period **2020–2023** using transactional, product, inventory, and branch data.

The analysis aims to provide insights related to sales performance, profit trends, customer ratings, and regional branch performance to support data-driven business decisions.

---

## 📂 Datasets Used
This project uses four datasets provided by Kimia Farma:

1. **kf_final_transaction**  
   Contains transaction-level data such as transaction date, product ID, branch ID, price, discount, and transaction rating.

2. **kf_product**  
   Contains product master data including product name, product category, and base price.

3. **kf_inventory**  
   Contains inventory stock data for each product at each branch.

4. **kf_kantor_cabang**  
   Contains branch master data including branch name, city, province, and branch rating.

---

## 🛠 Tools & Technologies
- **Google BigQuery** – Data storage, data processing, and SQL-based analysis  
- **Google Looker Studio** – Data visualization and interactive dashboard creation  
- **Visual Studio Code** – SQL script documentation  
- **GitHub** – Version control and project repository  

---

## 🧱 Data Preparation
The data preparation process consists of the following steps:

1. Importing all four datasets into **Google BigQuery**
2. Ensuring correct data types (e.g., DATE, INTEGER, FLOAT)
3. Joining all datasets into a single **analysis table**
4. Creating calculated fields to support business analysis, such as:
   - Gross profit percentage
   - Nett sales
   - Nett profit

The final analysis table is stored in BigQuery as:

rakamin_academy.kimia_farma.analysis_table

