# Covid19-Data-Engineering-Project

![AWS Architecture](./AWS%20Architecture.png)

Dataset URL:  https://aws.amazon.com/blogs/big-data/a-public-data-lake-for-analysis-of-covid-19-data/  

Steps:

1. Understood the data in the datasets.
2. Uploaded the data to S3.
3. Built crawlers using AWS Glue.
4. The data can be seen on Athena.
5. Built a Data Model.
6. Built a Dimensional model using star schema.
7. Created Dimension and Fact Tables in Python (pandas).
8. Loaded data into those tables in Python (pandas).
9. Save the resulted CSV files onto S3.
10. Written an AWS Glue Job using Python Shell Script.
   - Connected to Redshift.
   - Created Dimension and Fact Table schemas.
   - Loaded data from CSV files in S3 to Redshift.

### This is the creation of a datawarehouse.
