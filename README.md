# NHL_ETL

## sources of data: https://www.kaggle.com/martinellis/nhl-game-data

## Data Cleanup & Analysis

The type of transformation needed for this data (cleaning, joining, filtering, aggregating, etc).
The type of final production database to load the data into (relational or non-relational).
The final tables or collections that will be used in the production database.

We EXTRACTED these files from the Kaggle site.

Game.csv has 16 data fields:

game_id
season
type
date_time
date_time_GMT
away_team_id
home_team_id
away_goals
home_goals
outcome
home_rink_side_start
venue
venue_link
venue_time_zone_id
venue_time_zone_offset
venue_time_zone_tz


Team_info.cvs has 6 data fields:

team_id
franchiseId
shortName
teamName
abbreviation
link

Project Report

Extract: your original data sources and how the data was formatted (CSV, JSON, pgAdmin 4, etc).
Transform: what data cleaning or transformation was required.
Load: the final database, tables/collections, and why this was chosen.
