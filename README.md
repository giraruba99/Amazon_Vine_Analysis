# Amazon_Vine_Analysis
This analysis touches big data and cloud storage of huge amount of data. Thus, there are so many moving parts that need to work in synchronized way, and we were able to come with a beautiful & meaningful analysis.

## Purpose of the Analysis
* The main purpose of this analysis is to use a AWS S3 bucket stored data on Amazon reviews, create data frames according to different criteria, create a server in PostgreSQL and export CSV for later analysis.

## Results and Analysis
* Amazon_Reviews_ETL
- We selected `Lawn and Garden` for this analysis, and the ETL process went smoothly. We were able to create a DataFrame exclusively for Lawn and Garden. Below is the image of our DataFrame table.


- The 4 data frames created on Google Collab notebook, we were able to create 4 tables on PostgreSQL data base.

* Amazon Vine Analysis
- Then we were able to create DataFrames based on votes, and those DataFrames are going to be used to get some insight in to vines and no vines.
