# IPL Database Analysis Project

This project is an in-depth analysis of the Indian Premier League (IPL) from 2008 to 2022 using SQL. The dataset used contains over 225,000 records from ball-by-ball match data, covering various aspects such as player performances, team statistics, match outcomes, and more. The project showcases advanced SQL queries, including complex views, functions, procedures, and database normalization.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)

## Project Overview
The IPL Database Analysis Project is designed to help stakeholders such as team managers, players, and administrators gain valuable insights through SQL-based analytics. The project provides tools to evaluate player performance, team strategies, match summaries, and win/loss statistics.

## Dataset
The dataset was sourced from Kaggle and contains detailed ball-by-ball records of IPL matches from 2008 to 2022. You can find the dataset [here](https://www.kaggle.com/datasets/vora1011/ipl-2008-to-2021-all-match-dataset).

### Key Tables:
- `matches`: Contains details about each match.
- `deliveries`: Includes ball-by-ball data such as runs scored, wickets, and players involved.
- `teamsmaster`, `playermaster`, `umpiresmaster`: Master tables with data about teams, players, and umpires.

## Features
- **Complex Queries**: Advanced SQL queries analyzing player rankings, team performance, and match outcomes.
- **Database Views**: Custom views like `PlayerRanking`, `MatchDetails`, `WinPercentageByTeam`.
- **Stored Procedures**: Procedures to calculate team win percentages, player strike rates, and boundary counts in specific matches.
- **Database Triggers**: Backup mechanisms ensuring data integrity before any deletion operations on master tables.
- **Database Normalization**: Data stored in third normal form (3NF) to ensure efficient data storage and retrieval.
