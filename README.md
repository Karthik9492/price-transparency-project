# price-transparency-project
# Modular Architecture diagram​

# Objective:
The goal of this project is to promote transparency in hospital pricing by collecting, cleaning, transforming, and analyzing publicly available hospital data. The processed data is then visualized through interactive dashboards for easier interpretation and decision-making.
Workflow Overview:
# 1. Data Collection:
Raw hospital pricing data was collected from public hospital sources. The collected files were stored securely in Microsoft OneDrive for easy access and backup.
# 2. Data Cleaning:
Used Python (Pandas) for data preprocessing. Key tasks included handling missing values, correcting data types, normalizing column names, and filtering relevant pricing information. Cleaned datasets were stored and version-controlled in GitHub for collaborative development and deployment.
# 3. Data Integration:
Utilized Azure Data Factory to import and orchestrate the data pipeline. Connected to the GitHub repository and fetched cleaned datasets for transformation.
# 4. Data Storage:
Transformed data was stored in Azure Data Lake Storage Gen2, providing scalable and secure storage optimized for big data analytics.
# 5. Analytics and Processing:
Performed further data analysis using Azure Synapse Analytics to uncover pricing patterns, regional cost differences, and provider-specific variations.
# 6. Dashboard Visualization:
Developed dynamic dashboards using Power BI, Tableau, and Looker. These dashboards allow stakeholders to explore pricing trends, compare hospitals, and identify cost-effective healthcare options.
# Tools and Technologies Used:
Python (Pandas)
Microsoft OneDrive
GitHub
Azure Data Factory
Azure Data Lake Storage Gen2
Azure Synapse Analytics
Power BI, Tableau, Looker
# Outcomes & Impact:

• Delivered a transparent view of hospital pricing data for consumers and policymakers.

• Enabled insights into healthcare cost variation across providers and regions.

• Enhanced accessibility of complex datasets through user-friendly dashboards.

