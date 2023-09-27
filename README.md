# Sales_Analysis_and_Azure_Pipeline

This is a project that analyzes yearly sales data gathered from an online source. The link to the online source can be found at the bottom.
It downloads 12 csv files, totalling >500000 rows, into a folder. The python code then reads those csvs and creates one big dataframe for processing, cleaning, and transformation of the data. It deals with null values, numeric type conversions, datetime type conversions, as well as handling extraneous errors. 
Some visualization is also done on python using the matplotlib package for sales analysis by product, city, and month.
The script then uploads the data to an Azure Data Lake Gen2 container for SQL analysis within Azure Synapse Studio. The container is linked to Azure Synapse for querying and 
analysis through a SQL pool created within the Synapse Studio.

A Power BI visualization also provides a visual aspect and analysis on the transformed data by grouping the data by multiple measures and dimensions. The title of each 
visualization describes the analysis performed.

Source:
https://github.com/KeithGalli/Pandas-Data-Science-Tasks/tree/master/SalesAnalysis/Sales_Data
