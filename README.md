# Database query with CLT

__Author: Bokai Zhou__

This is the third individual project to generate a script that queries a database. It is combined with the command-line tool. 

This project is to provide introduction to data exploration and analysis using SQL language, which should be a must tool for every data scientist - both for getting access to data, but more interesting, as a simple tool for advance data analysis. Some of the queries referred to [Data Analysis using SQL](https://www.kaggle.com/code/dimarudov/data-analysis-using-sql/notebook)


### Database: [European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer)

| Table name |	Total Rows |	Total Columns |
|:----:|:--------:|:----:|
|Country|	11|	2|
|League	|11	|3|
|Match	|25979	|115|
|Player|	11060	|7|
|Player_Attributes	|183978|	42|
|Team	|299|	5|
|Team_Attributes	|1458	|25|


### Command lines:
- describe: Load the data and print all the tables in dataset

- find-countries: Find all countries in the database
  
- find-leagues: Find all leagues in the database

- show-teams: Find first 10 teams in the database
           
- season-info: Find detailed information for each league in each season
  
- show-matches: Find first 10 detailed matches in the database

- myquery: Query the database with your own queries

  Arguments: 
    --q, default="SELECT * FROM Country;", Input your sql query
