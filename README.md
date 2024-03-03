<h1>Batch Data Pipeline Project</h1>

<h2>Description</h2>
The project involved crafting a robust data pipeline using Apache Airflow and various AWS services, facilitating the extraction, transformation, and loading of raw stock market data from on-premise CSV snapshots into a PostgreSQL database hosted on AWS.
<br />


<h2>Language and Libraries Used</h2>

- <b>Python</b>
- <b>Pandas</b> 
- <b>SQL</b>
- <b>Bash Scripting</b>


<h2>Environments/Cloud Services Used </h2>

- <b>Docker</b>
- <b>Anaconda</b>
- <b>PostgreSQL</b>
- <b>pgAdmin</b>
- <b>Apache Airflow</b>
- <b>S3FS Fuse Filesystem</b>
- <b>AWS CLI</b>
- <b>Amazon S3</b>
- <b>Amazon EC2</b>
- <b>Amazon Lambda</b>
- <b>Amazon SNS</b>
- <b>Amazon RDS</b>


<h2>Project Workflow:</h2>


- Orchestrated the configuration of security groups for seamless communication between AWS services and components
- Managed the download and processing of stock data from Google Drive to a local machine
- Set up an Amazon S3 bucket for storing source data and scripts, and configured an AWS RDS instance for PostgreSQL database storage
- Provisioned an Amazon EC2 instance, installing necessary dependencies and mounting the S3 bucket for streamlined access to data and processing scripts
- Implemented data processing activities, transforming and moving data utilizing Python and Bash scripts
- Established a PostgreSQL table for storing processed data, designing and implementing SQL insertion queries
- Implemented Amazon SNS for real-time email-based pipeline monitoring alerts on success or failure
- Developed and deployed a data pipeline using Apache Airflow, Docker, and AWS services, aligning with the provided architecture
- Automated the data pipeline, creating a monitored S3 bucket and implementing an event-based Lambda function for triggered execution


