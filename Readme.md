# Project Name : Python automation For GCP
This project is all about interacting and automating the dataset to be to be used in Google cloud storage Buckets and Analyse the created pytables Loaded in to BigQuery services all this automated by using Python. 

# Description
The purpose of this repo is to provide an interface to GCP services using Python. This allows you to write Python code to access GCP resources like BigQuery, Cloud Storage,  BigTable , compute etc.

* python libraries are used to create fake datasets (faker)
* once you run the main.py it automatically creates fake data instances almost 500 datasets and automatically later creates tables and dataquery in to the BigQuery 
* this all is done through the json file which is created to authenicate to google cloud console 

**cloud_bigtable file has the py files to automatically create instances and loads the created datasets in the bigquery when main.py calls it

**Compute_operations are responsible of storing the values on to the bucket storage but unfortunately my billing services is not getting verified due to some reasons this operation is not working therefore once it gets verified then only the operations will execute and will load on to the bucket storage 

just that we hav to specify the created bucket to all the required feilds which asks for destination then it will automatically be loaded. Unfortunately im unable to do it because of billing issues and document verification errors

**Data_analytics involves in creating dataset instance locally, extracting the data, generating the datasets using faker python library and loading it on to the bucket where inturn fetched by the bigquery for analytical purposes.

# Installation
To install this application, follow these steps:

Install Python on your machine if you don't already have it installed.
Install the required dependencies by running pip install -r requirements.txt in the project directory.

# Contributor
Ashique George
