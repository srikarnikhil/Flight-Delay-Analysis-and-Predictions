1.data csv files should be uploaded to s3 bucket.
2.a user need to be created so that we get access key and secret.
3.we need to use these secrets in databriks to mount s3 bucket to a path in databricks.
4. all the necessary modules need to be imported before running the code to avoid errors.
5. once the data cleaning is done or model prediction is over the cleaned data is again stored to s3 bucket.
6.this cleaned files are dowloaded from s3 bucket using the python script and loaded into sqlite database.
7.downloaded csv files can also be imported into other DBMS(choice of user)
8.Queries are run against the data to answer some business questions.
9.These csv files or the saved db file can be imported tableau for further vizualizations
10.tablueau desktop needs to be installed to import these database or csv files.