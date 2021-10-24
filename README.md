# Property-Analysis

# Steps followed
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

Find the ER diagram for OLTP Database
------------------------------------

![ER Diagram](https://user-images.githubusercontent.com/58709774/135180680-5b8cf072-e1b1-4f0f-91e0-6444a1784595.png)

Find the Data Ware House diagram for DWH Modelling
-------------------------------------------------
![DW_Dimensional modelling](https://user-images.githubusercontent.com/58709774/135181458-aa6f564a-a27d-446d-ac15-6470df8bf5d8.jpg)

