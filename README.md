# Tokyo-Olympics

## About Dataset
### Details
This contains the details of over 11,000 athletes, with 47 disciplines, along with 743 Teams taking part in the 2021(2020) Tokyo Olympics.
This dataset contains the details of the Athletes, Coaches, and Teams participating as well as the Entries by gender. It contains their names, countries represented, discipline, gender of competitors, names of the coaches.

### Source: 
Dataset was gotten from Kaggle.com

### Project Aim
This project leverages multiple Azure services, which include Azure Data Factory, Azure Storage, Azure Databricks, Azure Synapse Analytics, and Power BI. The primary objective of this project is to employ Azure Data Factory for the orchestration and automation of data integration and workflow procedures. This platform streamlines the extraction, transformation, and loading (ETL) of data from diverse sources like Kaggle, and Git Hub.

The data is gotten from Kaggle and loaded to Git Hub, Azure Data Factory is used to ingest/extract the data from Git Hub and the raw data is stored in Data Lake Gen 2. Once the data gathering phase is completed, Azure Databricks is harnessed to carry out data processing and transformation activities. Databricks offer the capability for scalable and distributed data processing, thereby facilitating efficient data manipulation, cleansing, and aggregation. Furthermore, it creates a collaborative workspace for data engineers and scientists to collaborate seamlessly. After the transformation process, the transformed data is moved to the Transformed folder in Data Lake Gen 2.
<img src="ETL Diagram.png">

Azure Synapse Analytics, a powerful analytics service, is used for data warehousing and advanced analytics. It enables the storage and analysis of large volumes of structured and unstructured data. With Synapse Analytics, the project can perform complex queries, run machine learning models, and derive valuable insights from Olympic data. Azure Synapse Analytics can also be used to extract, transform and load the data in Azure.

<img src="Azure Data Factory.PNG">

For the purpose of showcasing the analyzed data in a visually captivating and interactive fashion, Power BI is put into action. Power BI empowers the creation of user-friendly dashboards and reports that can be easily shared with and accessed by stakeholders. It offers the capability to monitor data in real-time, conduct on-the-fly analysis, and acquire valuable insights into the performance, trends, and patterns of the Olympic Games.


In summary, the Tokyo Olympic Data Engineering Project demonstrates the fusion of Azure services to construct a resilient and scalable data engineering solution. It highlights the potential of Azure Data Factory for data integration, Azure Databricks for data processing, Azure Synapse Analytics for advanced analytics, and Power BI for data presentation. Through the utilization of these services, the project facilitates effective data handling, analysis, and visualization, thereby elevating the decision-making process and delivering invaluable insights into the Tokyo Olympic Games.


