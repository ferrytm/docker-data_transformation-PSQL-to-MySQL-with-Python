# docker-data_transformation-PSQL-to-MySQL
This task is to showcase proficiency in Docker, Database Management, ETL (Extract, Transform, Load), and Python scripting. The task involves setting up MySQL and PostgreSQL databases within Docker Desktop, importing CSV datasets from your local machine, storing the aggregated data in PostgreSQL, and subsequently transferring it to MySQL using Python 3.

## Preparing the Environment
Refer to .\scripts\installation process.txt for more details.
1. Install Docker Desktop 
2. Create PostgreSQL image and Mysql image in Docker
3. Verify the connection to PostgreSQL and MySQL
4. Install Anaconda
5. Install pstgresql connector and Mysql connector in Anaconda

## Process Data 
Refer to Jupiter Notebook file in .\scripts\spotify_artist_analysis.ipynb for more detail.
1. Read data file from local csv data, in .\datasource\spotify_top_songs_audio_features.csv
2. Aggregate data by computing the average of danceability, energy, and tempo of songs grouped by musical key, artist_name, and track_name.
3. Load aggregated data to PostgreSQL
4. Transfer the aggregated data from PostgreSQL table to MySQL table


