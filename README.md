# Data Engineering Deep Dive: Analyzing Olympics with Azure
DataEngineering_Deep Dive: Analyzing_OlympicswithAzure
Here's a simple step-by-step outline for your pipeline diagram:

Data Sources: Used a GitHub repository with CSV files 

Azure Data Factory: Connected the data sources to Azure Data Factory, ingested using the HTTP API.

Azure Data Lake Gen2 (for data storage): Connected Azure Data Factory to an Azure Data Lake Gen2 for storage.

Azure DataBricks: Connected from Azure Data Lake Gen2 to Azure DataBricks for data transformation process with PySpark.

Azure Data Lake Gen2: After Azure DataBricks, load the transformed data back to the Data Lake Gen2. 

Azure Synapse: From the Data Lake, make a connection to Azure Synapse and used SQL scripting there to receive and make other analytics. 

Analytics Tools: Lastly, this is not within the scope of data engineering, but the ground work has been laid out to do the dashboarding with Tableau, PowerBI, and Looker.

Thanks for checking out the project. Let's stay connected.
