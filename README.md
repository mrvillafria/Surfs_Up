# Surfs Up with Advanced Data Storage and Retrieval

## Overview of Project
For this week's project, we will be using SQLite and SQLAlchemy in addition to Python and Pandas in a Jupyter Notebook. SQLite is a serverless database engine that allows us to quickly setup a database engine without a server. SQLite is stored locally which allows quick testing in comparison to setting up a SQL database server. SQLAlchemy is a Python library that we'll use for querying data and can be used to perform the same query across different SQL dialects. Object Relational Mapper, ORM, is a primary feature of SQL Alchemy. ORM makes it possible to query a database using SQL or Python. 

### Purpose
The purpose of this week's project was to run weather analytics for a potential business opportunity called Surf 'n Shake. The idea of Surf 'n Shake is to serve surfboards and ice cream to locals and tourists in Oahu. In order to build a strong business plan for our investors, one of the main concerns we wanted to look into was how temperature could affect the business. We pulled temperature statistics for the months of June and December so we can analyze weather trends. This data will help determine if Surf 'n Shake is sustainable year-round.

## Results
To get the temperature statistics for June and December, we first had to query to retrieve all of the temperatures from our hawaii.sqlite database for those two months. We then converted the temperatures to a list and then created a Dataframe from the list. From there, the easiest way to get basic statistic details was by using Pandas describe method. 

#### Summary Statistics for June
![June_Temps](/Resources/June_Temps.PNG)

#### Summary Statistics for December
![December_Temps](/Resources/December_Temps.PNG)

### Analysis of June and December Temperature Statistics
Here are three key differences between June and December:
- There are more data entries for June (1,700) than there is for December (1,517)
- The average temperature in for June (74.94 degrees) is ~3.9 degrees higher than December (71.04 degrees)
- The minimum temperature in June (64 degrees) is 8 degrees higher than December (56 degrees)

## Summary
