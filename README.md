# Transform Files Using a Serverless SQL Pool

This studying demonstrates how to use **serverless SQL pools** in **Azure Synapse Analytics** to transform data files. It covers provisioning an Azure Synapse Analytics workspace, querying and transforming data in different file formats (CSV), and encapsulating data transformation in stored procedures.

## Steps Involved

1. **Provision an Azure Synapse Analytics Workspace**  
   The first step is to provision an Azure Synapse Analytics workspace, which will serve as the environment for querying and transforming data files.

2. **Query Data in Files**  
   Using a serverless SQL pool, I queried data in different files (such as CSV, Parquet, and JSON). Serverless SQL pools allow for easy querying of data without the need for managing dedicated infrastructure.

3. **View Files in the Data Lake**  
   I accessed the files stored in the Azure Data Lake, which provided the raw data that will be transformed and queried.

4. **Use SQL to Query CSV Files**  
   I used SQL queries to access and retrieve data from CSV files stored in the Data Lake. This is crucial for structured data analysis.

5. **Transform Data Using CREATE EXTERNAL TABLE AS SELECT (CETAS) Statements**  
   To transform the data, I used **CREATE EXTERNAL TABLE AS SELECT (CETAS)** statements. This allowed me to create external tables and load the transformed data into these tables efficiently.

6. **Create an External Data Source and File Format**  
   An **external data source** was created to link the data lake to the serverless SQL pool. Additionally, I created a file format to define the structure of the files, ensuring that the data can be read and processed correctly.

7. **Create an External Table**  
   I created an **external table** to point to the data in the lake and provide the necessary schema. This enabled SQL queries to be run on the external data as if it were in a traditional relational database.

8. **Encapsulate Data Transformation in a Stored Procedure**  
   To streamline the transformation process, I encapsulated the data transformation logic within a **stored procedure**. This makes the transformation process reusable and easier to manage.

## Studying Workflow

- **Step 1:** Provision an Azure Synapse Analytics workspace.
- **Step 2:** Query the data stored in CSV files.
- **Step 3:** Transform the data using SQL queries and CETAS.
- **Step 4:** Create external tables and sources to work with the data.
- **Step 5:** Encapsulate transformation logic in stored procedures for ease of use.

## Tools and Technologies Used

- **Azure Synapse Analytics**  
- **Serverless SQL Pools**
- **Azure Data Lake**
- **SQL for Data Querying and Transformation**
- **Stored Procedures for Automation**

## How to Use

1. Clone this repository to your local environment or Azure.
2. Follow the instructions to provision an Azure Synapse Analytics workspace.
3. Use the SQL scripts provided to query and transform data in the Data Lake.
4. Modify and execute the stored procedure to apply the transformation logic.

## Cleanup

To delete all resources created for this studying, you can follow these steps:
1. Delete the external tables and stored procedures in the Synapse workspace.
2. Remove any data sources or file formats created in Synapse.
3. Clean up the Azure Data Lake and Synapse Analytics workspace.



Bu README, verdiğiniz adımları takip ederek GitHub üzerinde paylaşılabilir bir şekilde düzenlenmiştir.
