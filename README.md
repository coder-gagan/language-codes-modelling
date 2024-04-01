This project is a Data Engineering project which demonstrates relational modelling of raw data.

The project has python script written in Jupyter Notebook that does the following:
- Reading data from a raw language codes dataset containing a set of raw csv files
- Using pandas library to create intermediate dataframes from data processing
- Using pandas to clean-up unneeded columns, renaming defaulted column names to simpler names
- Using psycopg2 to create a database and establish a connection with it
- Using psycopg2 to create schema and related constraints within the created database
- Using psycopg2 to insert records into tables
- demonstrating a deliberate contraint check failure
- relaxing a constraint and re-inserting records from the dataframe without running into errors
