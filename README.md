# Movies-ETL

## Overview

Amazing Prime Video team would like to evelop an algorithm to predict which low budget movies will become popular. To do this, they will be sponsoring a hackathon - an event where teams of programmers and analysts collaborate on a project, using data to solve a problem. 

I am assisting Amazing Prime by providing them a clean set of movie data by extracting data from two sources, transforming the datasets by cleaning and joining them, and then loading the clean data into SQL tables. 


Used ETL (Extract, Transform, Load) to create a data pipeline. 

Analysis is impossible without good data. 

Extract from two sources. Transform into one dataset and load it into SQL table. 

## Resources

- Data Sources: Wikipedia:wikipedia-movies.jason, Kaggle/MovieLens: movies_metadata.csv and ratings.csv 
- Software: Python, Pandas, Jupyter, PostgreSQL 11, pgAdmin 4, 

## Results

List of movies from 1990 to 2018. An iteratve process was used to 
1. **inspect** the data to identify problems; 
2. develop a **plan** to decide which data should be dropped,  which data should be fixed, and how to fix it; and
3. **execute** the repairs. 

This iterative process was followed many times until the dataset was clean and ready for use. 


Using regular expressions (Reg Ex)


## Summary
Once the data was successfully produced for the hackathon, Amazing Prime requested adjustments to the code so it could be updated on a daily baisis. I created an automated pipeline that will take in new data, perform the appropriate transformations, and load the data into existing tables. Amazing Prime now has real time data availalble to help them predict future sucess of movies. 

The final product was two SQL files


All information is available for review on Git Hub.
