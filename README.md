# DATA-PROJECT-DATABASE  

This repository contains the sql queries to solve the questions of the IPL project using SQL.
1. Number of matches played per year for all the years in IPL.
2. Number of matches won per team per year in IPL.
3. Extra runs conceded per team in the year 2016
4. Top 10 economical bowlers in the year 2015
5. Find the number of times each team won the toss and also won the match
6. Find a player who has won the highest number of *Player of the Match* awards for each season
7. Find the strike rate of a batsman for each season
8. Find the highest number of times one player has been dismissed by another player
9. Find the bowler with the best economy in super overs

## Getting Started  

#### **Clone the repo from GitHub**  
```bash
git clone https://github.com/Rajkumarsahu-xyz/data-project-database.git
```

#### **cd to the js-ipl-data-project directory**
```bash
cd data-project-database
```

#### **Install and Setup PostgreSQl in your system**  
Follow this link to understand how to install PostgreSQl  - [postgres](https://www.digitalocean.com/community/tutorials/how-to-install-postgresql-on-ubuntu-20-04-quickstart).

#### **Running the SQL queries**  
Refer to the index.sql file for creation of tables matches and deliveries, and then copy the data into the tables using below query. 
```bash
\COPY matches FROM 'data-project-database/csv-files/matches.csv' DELIMITER ',' CSV HEADER;

\COPY deliveries FROM 'data-project-database/csv-files/deliveries.csv' DELIMITER ',' CSV HEADER;
```

Now you can copy the queries in all the 9 files and run it on the Postgres terminal to see the result.
