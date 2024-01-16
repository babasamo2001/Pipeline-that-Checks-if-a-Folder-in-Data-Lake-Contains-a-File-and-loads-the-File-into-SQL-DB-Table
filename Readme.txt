
 
  Project Title: ADF Data Factory Pipeline that Continously Checks if a Folder in Azure Data Lake Contains a Specific File and then loads the File into SQL Database Table if file Present

A.  Source Folder Details:
	 Number of Files: 2
	 File format: CSV

B.  Target Location Details:
	 Azure SQL Database table

	

C.  Business requirements:
    Client (user) needed to continuosly check if a data lake folder contains a specific file and then load the file to Azure SQL database if file is found
	

D.  Solution Steps: 
   	 -create RBAC role assignment for the storage account container 
   	 -create link services, datasets, ETL pipeline and activities
   	 -check if source folder contains the specific file and then copy the file to the Azure SQL Database table if file is present
   	 -check the Azure SQL database table for the copied data to confirm the pipeline runs successfully


E.  Azure Services used: 
   	 -Azure Data Lake
   	 -Azure Data Factory
   	 -Azure SQL Database
