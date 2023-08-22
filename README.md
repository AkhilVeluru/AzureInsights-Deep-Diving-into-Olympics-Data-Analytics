# TokyoOlympics_Data_Analytics
DataEngineering_Deep Dive: Analyzing_OlympicswithAzure
Here's a simple step-by-step outline for your pipeline diagram:

Data Sources: Used a GitHub repository with CSV files 

Azure Data Factory: Connected the data sources to Azure Data Factory, ingested using the HTTP API.

Azure Data Lake Gen2 (for data storage): Connected Azure Data Factory to an Azure Data Lake Gen2 icon. Label it clearly to indicate that this is the storage phase.

Azure DataBricks: connected from Azure Data Lake Gen2 to Azure DataBricks, symbolizing the data transformation process with PySpark

Azure Data Lake Gen2: After Azure DataBricks, connect it back to another representation of Azure Data Lake Gen2, suggesting transformed data storage.

Azure Synapse: From the Data Lake, make a connection to Azure Synapse

Analytics Tools: Lastly, fan out connections from Azure Synapse to icons representing Tableau, Power BI, and Looker, showing downstream analytics.
