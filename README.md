# 📊 Superstore Sales Analysis Project

A comprehensive end-to-end data analysis project using **Power BI**, **SQL**, **Python**, and **Excel** on a fictional Superstore dataset. This project provides key business insights on **sales performance**, **customer behavior**, **regional trends**, and **profitability**.

---

## 📁 Project Structure

Superstore-Sales-Analysis-Using-Power-BI-and-SQL/
├── LICENSE # License information (MIT)
├── README.md # Project overview and setup guide
├── Superstore Sales Insights.pbix # Power BI dashboard
├── superstore_final_dataset.csv # Final cleaned dataset
├── superstore_sales_cleaned.csv # Intermediate cleaned dataset
├── SuperstoreSalesAnalysis_JupyterNotebook.ipynb # Python notebook for cleaning & EDA
├── Superstore_sales_analysis_SQL_Insights.sql # SQL queries for analysis
└── SuperstoreData_cleaned_dump_Dataset.sql # SQL dump to create and populate DB

---

## 🚀 Tools & Technologies Used

| Tool           | Purpose                          |
|----------------|----------------------------------|
| **Power BI**   | Interactive dashboards & visuals |
| **SQL**        | Data querying & exploration      |
| **Python**     | Data cleaning & exploratory analysis |
| **Excel**      | Initial data storage and inspection |

---

## 📦 Dataset Overview

The dataset includes sales transactions with the following columns:

- **Order ID, Order Date, Ship Date**
- **Customer ID, Segment, Region, State, City**
- **Product Name, Category, Sub-Category**
- **Sales, Quantity, Discount, Profit, Shipping Mode**

---

## 📌 Objectives

- Analyze **sales trends** over time
- Compare **regional and state-wise performance**
- Study **product category** and **sub-category profitability**
- Segment customers based on **sales behavior**
- Explore **shipping mode preferences**

---

## 🛠 Setup Instructions

### ⚙️ SQL Setup

**Requirements:**

- MySQL / PostgreSQL / SQL Server
- SQL client (e.g., MySQL Workbench, pgAdmin, SSMS)

**Steps:**

1. Import database dump:
   ```sql
   SOURCE path/to/SuperstoreData_cleaned_dump_Dataset.sql;

-- Run queries from
Superstore_sales_analysis_SQL_Insights.sql

## Python (Jupyter Notebook)
Requirements:

Python 3.6+

Jupyter Notebook

Libraries: pandas, numpy, matplotlib, seaborn
# Install required packages
pip install pandas numpy matplotlib seaborn notebook

# Launch notebook
jupyter notebook
Open the notebook: SuperstoreSalesAnalysis_JupyterNotebook.ipynb
Run all cells to clean, analyze, and visualize the data.

📈 Power BI Dashboard
Requirements:

## Power BI Desktop installed

Usage:

Open the file: Superstore Sales Insights.pbix

Explore interactive charts

To update data: Go to Home → Refresh

## 📊 Excel Files
superstore_sales_cleaned.csv: Contains cleaned, pre-processed data.

superstore_final_dataset.csv: Final dataset used for analysis and dashboards.

Can be opened using MS Excel, Google Sheets, or LibreOffice.

## 🔍 Key Insights
✅ Sales Trends

Month-wise & year-wise sales growth

Peak seasons & months

✅ Region & State Performance

Top-performing and underperforming states

Regional comparison of revenue and profit

✅ Product Category Analysis

Most profitable categories & sub-categories

Loss-making items

✅ Customer Segmentation

Sales volume by customer segment

High-value customers

✅ Shipping Mode Analysis

Preferred shipping types

Profitability by shipping mode

## 🤝 Contributing
Contributions are welcome!
To contribute:

Fork the repository

Create a new branch

Make your changes

Create a pull request

## 📄 License
This project is licensed under the MIT License.
See the LICENSE file for more details.

<img width="1535" height="994" alt="Screenshot 2025-07-26 123109" src="https://github.com/user-attachments/assets/2e27846a-fec5-4c38-b7b3-11378f66617b" />

<img width="1508" height="953" alt="Screenshot 2025-07-26 123100" src="https://github.com/user-attachments/assets/c49edf88-7457-44f2-806c-b55ae2b0e827" />
<img width="1506" height="1089" alt="Screenshot 2025-07-26 123052" src="https://github.com/user-attachments/assets/9251cbe3-bc82-4390-b9a0-174a98e7be12" />


