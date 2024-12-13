# Exploratory Data Analysis

**Project Description:**
Exploration of food vendor data in Vancouver to identify geographic and business insights.

**Project Title:**
Food Vendor Distribution Analysis

**Objective:**
To analyze food vendor distribution across Vancouver, focusing on Downtown and identifying trends in vendor types.

**Dataset:**
The food vendors dataset from the City of Vancouver website: Food Vendors Dataset.

**Methodology:**
- Raw data ingestion into an S3 bucket.
- Data profiling and cleaning using AWS Glue DataBrew.
- Aggregation of vendor counts and grouping by geographic areas.
- Analysis of vendor types specific to Downtown.

**Tools and Technologies:**
- AWS S3
- AWS Glue DataBrew
- AWS Athena

**Deliverables:**
- Count of food vendors in Downtown.
- Identification of the most common vendor types.
- Insights into vendor distribution and clustering.

# Descriptive Analysis

**Project Description:**
Detailed descriptive statistics of food vendor data, examining distributions and key trends.

**Project Title:**
Descriptive Analysis of Food Vendors in Vancouver

**Objective:**
To assess and visualize the distribution and characteristics of food vendors in Vancouver.

**Dataset:**
Food vendors dataset from the City of Vancouver.

**Methodology:**

- Upload and store raw data in an S3 bucket.
- Data cleaning (e.g., replacing missing values, removing duplicates).
- Use of AWS Glue DataBrew for profiling and transformations.

**Tools and Technologies:**
- AWS S3
- AWS Glue DataBrew
- Excel for preliminary storage and visualization

**Deliverables:**
- Cleaned dataset stored in the transformed S3 bucket.
- Summary statistics and visualizations.
  
# Diagnostic Analysis

**Project Description:**
In-depth diagnostic analysis to identify patterns and issues in food vendor data.

**Project Title:**
Diagnostic Analysis of Food Vendor Clusters in Vancouver

**Objective:**
To uncover causes behind geographic clustering of vendor types and analyze underlying trends.

**Background:**
Vancouver’s food vendors demonstrate significant clustering, with trends in product types and locations.

**Dataset:**
The food vendors dataset sourced from the City of Vancouver.

**Methodology:**
- Use of ETL pipeline for data transformation.
- Analysis of geographic clusters.
- Grouping and comparison of vendor types.

**Tools and Technologies:**
- AWS S3
- AWS Glue
- AWS Glue DataBrew

**Deliverables:**
- Geographic cluster analysis report.
- Identification of patterns in vendor distribution.

**Timeline:**
- Data ingestion and cleaning: 2 weeks
- ETL and cluster analysis: 3 weeks

# Data Wrangling

**Project Description:**
Preprocessing and cleaning of raw data to ensure consistency and readiness for analysis.

**Project Title:**
Data Wrangling for Food Vendor Insights

**Objective:**
To clean and transform raw food vendor data for exploratory and diagnostic analysis.

**Background:**
Unprocessed food vendor data contained missing values, duplicates, and irrelevant columns.

**Dataset:**
Food vendors dataset stored in the S3 raw bucket (fv-raw-harshil).

**Methodology:**
- Ingestion of raw data into S3.
- Profiling and cleaning using AWS Glue DataBrew.
- Storage of cleaned data in the transformed bucket (fv-trf-harshil).

**Tools and Technologies:**
- AWS S3
- AWS Glue DataBrew

**Deliverables:**
- Cleaned and structured dataset.
- Data stored in transformed S3 bucket.

**Timeline:**
- Profiling and cleaning: 1 week
- Verification and storage: 1 week

# Data Quality Control

**Project Description:**
Ensuring high-quality data by implementing validation and governance protocols.

**Project Title:**
Data Quality Control for Vancouver Food Vendors

**Objective:**
To guarantee the integrity and reliability of data used for analysis and reporting.

**Background:**
The raw dataset contained errors and inconsistencies that required systematic cleaning and validation.

**Scope:**
Focus on detecting and correcting data quality issues, including missing values, duplicates, and inaccuracies.

**Methodology:**
- Profiling data in AWS Glue DataBrew.
- Cleaning processes (e.g., replacing nulls, removing duplicates).
- Validation via an ETL pipeline in AWS Glue.

**Deliverables:**
- Quality-checked dataset stored in the transformed S3 bucket.
- Reports on data quality metrics and cleaning operations.

**Timeline:**
- Profiling and validation: 2 weeks
- Cleaning and final storage: 1 week
