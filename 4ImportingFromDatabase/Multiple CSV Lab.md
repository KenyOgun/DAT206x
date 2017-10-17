> In this lab, you will you will import data to Microsoft Excel from a SQL database on Azure. Once you have imported the data, you will explore existing table relationships and create a new one yourself. You will also import data from CSV files which resides in a file folder. You will append this new data to the corresponding existing data that comes from the SQL Database. Finally, you will create a Date table in the data model to be used for data analysis.

## Scenario
VanArsdel is a company that manufactures and sells sporting goods. The company has offices in the United States (US) and several other countries. Its sales comprise of US sales and International sales. VanArsdel’s sales come from its owned manufactured products, as well as other manufacturers’ products. 

VanArsdel's US office stores the sales data on a SQL Database on Microsoft Azure. This is a relational database service in the cloud based on the Microsoft SQL Server engine, with built-in, mission-critical capabilities. The following image shows the database diagram for the tables of your interest:

VanArsdel International sales transactions are available as comma separated (CSV) files. They could be generated daily, either manually by someone, or automatically by an automated process. They are available in a dedicated folder. These CSV files have the same column structure as the sales table for the US sales that comes from the SQL Database. 

You want to perform analysis on VanArsdel's worldwide sales data for the year of 2015. You need to bring all these data into Excel before you can perform any analysis.