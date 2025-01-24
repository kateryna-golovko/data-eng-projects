# Data Modeling with Cassandra
The project is provided by Udacy as part of the "Data Engineering with AWS" course, this is the first out of four projects. The Jupyter notebook with some pre-prepared code is provided. The project consists of two parts: ETL Pipeline for Pre-Processing the Files and Complete the Apache Cassandra coding portion of the project.
## Part 1.ETL Pipeline for Pre-Processing the Files
- Import Python packages that will be used in the project
- Process the files to create the data file csv that will be used for Apache Casssandra tables
- Check the number of rows in the csv file to ensure everything worked as expected
## Part 2. Complete the Apache Cassandra coding portion of the project
- Create a cluster
- Create a keyspace
- Set keyspace
- Create 3 tables for the 3 provided queries:
    - Query 1:  Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
    - Query 2: Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
    - Query 3: Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'
- For each query:
    - Choose appropriate primary key (and clustering column(s) if required)
    - Create a table with required columns only
    - Populate the table using the created in part 1 csv file
    - Use SELECT statement to verify the appropriate data was entered into the table
    - Use Pandas to make output more readable and understandable
- Drop all the created tables
- Close the session and cluster connection
