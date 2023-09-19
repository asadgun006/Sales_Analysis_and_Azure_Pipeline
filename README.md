# Sales_Analysis_and_Azure_Pipeline

This is project that analyses sales data gathered from a source online.
It downloads 12 csv files, totalling >500000 rows, into a folder. The python code then reads those csvs and creates one big dataframe for processing, cleaning, and transformation
of the data. It deals with null values, numeric type conversions, datetime type conversions, as well as handling extraneous errors. 
Some visualization is also done on python using the matplotlib package for sales analysis by product, city, and month.
The script then uploads the data to an Azure Data Lake Gen2 container for SQL analysis within Azure Synapse Studio. The container is linked to Azure Synapse for querying and 
analysis.
