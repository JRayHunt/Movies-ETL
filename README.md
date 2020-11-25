# Movies-ETL
## Purpose
The objective of this project is to use ETL to merge and cleanse multiple data sources for hackathon participants.
After initial review, the decision was madeto update this data daily by automating the ETL process. This required us to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.

## Summary
The process was very similar to the work we performed during the module activities. Because of the large size of the ratings file, the upload took 1.6 hours. Automatically loading the data into the Postgres database resulted in the following count of rows per table:
[movies_query.png](/Resources/movies_query.png)
[ratings_query.png](/Resources/ratings_query.png)
