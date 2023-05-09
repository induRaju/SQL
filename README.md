# SQL
Road Safety Prediction
## Title: RoadSafety
This project aims in creating a database from the accident.csv dataset fro the purpose of analyisng the number of 
accidents which occurs in different types of road, road surface, weather conditions, light conditions, area etc.

## Problem Motivation:
    By examining the characteristics of the accident information, the number of big accidents is to be decreased. 
There may be one or more specific causes, such as poor lighting or hazardous road conditions, that contribute to an increase 
in accidents. To pinpoint the precise circumstances that cause the majority of accidents, we will evaluate the dataset. 
The main difference in tackling these problems comes up due to the difference between a Database Management System and 
excel data files.

## Getting Started
Dataset: https://www.kaggle.com/datasets/qasimhassan/reducing-the-number-of-high-fatality-accidents

### Dependencies
Describing the prerequisites, libraries, OS version, etc., needed for our application.
    Operating System: Windows 10
    IDE : Jupyter
    Python Version: Python 3.10.7
    Package Manager: pip
    Database: PostgreSql
    Packages: Pandas, psycopg2

### Installing
1. How/where to download your program
    https://www.python.org/downloads/ - Python Download
    https://jupyter.org/install - Jypyter installation
    https://www.postgresql.org/download/ - Psotgresql download

2. Installing Packages:
    1. pip install pandas
    2. pip install psycopg2
     
### Executing program
Step 1:Open folder named milestone2 in postgresql.
Step 2:Run the create table queries in the database which is present in create.sql file.
Step 3:Insert the values for 5 tables which is present in the load.sql file.
Step 4:The accident table and accident details table are bulk imported from the datasets using a python script.
    Step 4.1: Open the import.py file in jupyter notebook
    Step 4.2: Run the script to import the values into the tables.
Step 5:Then the queries are executed from the create.sql file.
Step 6:Indices are created for the purpose of query optimization which you can find again the create.sql file.
Step 7: A delete trigger is deleted to automatically delete contents from accidentdetails table if 
a value is deleted in the accident table. This query can be found in the create.sql file.

## Authors
Contributors names and contact info:
Rakshokini Umashankar - rakshoki@buffalo.edu
Kaviyaa Vasudevan - kaviyaav@buffalo.edu
Suriya Badrinath - suriyaba@buffalo.edu
