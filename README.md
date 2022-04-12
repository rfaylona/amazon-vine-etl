# Big Data Homework - "Alexa, can you handle big data?"

## Background
In this challenge, using ETL knowledge; many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. The first goal for this challenge will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance.

Create DataFrames to match production-ready tables from two big Amazon customer review datasets.

### Process

Using the furnished schema to create tables to create the RDS database.

Creating two separate Google Colab notebooks and extract any two datasets from the list at review dataset, one into each notebook.

For each notebook, complete the following:

Count the number of records (rows) in the dataset.

Transform the dataset to fit the tables in the schema file. Be sure the DataFrames match in data type and in column name.

Load the DataFrames that correspond to tables into an RDS instance. Note: This process can take up to 10 minutes for each. Be sure that everything is correct before uploading.