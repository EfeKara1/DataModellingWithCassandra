# DataModellingWithCassandra
# Datasets
## Data
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv

## Project Template

## Project Steps

Below are steps i followed to complete each component of this project.
Modeling existing NoSQL database or Apache Cassandra database

    Design tables to answer the queries outlined in the project template
    Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
    Develop CREATE statement for each of the tables to address each question
    Load the data with INSERT statement for each of the tables
    Include IF NOT EXISTS clauses in your CREATE statements to create tables only if the tables do not already exist.
    Test by running the proper select statements with the correct WHERE clause

Build ETL Pipeline

    I implemented the logic in section Part I of the notebook template to iterate through each event file in event_data to process and create a new CSV file in Python
    I made the necessary edits to Part II of the notebook template to include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in your data model
    Test by running SELECT statements after running the queries on your database

