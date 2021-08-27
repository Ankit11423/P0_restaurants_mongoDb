# P0_restaurants_mongoDb#
## Project Description
BY using Hortonworks-sandbox in virtual Machine,i created directories in Hdfs and loaded the data in it,later on i created external tables using HiveQL and
analyzed the data using some aggregations like filtering and bucketing
## Technologies Used
* MongoDB
* PyMongo
* Git
## Features
* No SQL DataBase
* Processing unstructured data in Mongo shell
* Processing unstructured data in PyMongo using Python Program
* some queries are solved using NoSQL

## Getting Started
* To start this project user need to install MongoDB in our system. Also Need to install Mongo Tool for importing the dataset in MongoDB Database. MongoDB Download URL :https://www.mongodb.com/try/download . MongoDB Database Tool Download URL : docs.mongodb.com/database-tools/installation/installation
* "git clonehttps://github.com/Ankit11423/P0_restaurants_mongoDb.git" by using this we can pull the dataset 
*After downloading the MongoDB CLI we have do some setup . here we will be using 2 application(one is mongod and another is mongos)
*mongod is the database service and mongo is shell . everytime when we are going to use MongoDB database we have to first start our Mongod
* use this command for allocating the folder where mongoDB will going to Create and store Database ->"C:\Program Files\MongoDB\Server\5.0\bin\mongod" --dbpath="c:\data\db" [Note:- --dbpath is our created folder path]
* create a Database in your MongoDb and in that create Collection using command <create DatabaseName> , db.createCollection()
* Later load the restaurants dataset in the MongoDB Database by using Mongo Tool and use this command for import the dataset "C:\Program Files\MongoDB\MongoDB_Import\bin\mongoimport" --db products --collection zipcodes --type json --file restaurants.json"
* use database_name;
* Now we can create queries and analyze the data
*also we can perform all queries through Python Program 
*first we have to install PyMongo using this command "pip install pymongo"
*We have to import Pymongo in our python program and connection should be done with PyMongoClient
*Only than we will be able to execute queries and fetch result from MongoDB Collection
## Usage
* Create Database on MongoDB 
* Load the data using MongoTool
* Create Collections

