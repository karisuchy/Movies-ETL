# Movies-ETL

## Overview

The Amazing Prime Video team would like to develop an algorithm to predict which low budget movies will become popular. To do this, they will be sponsoring a hackathon - an event where teams of programmers and analysts collaborate on a project, using data to solve a problem. 

Amazing Prime realizes that good analysis is impossible without good data. I assisted them by extracting movie data from two sources, transformed the datasets by cleaning and joining them, and then loaded the clean data into SQL tables so they have clean movie data to provide to hackathon participants. 

## Resources

- Data Sources: Wikipedia:wikipedia-movies.jason, Kaggle/MovieLens: movies_metadata.csv and ratings.csv 
- Software: Python 3.7, Jupyter 6.3.0, Pandas 1.2.4, PostgreSQL 11, pgAdmin 4, 

## Results

ETL (Extract, Transform, Load) was used for this project. Starting with a list of movies from 1990 to 2018, an iterative process was followed to: 
1. **inspect** the data to identify problems; 
2. develop a **plan** to decide which data should be dropped, which data should be fixed, and determine how to fix it; and
3. **execute** the repairs. 

This iterative process was followed many times until the dataset was clean and ready for use. Two examples of the type of python code used are included below. 


Code used to merge columns:

![merging_columns](https://user-images.githubusercontent.com/90162669/141882626-9db53bff-0c56-4723-8502-d275496092a0.png)


Code used to provide consistent format of box office dollars:

![clean_box_off_data](https://user-images.githubusercontent.com/90162669/141882268-184e48f1-430f-4876-aefa-934f1f5f78b7.png)




## Summary

The end product was two SQL files containing information about 6,052 movies and 26 million corresponding reviews. 

Once the data was successfully produced for the hackathon, Amazing Prime requested adjustments to the code so it could be updated on a daily basis. I created an automated pipeline that will take in new data, perform the appropriate transformations, and load the data into existing tables. Amazing Prime now has real time data available to help them predict future success of movies. 

All information is available for review on Git Hub.
