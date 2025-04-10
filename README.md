# DP-203-Lab2
### Query Files Using a Serverless SQL Pool
Azure Synapse Analytics provides serverless SQL pools that enable you to decouple the SQL query engine from the data storage and run queries against data files in common file formats such as delimited text and Parquet.

### Azure Synapse Analytics - Data Querying and Visualization
This project involves querying, analyzing, and visualizing data using Azure Synapse Analytics. Various data file formats (CSV, JSON, Parquet) were queried using SQL, and meaningful insights were derived from the data. Additionally, the results were visualized to present the data analysis more effectively.

### Contents

- **Azure Synapse Analytics Workspace Setup:**  
  An Azure Synapse Analytics workspace was created in the Azure portal, and the Azure Data Lake Storage connection was established.

- **Data Querying and File Types:**
    - **CSV Files:** SQL queries were executed on CSV files to retrieve the first 100 rows of data.
    - **JSON Files:** SQL queries were run on JSON files to extract values from the JSON data.
    - **Parquet Files:** SQL queries were executed on Parquet files to analyze the data.

- **Data Visualization:**
    - SQL query results were visualized using the integrated charting tools in Synapse Studio.
    - Line and column charts were used to visualize the annual revenue trend.

- **Data Sources and External Databases:**
    - External data sources were created using PolyBase to reference data stored in the data lake for more complex queries.
    - **External Data Source:** An external data source was set up to allow SQL querying of data from the data lake.
    - **External Table:** External tables were created to query data from CSV files.

- **Resource Cleanup:**
    - After completing the project, Azure Synapse Analytics resources were cleaned up to avoid unnecessary costs.

---

### Additional Enhancements

1. **Data Cleansing and Preprocessing:**
    - "Before analysis, missing or erroneous data was identified and cleaned."
    - "Data transformation tasks were carried out on JSON and CSV files, ensuring the data was suitable for analysis."

2. **Performance Optimization:**
    - "SQL queries were optimized for faster data retrieval by using appropriate indexes and filtering techniques."
    - This section can explain steps taken to improve the performance of SQL queries, such as indexing or query optimization.

3. **Data Integration:**
    - "Data from different sources (CSV, JSON, Parquet) was integrated into Azure Synapse Analytics, providing a unified environment for analysis."
    - This could describe the process of merging or integrating data from various file types.

4. **Advanced SQL Queries:**
    - "Complex SQL queries were executed, such as group-based analyses, conditional queries, and joins."
    - You can provide examples of advanced SQL queries used in the project.

5. **Data Sources and Security:**
    - "Security configurations were implemented to manage access control and authentication for data stored in Azure Data Lake."
    - This could include information on setting up roles, permissions, or data access security.

6. **Data Lake and Data Warehouse Integration:**
    - "Data loaded into the data lake was queried through SQL pools, and prepared for potential integration into the Azure Synapse Analytics data warehouse."
    - You could explain the difference between a data lake and a data warehouse and how they were integrated for analysis.

7. **Visualization Tools and Techniques:**
    - "Different chart types, such as line and column charts, were used for specific insights, showcasing trends and distributions of the data."
    - This can explain what types of charts or visualization tools were best suited for different kinds of analysis.

8. **Advanced Analysis and Use Cases:**
    - "Analysis was performed based on specific use cases, and tailored reports were generated to address these use cases."
    - This section could focus on how the analysis can be used in real-world scenarios.

---

### Requirements
- **Azure Subscription** (Administrator-level access)
- **Azure Synapse Analytics Workspace**
- **Azure Data Lake Storage Gen2**
- **SQL Knowledge**

### Technologies Used
- **Azure Synapse Analytics**
- **SQL (Structured Query Language)**
- **Azure Data Lake Storage Gen2**
- **PolyBase**
- **Synapse Studio**

### Steps
1. Create an Azure Synapse Analytics workspace.
2. Upload data files to Azure Data Lake.
3. Query the data using SQL in Synapse Studio.
4. Visualize the query results.
5. Clean up resources once the project is completed.

### Outcomes
This project demonstrates how data querying and visualization processes can be simplified using Azure Synapse Analytics, providing an efficient way to analyze data and derive insights.

##screenshots

![1](https://github.com/user-attachments/assets/fd119326-6713-4d43-af95-21f0d700dd63)

![2](https://github.com/user-attachments/assets/ad377b98-3152-4f68-ac36-93a27cbba6b3)

![3](https://github.com/user-attachments/assets/c5723c82-d3fb-4ac1-8812-28b3024df69e)

![4](https://github.com/user-attachments/assets/bd5549d2-ee59-4b92-8773-bbc4383ac9a2)

![5](https://github.com/user-attachments/assets/3779a751-8bc5-40a3-a22f-ffb6b5f03cfa)

![7](https://github.com/user-attachments/assets/ec9c2365-324d-4852-bc50-491775700a2f)

![6](https://github.com/user-attachments/assets/557fe722-64ef-476b-929d-6d17c3cf5c08)
