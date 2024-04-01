## Language Code Data Modelling project

This project is a Data Engineering project which demonstrates relational modelling of raw data.

A publicly available raw data set has been analysed and normalized into a postgres database.


ER Diagram visualized from the raw dataset:
<img width="791" alt="DataModel_LanguageCodes" src="https://github.com/coder-gagan/language-codes-modelling/assets/141386400/77e673a1-f068-465c-8094-f9e4fc650cea">


### This project demonstrates my expertise in
- using postgres DB and Jupyter Notebook
- analysing spreadsheets-based raw dataset for identifying possible relationships among disjoint data
- documenting the relationships among data as a Entity Relationship(ER) Diagram
- writing pandas-based python script for extracting data from these sheets and capturing them in intermediate dataframes
- writing psycopg2-based python script for executing a DDL that reflects the determined relationship
- writing psycopg2-based python script for executing DML scripts that move records from dataframes into the tables created
- adding/altering the constraints on tables to allow for data normalization


### The python script written in Jupyter Notebook does the following
- Reads data from a language-codes dataset containing a set of raw .csv files
- Uses pandas library to create intermediate dataframes from data processing
- Uses pandas to clean-up unneeded columns, renaming defaulted column names to simpler names
- Uses psycopg2 to create a database and establish a connection with it
- Uses psycopg2 to create schema and related constraints within the created database
- Uses psycopg2 to insert records into tables
- demonstrates a deliberate contraint check failure
- relaxes a constraint and re-inserts records from the dataframe without running into errors


### Technologies used
- scripting language -> Python
- python libraries -> pandas (for data analysis), psycopg2 (database adapter for connecting to postgres via python code)
- data modelling -> draw.io
- database -> postgresql


### Credits
This inspiration for creating this project was derived from Darshil Parmar's Youtube channel which has videos and tutorials on several projects for aspiring Data Engineering projects. For sake of individual learning during hands-on, a different dataset was deliberately used than the one used by Darshil in his video demonstration. For more info about Darshil, visit https://datawithdarshil.com/
