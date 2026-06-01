# Business Sales Performance Analytics Dashboard

## Project Overview

This project analyzes retail sales data to uncover business insights related to revenue, customer activity, product performance, and geographical sales distribution. Using Power BI, I developed an interactive dashboard that enables stakeholders to monitor key business metrics and make data-driven decisions.

The project demonstrates the complete analytics workflow, including data cleaning, transformation, KPI development, visualization, and business insight generation.

---

## Business Objective

The primary objective of this project is to help businesses answer important questions such as:

* Which products generate the highest revenue?
* How do sales trends change over time?
* Which countries contribute the most to overall revenue?
* What opportunities exist for business growth and expansion?

---

## Dataset

**Dataset:** Online Retail Dataset

The dataset contains transactional sales records, including:

* Invoice Number
* Product Description
* Quantity
* Invoice Date
* Unit Price
* Customer ID
* Country

---

## Tools & Technologies

* Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Data Cleaning & Transformation
* Data Visualization

---

## Data Cleaning & Preparation

The following data cleaning steps were performed using Power Query:

* Removed duplicate records
* Filtered Quantity > 0
* Filtered UnitPrice > 0
* Removed cancelled transactions (InvoiceNo starting with "C")
* Removed accounting adjustment entries such as "Adjust bad debt"
* Converted InvoiceDate to Date format
* Handled missing Customer IDs
* Validated data quality before analysis

---

## KPIs Created

The following business metrics were calculated using DAX:

### Total Revenue

Measures the total sales revenue generated.

### Total Orders

Counts the total number of unique orders.

### Total Customers

Counts unique customers who made purchases.

### Average Order Value

Calculates average revenue generated per order.

### Total Products Sold

Calculates the total quantity of products sold.

### Countries Served

Counts the number of countries where sales occurred.

---

## Dashboard Features

### Executive KPI Overview

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value
* Total Products Sold
* Countries Served

### Sales Trend Analysis

* Revenue Trend Over Time
* Monthly Order Trend

### Product Analysis

* Top Products by Revenue
* Product Performance by Quantity Sold

### Geographic Analysis

* Revenue by Country
* Top 10 Countries by Revenue
* Interactive Sales Map

### Interactive Filters

* Country
* Year
* Month

---

## Key Insights

* Generated approximately 10.63M in total revenue.
* Processed over 20.7K customer orders.
* Served 4.34K customers across 38 countries.
* The United Kingdom contributed the largest share of total revenue.
* A small number of products generated a significant portion of sales.
* Strong seasonal sales patterns were observed during peak periods.

---

## Business Recommendations

* Increase marketing efforts in high-performing international markets.
* Maintain inventory levels for top-selling products.
* Develop customer retention and loyalty strategies.
* Plan inventory and promotions around seasonal demand trends.

---

## Dashboard Preview

https://github.com/divya524/FUTURE_DS_01/blob/main/Business%20Sales%20Performance%20Analytics_photo.png
---

## Project Outcome

This project demonstrates how business data can be transformed into actionable insights through effective data cleaning, KPI development, and visualization. The dashboard provides stakeholders with a comprehensive view of business performance and supports informed decision-making.

---

## Author

**Divyasri Vanapalli**

Aspiring Data Analyst | Power BI | SQL | Python | Data Visualization
