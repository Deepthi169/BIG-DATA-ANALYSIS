# BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: DEEPTHI G

*INTERN ID*: CT04DY172

*DOMAIN*: DATA ANALYSIS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

Task 1 – Big Data Analysis

*DESCRIPTION*

The primary goal of Task 1 was to perform analysis on a large dataset using a scalable big data processing tool such as PySpark or Dask.
The dataset chosen for this task was insurance_data.csv, which contains records of health insurance claims.
The dataset includes multiple attributes such as:

*PatientID* – Unique identifier for each patient
*age* – Age of the patient (some missing values)
*gender* – Male or Female
*bmi* – Body Mass Index, a measure of body fat
*bloodpressure* – Blood pressure reading
*diabetic* – Yes/No indicator for diabetic condition
*children* – Number of children dependent on the patient
*smoker* – Yes/No indicator for smoking status
*region* – Geographical region of the patient
*claim* – The medical insurance claim amount

The task followed the ETL (Extract – Transform – Load) process:

Extract – The dataset was read into PySpark from a CSV file.

Transform – Data was cleaned by handling missing values and formatted into the correct data types.
Then, various group-based aggregations were performed to derive insights such as:

Average claim amount per region
Count of smokers vs non-smokers
Average BMI by diabetic status
Average claim by gender

Load – The processed dataset was stored in the Parquet format, which is a columnar storage file format optimized for big data analytics.

The output provided clear, actionable insights from the dataset:

Patients in the northeast region had the highest average claim amounts.
The number of non-smokers was significantly higher than smokers in the dataset.
Diabetic and non-diabetic patients showed slightly different average BMI values.
Male patients had a higher average claim amount compared to female patients.
These results can help insurance companies understand patterns in claim amounts and make informed policy decisions.

*TOOLS USED*

PySpark – The Python API for Apache Spark, a distributed computing framework used to process large datasets efficiently.
It allows operations to be performed on data that is too large to fit into memory by splitting it across multiple cores or even multiple machines.
Pandas (optional) – Useful for converting smaller Spark DataFrames into pandas DataFrames for quick checks or plotting.
NumPy (optional) – Used indirectly by pandas and Spark for numerical operations.
Parquet File Format – Chosen for storing the processed output because it is efficient in both storage and read performance, especially for analytical queries.

*Editor / Platform*

The task was performed using:

*Google Colab* – A cloud-based Python notebook environment provided by Google, which removes the need for local installation of Spark and Java. It comes with a ready-to-use Python environment and the ability to install PySpark directly within the notebook.
*GitHub* – For storing and version-controlling the project files, ensuring the work can be shared and pulled to other environments.

*APPLICATIONS*

This kind of big data analysis has applications in:

Health Insurance – Identifying high-claim regions, tracking health risk indicators (BMI, smoking habits, diabetes status), and developing targeted health plans.
Healthcare Policy Planning – Using aggregated data to design region-specific awareness campaigns or intervention programs.
Fraud Detection – Detecting unusual patterns in claims which might indicate fraudulent activity.
Predictive Analytics – Feeding this cleaned and aggregated data into machine learning models to predict future claim amounts, detect high-risk individuals, or forecast healthcare costs.
Business Intelligence Dashboards – The output from Task 1 can be directly used in BI tools such as Tableau, Power BI, or integrated into dashboards created in Task 3 for interactive visualization.
