# snowflake-python-lambda-layer
AWS Lambda Layer for snowflake - includes snowflake-connector-python and pandas

AWS Lambda Layer to use with Lambda functions requiring:

snowflake-connector-python
pandas

Instructions from:
https://medium.com/analytics-vidhya/aws-adding-python-libraries-to-lambda-layers-8c4eaf8fed80

Layer built using wsl Ubuntu 20.04

Instructions ->

1. Upload zip file to a S3 bucket
2. Create lambda layer and point to the zip file in S3
