# Property-Analysis

# General Steps 
1.Determine the business process (Analysing the requirements)


2.Deteine the grain of the project (Identify entity and relations between them)(What does row in fact table represent)
•	Always take most atomic level. For eg: Take day level data


3.Design a Fact table (Analyse Dimensions and measures and add attributes to Entity and design a DWH diagram)

•	Determine the dimensions (Who, what, where, when)

•	Determine the measures. (How business measures success, Best measures are additive)

•	Use Surrogate Keys

•	Determine the attributes (Very descriptive)

•	Determine data types


4.Create an OLTP table using SQL with Business keys or Primary Keys ( Use an ERD to identify the model)


5.Populate the table using ETL to a DWH


6.Get Valuable insights from your data in DWH using Power BI visualisations

PROJECT STEP BY STEP
--------------------
Project Key
----------

One stop online platform for property investors, managers, owners, tenants and service providers. It will analyze the data sets across different platforms and provide the end user with a complete analysis about the Geographical location Property market 
Tasks 

•	Clean, standardise data

•	Build a data warehouse with fact & dimension tables.

•	Build SSRS and Power BI reports

Results

•	Choose city and suburb and distance, display transport/school/property value/rental value/crime rate within a particular distance/radius eg. 1, 5 km from the input suburb.

•	Generate financial report eg. Rental incomes vs Expenses for landlords.

•	Display forecasted property value within 1, 5 and 10-year value.

Sprints
-------
Sprint 1: Standardise Dataset
-----------------------------
Given raw dataset, standardize datasets for public transport in Australia
Given raw dataset, standardize datasets for local school.
Given raw dataset, standardize dataset for Rental Median per suburb, city
Given raw dataset, standardize the dataset for Median Property Value per suburb
Given raw dataset, standardize the dataset for Crime rate of each suburb and city.

Sprint 2: Design Datawarehouse & Build SSIS package
---------------------------------------------------

Using Suburb and City Dataset, design a Dim table - DimGeography with State / City / District / Postcode / Suburb / Lon / Lat.

DimTransport: Load public transport data to StgTransport table

DimState with DWStateKey, StateCode and StateName

Design DimAuLocalSchool tables for Aus local school

Design FactCrimeByYear

Design FactSuburbRentalMedian

Design Fact table – FactMedianPropertyValueByYear

Design Fact table FactSuburbPopulation

Sprint 3: Build SSRS Report
---------------------------

Given suburb and city, display median rental value, median yearly income, and value changes of the property within 1 km radius.

Given suburb and city, display local public transport within 1km radius - update data sets.

Given suburb and city, display local schools within 1km radius.

Given suburb and city, display crime rate within 1 km radius.

Given suburb and city, display property value of the area in Column chart and line chart of 1 year, 5 years and 10 years value

Given suburb and city, display median rental value, median yearly income, and value changes of the property within 1 km radius.


Sprint 4: Build Power BI Dashboard from the designed Datawarehouse
-------------------------------------------------------------------

Given suburb and city, display median rental value, median yearly income, and value changes of the property within 1 km radius

Given suburb and city, display local public transport within 1km radius

Given suburb and city, display local schools within 1km radius

Given suburb and city, display crime rate within 1 km radius

Given suburb and city, display property value of the area within 1km radius in Column chart and line chart of 1 year, 5 years and 10 years value

Build Monthly Property financial report on Power BI- rental income vs expense.

Line chart of Property Value Changes in the suburb of 1,5 and 10 years on DW.

Build Pie chart of all expense categories on DW.

Build Crime rate Map around the given input property on Power BI.

Build Custom map display Public transport within 1km radius of given input property



Find the Data Ware House diagram for DWH Modelling
-------------------------------------------------
![DW_Dimensional modelling](https://user-images.githubusercontent.com/58709774/135181458-aa6f564a-a27d-446d-ac15-6470df8bf5d8.jpg)

