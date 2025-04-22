# ONLINE BANKING ANALYSIS

This project leverages Apache Spark to deliver scalable, high-performance analysis of bank statement data. It automates ETL pipelines to clean, aggregate, and analyze large volumes of financial transactions. Key features include fraud detection, customer segmentation, and real-time alerting with Spark Streaming. The solution is designed for extensibility, supporting integration with Hadoop, Hive, and cloud storage. Users can customize analysis pipelines via configuration files, and interactive dashboards provide actionable insights on spending patterns, risk, and compliance. Comprehensive documentation and ready-to-use notebooks make it easy for both technical and non-technical users to derive value from their financial data
                            
 So now let me explain the dataflow of how we have done is, first primarly we have ingested the data that is , we retrieved the data and then downloaded the datasets from kaggle and then we stored this datasets in cloud storage and imported from MYSQL to hive by sqoop this is how we have ingested the data , second after ingesting the data we have processed the large datasets in hive and then we have analyzed the data using pyspark in jupyter notebook by implementing several use cases.
                            
 ## TECHNOLOGIES USED:
 Spark SQL
 Spark
 HDFS
 Hive

 ## Project Structure

 banking_p2.ipynb: Jupyter notebook containing the core analysis and processing logic.
 credit card.csv: Dataset containing credit card transaction records.
 loan.csv: Dataset containing loan information.
 loan_dataset_commands.txt: Text file with Spark SQL commands related to the loan dataset.
 txn.csv: Dataset containing general transaction records.​

 ## Features

 1) Data Ingestion: Reads and parses CSV files containing transaction, credit card, and loan data.
 2) Data Cleaning: Handles missing values, duplicates, and inconsistent data entries.
 3) Data Transformation: Applies necessary transformations to prepare data for analysis.
 4) Analytical Queries: Performs various analytical operations to extract insights.
 5) Visualization: Generates plots and charts to visualize transaction patterns and trends.
 6) Fraud Detection: Identifies anomalous transactions that may indicate fraudulent activity.​
                          
 ## ROLES AND RESPONSIBLITIES:
 Collaborated in a team of 4 members using visual studios.
 Utilized the historical data from kaggle.com.
 Collected 3 datasets of online transactions, loan and customer credit card.
 Implemented Spark Session to load the data into Data Frames.
 Used standalone cluster mode in spark environment to run on Spark SQL queries.

## license
This project uses the following license: [MIT License](LICENSE)
