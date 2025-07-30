# Business Intelligence Specialist
**Technical Skill**: Microsoft Excel, Python, ELK, Google Looker, SQL, Tableau, PowerBI, Google Cloud Platform, MongoDB, BigQuery

**Soft Skill**: Team Work, Presentation Skill, Negotiation, Technical Analyst

## Education
- **D4 Informatics Engineering** : Politeknik Negeri Malang

## Professional Experience
### Data and Business Intelligence at PCS Payment 
<font color="grey"> November 2023 - Now</font>

- Collaborated with stakeholders across IT, Sales, and Operations to gather and define data requirements, ensuring alignment with business needs
- Designed and maintained 20+ real-time operational dashboards to track KPIs, transactional trends, and system issues—enhancing decision-making speed and reducing reporting turnaround by 30%.
- Executed complex data transformations, including aggregation and cleansing, to create comprehensive datasets for advanced analytical projects.
- Built Python automation to detect transaction anomalies in Elasticsearch—including timeouts, transform failures, and ticket issues—triggering real-time alerts via Google Chat and reducing manual checks by 40%.
- Established a reliable ELT system to transfer transactional and profile data from MongoDB and MySQL into Elasticsearch, providing operation teams with up-to-date data

### Freelance Python Tutor at Superprof.com
<font color="grey"> October 2023 - Jun 2025</font>

- Delivered instruction in Python programming and Machine Learning, covering foundational concepts including supervised/unsupervised learning and model evaluation.
- Guided learners in data preparation, including cleaning, handling missing values, and performing Exploratory Data Analysis (EDA) for model readiness.
- Provided hands-on training in Natural Language Processing (NLP) using IndoBERT and time series forecasting using N-BEATS, focusing on model architecture, configuration, and performance tuning.


### Data Engineering at IYKRA  
<font color="grey"> July 2023 - August 2023</font>

- Design an architecture pipeline (batch processing) to integrate data into a data warehouse using
Apache Airflow, Apache Spark, and Apache Kafka.
- Perform the ETL (Extract, Transform, Load) process for data processing and loading stages.
- Develop a dashboard visualization specifically for Fault Detection in Online Transactions using
Looker Studio and BigQuery.

### IT Support Intern at Opero Hotel Southkey  
<font color="grey"> January 2023 - February 2023</font>

- Responsible for ensuring the seamless operation of Guest Internet, Property Management Systems,
Point of Sales, Opera, Telephony systems, and other software providers.
- Responds courteously and effectively to visitor's and system user's questions and difficulties.
- Generate weekly and daily reports to track telephone and printer usage across various departments

## Project
### Automatic Notifications for Monitoring Timed-Out Transactions
**Tools: Python, Google Chat Webhook, ELK API**
This describes an automated notification system built with Python. It connects to ELK Stack (Elasticsearch, Logstash, Kibana) via its API to monitor transaction data for any timed-out transactions. Once a timeout is detected, a summary of that transaction is automatically sent to a Google Chat webhook.

### Fraud Detection for Online Transaction
**Tools: Apache Airflow, DBT, Google Looker, Python, Docker, Spark, Google Storage, Google BigQuery**

The project is about build a data pipeline for its large volume of online transaction data. This pipeline will assess data quality (acknowledging existing limitations like inaccuracies or missing info) and enable fraud detection to protect the business. The ultimate goal is to ensure the data is reliable for both analysis and reporting of online payment fraud.

![architecture](assets/img//architecture.png)

[Presentation](https://drive.google.com/file/d/1Du-qdJ4TgBvl1wrcb0-DgKF5pO9ma3Kw/view) | [Github](https://github.com/widiarsaf/final-project-fraud-transaction-pipeline) |   [Dashboard](https://lookerstudio.google.com/reporting/eef88548-5ad4-4b22-82c4-37b7bb29ce0e) 

### Simple Orchestrate ETL with Apache Airflow
This project demonstrates a simple ETL pipeline orchestrated with Apache Airflow. Data is extracted from a source, transformed using Pandas, and then loaded into Google Cloud Storage and BigQuery. Finally, Looker Studio is used for data visualization from BigQuery.

![architecture](assets/img/architecture-etl.png)

[Github](https://github.com/widiarsaf/simple-orchestrate-etl-airflow-globalSuperstore/tree/master)

### Customer Segmentation and Churn Analysis
The architecture for ETL begins with extracting data from the data source, which is then transformed using pandas, with orchestration processes managed using Airflow. After the transformation, the data will be ingested into Google Storage, and subsequently sent to Google BigQuery. After that, a visualization process is carried out using Looker Studio.

![customer-segmentation](assets/img/customer-segmentation.png)

