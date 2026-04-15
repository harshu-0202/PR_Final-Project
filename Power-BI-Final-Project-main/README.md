# 📊 Power BI Sales & Returns Analytics Dashboard

## 📌 Project Overview

This project showcases an end-to-end Power BI dashboard built to analyze
sales performance, customer behavior, product insights, and return
trends. The dataset follows a star schema model, enabling efficient data
analysis and interactive reporting.

## 🗂️ Dataset Description

The project uses multiple structured 
tabels:

### 🔹 Dimension Tables

-   Customer_Dim -- Customer details (Name, Segment, Region)
-   Product_Dim -- Product information (Category, Subcategory, Price)
-   Date_Dim -- Date hierarchy (Year, Month, Quarter)
-   Region_Dim -- Regional data and managers

### 🔹 Fact Tables

-   Sales_Fact -- Transactional sales data (Units Sold, Total Amount)
-   Returns_Fact -- Product return records (Reason, Date)

## 🏗️ Data Model

-   Implemented a Star Schema
-   Fact tables connected with dimension tables via keys:
    -   CustomerID
    -   ProductID
    -   DateID
    -   Region

## 📈 Key Features of Dashboard

### 📊 Sales Analysis

-   Total Revenue & Units Sold
-   Sales trends over time (Year/Month/Quarter)
-   Region-wise sales performance

### 🧑‍🤝‍🧑 Customer Insights

-   Customer segmentation
-   Region-based customer distribution

### 📦 Product Performance

-   Top-performing products
-   Category & subcategory analysis

### 🔁 Returns Analysis

-   Return trends over time
-   Common return reasons
-   Impact of returns on overall sales

## 🛠️ Tools & Technologies

-   Power BI Desktop (.pbix)
-   DAX
-   Excel

## 📸 Dashboard Preview
![Dashboard](Dashboard.png)
![Photo](Photo.png)

## 🚀 How to Use

1.  Download the .pbix file
2.  Open in Power BI Desktop
3.  Explore the dashboard

