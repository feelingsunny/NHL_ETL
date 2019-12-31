# NHL_ETL

## sources of data: https://www.kaggle.com/martinellis/nhl-game-data

## Data Cleanup & Analysis

The type of transformation needed for this data (cleaning, joining, filtering, aggregating, etc).
The type of final production database to load the data into (relational or non-relational).
The final tables or collections that will be used in the production database.

## Queries Used
* Data Definition Language Statements:
  * ALTER 
  * DROP
  * CREATE VIEW
  * DROP VIEW
  
* Data Manipulation Language Statements: 
  * SELECT
  * APPEND
  * DELETE
  * UPDATE
  * JOIN
  
 * Aggregate Functions: 
   * SUM 
   * COUNT
   * GROUP BY 
   * WHERE 

## Project Report

Extract: your original data sources and how the data was formatted (CSV, JSON, pgAdmin 4, etc).
Transform: what data cleaning or transformation was required.
Load: the final database, tables/collections, and why this was chosen.

![ERD](https://user-images.githubusercontent.com/49255104/71630345-07a61580-2bc8-11ea-9d96-4ddbec818604.png)

* The transformed files were saved as a csv from Jupyter notebook and imported into pgAdmin for use in our queries.  The files were created in pgAdmin and joined into one table.  This resulting table is the LOAD portion of our ETL project.

* This project enables queries on NHL data at the team level.  Incorporating the team.csv file provides critical information so we can identify each team by something other than a randomly assigned identification number.

* Code and result from joining tables:

![Picture1](https://user-images.githubusercontent.com/49255104/71630374-391ee100-2bc8-11ea-89df-9780610a9787.png)

## All Nashville Predators home games
  
![Picture2](https://user-images.githubusercontent.com/49255104/71630377-3c19d180-2bc8-11ea-874d-e17121bd4c78.png)

## Nashville home games when they scored 4 or more goals

![Picture3](https://user-images.githubusercontent.com/49255104/71630379-3e7c2b80-2bc8-11ea-8a68-4d1d098ef45b.png)

## Nashville home games versus St Louis

![Picture4](https://user-images.githubusercontent.com/49255104/71630382-4045ef00-2bc8-11ea-96be-61b6ebe634a2.png)

## Nashville home wins in regulation

![Picture5](https://user-images.githubusercontent.com/49255104/71630387-420fb280-2bc8-11ea-8106-b1f7fc32e896.png)
