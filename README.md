# UberDataAnalytics


## Data Pipeline Using Apache Airflow, Glue, S3, Redshift and PowerBI


## Data Archiecture 

<img width="718" alt="image" src="https://github.com/salmah52/UberDataAnalytics/assets/44398948/88879e63-bc4e-4843-bcef-641ef84dfb49">


## Introduction

In this Uber data analysis case study, I explore the process of building and automating a Python ETL pipeline using AWS Glue. This case study is inspired by UberDataAnalytics and demonstrates how to extract, transform, and load Uber ride data from an AWS S3 bucket into an Amazon Redshift data warehouse. The project's key objective is to connect Power BI for data visualization and insights. I rely heavily on AWS services to create a robust data engineering and analytics solution.

## Technologies Used
- AWS Glue
- AWS S3
- Amazon Redshift
- Power BI
- Apache Airflow
- Amazon Athena

  
## Workflow
1. Data Extraction: I employ AWS Glue to extract Uber ride data from an AWS S3 bucket. AWS Glue's Crawler is used to infer data schemas and catalog the data efficiently.

2. Data Transformation: Amazon Athena is utilized to create SQL queries, allowing data transformation and the extraction of insights from the cataloged data.

3. Data Loading: AWS Glue is used once more to load the processed data into the Amazon Redshift data warehouse, a powerful solution for storing and managing large datasets.

4. Workflow Orchestration: Apache Airflow is responsible for orchestrating and automating the entire ETL process, ensuring its reliability and efficiency.

5. Data Visualization: Power BI is connected to the Amazon Redshift cluster, enabling insightful data visualization and reporting.



## Conclusion
In conclusion, this Uber data analysis case study provides a comprehensive solution for managing and analyzing Uber ride data. By leveraging AWS services, including AWS Glue, Amazon Redshift, and Apache Airflow, I have created an efficient and scalable ETL pipeline. The integration of Power BI allows for data-driven insights and reporting.

I hope this case study serves as a valuable resource for data analysts and engineers working with Uber ride data and AWS services. Feel free to contribute, modify, or adapt this case study to align with your specific use cases and requirements.

Power BI Visualization
You can access the Power BI visualization of the Uber ride data obtained in this case study at the following link: Link to Power BI Visualization


Happy Enginering 







Regenerate


