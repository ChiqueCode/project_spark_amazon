# project_spark_amazon

Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. However, they are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite taxing on the average local computer. 

ETL process performed completely in the cloud and uploaded the DataFrame to an RDS instance. Used PySpark & SQL to perform a statistical analysis of selected data.


Created DataFrames to match production-ready tables from two big Amazon customer review datasets.
Analyzed whether reviews from Amazon's Vine program are trustworthy.
