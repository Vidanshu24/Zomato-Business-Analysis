# 🍽️ Zomato Business Performance Analysis

## Project Overview

This project focuses on analyzing **Zomato restaurant data** to understand business performance across locations, pricing categories, cuisines, and customer engagement metrics such as ratings and votes.

The main goal of this project is to help businesses and stakeholders answer questions like:

- Which locations generate the highest revenue?
- Which cuisines perform the best?
- How do price categories impact revenue?
- Do higher ratings always lead to higher customer engagement?

The project is built end-to-end using **Python, SQL, and Power BI**, starting from raw data cleaning to a business-ready interactive dashboard.

---

## What is This Analysis About?

Zomato operates as a restaurant discovery and food delivery platform.  
This analysis simulates a **real business analytics use case**, where restaurant-level data is analyzed to:

- Measure overall business performance
- Compare restaurants based on price range and ratings
- Identify top-performing areas and cuisines
- Understand customer behavior through votes and booking trends

---

## Tools Used

- **Python (Pandas, NumPy)** – Data cleaning and preprocessing  
- **PostgreSQL(SQL)** – Analytical queries and aggregations  
- **Power BI** – Dashboard creation and visualization  
- **CSV Dataset** – Cleaned data used for analysis  

---

## Project Workflow (Step by Step)

### 1️⃣ Data Cleaning (Python)

The raw Zomato dataset contained missing values, inconsistent formats, and unnecessary columns.  
The following data cleaning steps were performed using Python (Pandas):

- Removed duplicate restaurant records  
- Handled missing and null values  
- Standardized rating and price category columns  
- Converted data types for numerical analysis  
- Prepared a clean dataset for SQL analysis and Power BI  

📄 **Output File:** `Cleaned_data.csv`  
📄 **Python File:** `Zomato cleaning analysis python.ipynb`

---

### 2️⃣ SQL Analysis

After cleaning the data, SQL was used to perform business-focused analysis such as:

- Categorizing restaurants based on spending levels (High / Medium / Low)  
- City-wise restaurant count and revenue analysis  
- Cuisine-level performance analysis  
- Rating bucket analysis (Excellent / Good / Average)  
- Aggregated metrics for dashboard KPIs  

📄 **SQL File:** `Zomato query analysis.sql`

---

### 3️⃣ Power BI Dashboard

A Power BI dashboard was created to visualize key insights in an easy-to-understand and interactive format.

The dashboard includes:

- Key performance indicators (KPIs)
- Revenue distribution across price categories
- Top 5 locations by sales
- Most popular cuisines
- Relationship between ratings and votes
- Online delivery distribution
- Table booking analysis

📄 **Dashboard File:** Power BI (.pbix)

> GitHub cannot preview `.pbix` files.  
> The dashboard can be downloaded and opened using **Power BI Desktop**.

---

## Dashboard Screenshot

🔹 **Zomato Business Performance Dashboard Overview**

  <img width="669" height="370" alt="Zomato Business Performance Dashboard" src="https://github.com/user-attachments/assets/fdefaafd-6889-449f-9521-ad7f37b42457" />



---

## Key Insights

- High price category restaurants contribute the highest revenue share  
- Italian cuisine generates the maximum sales  
- BTM and Koramangala are the top-performing locations  
- Higher ratings do not always guarantee higher customer votes  
- Table booking and non-booking restaurants are almost evenly distributed  

---

## Business Value

This project helps businesses and analysts to:

- Optimize pricing strategies based on revenue contribution  
- Focus expansion and marketing efforts on high-performing locations  
- Identify popular cuisines for better menu planning  
- Understand customer engagement beyond just ratings  
- Support data-driven decision-making  

---

## Future Improvements

- Time-based trend analysis (monthly / yearly sales)
- Profitability analysis instead of revenue only
- Customer segmentation using advanced techniques (RFM / clustering)
- Predictive analysis for ratings and sales performance

---

## Project Summary

This project demonstrates a **complete data analytics workflow**, starting from raw data cleaning using Python, analytical querying using SQL, and ending with actionable business insights through an interactive Power BI dashboard.

---

## Contact

Created by **Vidanshu Rautela**

Feel free to connect with me:  
🔗 GitHub: https://github.com/Vidanshu24  

⭐ If you found this project helpful, please consider starring the repository!


