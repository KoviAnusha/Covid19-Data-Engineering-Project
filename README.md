# Covid19-Data-Engineering-Project

![AWS Architecture](./AWS%20Architecture.png)

Dataset URL:  https://aws.amazon.com/blogs/big-data/a-public-data-lake-for-analysis-of-covid-19-data/  

Steps:

1. Understand the data in the datasets
2. Upload the data to S3
3. Build crawlers using AWS Glue
4. The data can be seen on Athena
5. Build Data Model
6. Build Dimensional model using star schema
7. Creation of Dimension and Fact Tables in python (pandas)
8. Loading data into those tables in python (pandas)
9. Save resulted CSV files onto S3
10. Writing a AWS Glue Job using Python Shell Script
   - Connect to Redshift
   - Create Dimension and Fact Table schemas.
   - Load data from CSV files in S3 to Redshift

### This is the creation of a datawarehouse.
