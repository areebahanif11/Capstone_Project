# 📊 AdventureWorks Sales Analytics Dashboard  
### Transforming raw sales data into actionable business insights using **Power BI**

---

## 🗂️ Table of Contents
- [Project Overview](#project-overview)  
- [Problem Statement](#problem-statement)  
- [Dataset Description](#dataset-description)  
- [Data Model](#data-model)  
- [Project Workflow](#project-workflow)  
- [Dashboard Preview](#dashboard-preview)  
- [Key Insights](#key-insights)  
- [Business Recommendations](#business-recommendations)  
- [Tools Used](#tools-used)  
- [How to Run](#how-to-run)  
- [Contact](#contact)

---

## 📘 Project Overview
This capstone project analyzes the **AdventureWorks** dataset to uncover important business trends, customer behavior patterns, and product performance insights. The aim is to support data-driven decision-making through a clean, interactive, and visually compelling **Power BI dashboard**.

The project covers:
- Customer sales trends  
- Product performance  
- Regional sales behavior  
- Profitability metrics  
- Customer demographics  

---

## ❗ Problem Statement
AdventureWorks wants to strengthen its sales strategy, improve profitability, and understand customer behavior. Key business questions include:

- Which products and categories are driving the most revenue?  
- Which customer groups have the highest purchasing power?  
- Which regions and territories perform the best?  
- What trends can guide future marketing and inventory decisions?  

This dashboard provides insights to help the company improve decision-making and identify growth opportunities.

---

## 📂 Dataset Description
The project uses a **star schema** containing the following tables:

### **DimCustomer**
Information about customers.  
**Key columns:** CustomerKey, FirstName, Gender, Education, Occupation, YearlyIncome, GeographyKey

### **DimDate**
Calendar information for time-series analysis.  
**Key columns:** DateKey, FullDate, Day, Month, Quarter, Year

### **DimProduct**
Product-level details.  
**Key columns:** ProductKey, ProductName, Category, Subcategory, StandardCost, ListPrice

### **DimGeography**
Geographical details for customer location analysis.  
**Key columns:** GeographyKey, City, StateProvince, CountryRegion

### **DimSalesTerritory**
Sales territory grouping.  
**Key columns:** SalesTerritoryKey, Region, Country, Group

### **FactInternetSales**
Main transaction table with sales metrics.  
**Key columns:** SalesOrderNumber, ProductKey, CustomerKey, OrderDateKey, SalesAmount, OrderQuantity, UnitPrice

---

## 🔧 Project Workflow
1. **Data Cleaning & ETL** in Power Query  
2. **Data Modeling** using relationships between dimension and fact tables  
3. **DAX Calculations** for KPIs and metrics  
4. **Dashboard Designing** with interactive visuals  
5. **Insight Generation** through sales, customer, and product analysis  

---

## 📊 Dashboard Preview
> <img width="395" alt="AdventureWorks Dashboard" src="https://github.com/user-attachments/assets/f13baf8c-b5a2-42ce-b0ce-47f2a3ce1759" />  

---

## 🔍 Key Insights
- **18K total customers**, evenly split between male and female.  
- **Total Profit:** **12.8M**, indicating strong revenue performance.  
- Customers with **Professional occupation** contribute the highest sales.  
- **Mountain-200 Black 46** is the **best-selling product**.  
- Customers with a **Bachelor’s education** make the most purchases.  
- Average customer yearly income is **$57.31K**.  
- **United States** leads in total sales, followed by Australia.

---

## 💡 Business Recommendations
- Focus marketing campaigns on **professionals** and **bachelor-degree customers** to boost revenue.  
- Increase stock and promotion of **top-selling products** like Mountain-200.  
- Strengthen operations in **high-performing regions** such as the USA and Australia.  
- Offer targeted discounts or bundles for low-performing products.  
- Build customer loyalty programs to encourage repeat purchases.

---

## 🛠️ Tools Used
- **Power BI**  
- **Power Query**  
- **DAX**  
- **Excel**   
 
