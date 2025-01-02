# AdventureWorks Data Analysis
## The Adventutre Works report provides analysis about dataset, about customers sales data, product sales data total quantities sold, total profit, total sales, total customers and geographical information.The aim of this analysis is to uncover trends and decision making about the customers.

## Introduction:

Adventure works is a company that sells outdoor gear such as bikes, hiking equiment and camping gear. In this report we will deep dive into the dataset provides and find insights. By looking trends, sales data and customers data we will find insights for effective decision making. 

## Problem Statement:

Task is to Think about the challenges or questions the hypothetical company might be facing based on the provided dataset. What issues could they potentially address, or opportunities could they seize through data analysis?

## Dataset used:
- <a href="https://github.com/areebahanif11/Capstone_Project/blob/main/AdventureWorks.xlsx">Dataset</a>


## Data Overview:

1.	DimCustomer:
-	Contains customer-related information.
- Key columns: CustomerKey, FirstName, LastName, EmailAddress, Phone, BirthDate, Gender, AddressLine, GeographyKey.
2.	DimDate:
-	Contains date-related information.
-	Key columns: DateKey, FullDate, Day, Month, Quarter, Year.
3.	DimProduct:
-	Contains product-related information.
-	Key columns: ProductKey, ProductName, ProductCategory, ProductSubcategory, StandardCost, ListPrice.
4.	DimGeography:
-	Contains geographical information.
-	Key columns: GeographyKey, City, StateProvince, CountryRegion, PostalCode.
5.	DimSalesTerritory:
-	Contains sales territory information.
-	Key columns: SalesTerritoryKey, SalesTerritoryRegion, SalesTerritoryCountry, SalesTerritoryGroup.
6.	FactInternetSales:
-	Contains internet sales transaction data.
-	Key columns: SalesOrderNumber, CustomerKey, OrderDateKey, ProductKey, SalesTerritoryKey, SalesAmount, OrderQuantity, UnitPrice.

## Dashboard:
<img width="395" alt="AdventureWorks Dashboard" src="https://github.com/user-attachments/assets/f13baf8c-b5a2-42ce-b0ce-47f2a3ce1759" />
