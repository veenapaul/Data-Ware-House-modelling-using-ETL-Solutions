# Property-Analysis

Steps followed
1.Determine the business process (Analysing the requirements)
2.Determine the grain of the project (Identify entity and relations between them)(What does row in fact table represent)
•	Always take most atomic level. For eg: Take day level data
3.Design a Fact table (Analyse Dimensions and measures and add attributes to Entity and design a DWH diagram)
•	Determine the dimensions (Who, what, where, when)
•	Determine the measures. (How business measures success, Best measures are additive)
•	Use Surrogate Keys
•	Determine the attributes (Very descriptive)
•	Determine data types
5.Create an OLTP table using SQL with Business keys or Primary Keys ( Use an ERD to identify the model)
6.Populate the table using ETL to a DWH
7.Get Valuable insights from your data in DWH using Power BI visualisations

