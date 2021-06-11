# Data Modeling with Apache Cassandra

## Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.  

### Objectives  

- Apply what I've learned on data modeling with Cassandra

- Build an ETL pipeline using Python

- Define and model my NoSQL database keeping in mind the queries I need to run

- Write an ETL pipeline that load the data into tables you create in Apache Cassandra and run your queries  

## Get Started  

`git clone https://github.com/tatianamara/data-modelling-with-apache-cassandra.git`

### Prerequisites

- Python3 installed (you can download [here](https://www.python.org/downloads/))
- Apache Cassandra local connection. Please see detailed instructions in the [https://cassandra.apache.org/quickstart/).
- Install requirements with pip3 install -r requirements.txt.

#### Run the Jupyter Notebook `Project_1B_ Project_Template` to execute all the code and create the tables with correct data

## Project Datasets

### Event Data

The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:

```
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
```
