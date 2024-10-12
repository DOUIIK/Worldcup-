# World Cup Data Analysis Project

## Overview

This project analyzes historical data from the FIFA World Cup, focusing on player statistics, match outcomes, and tournament details across different years. Using datasets from multiple World Cup tournaments, this analysis provides insights into which countries and players have performed the best in various aspects such as total goals, attendance, and match results.

## Datasets

- **WorldCupPlayers.csv**: Contains information on players, including their position, coach, and performance in each match.
- **WorldCupMatches.csv**: Includes match data such as date, teams, goals scored, referees, and attendance.
- **WorldCups.csv**: Provides a summary of each tournament, including the host country, winners, number of goals, matches played, and attendance.

## Key Features

- **Data Cleaning**: The datasets were cleaned to handle missing data and standardize country names (e.g., "Germany FR" to "Germany").
- **Podium Count**: A bar chart that visualizes how many times each country has won, placed second, or third in World Cups.
- **Top Scoring Countries**: An analysis of the top goal-scoring teams, with visualizations for the countries with the most goals across World Cup tournaments.
- **Word Cloud**: A word cloud generated from the countries that have won the most World Cup matches.
- **Attendance, Matches, and Goals**: Various visualizations that track attendance, number of qualified teams, matches played, and goals scored in each tournament.
- **Top 5 Scoring Teams by Year**: A stacked bar chart that shows the top 5 teams with the highest number of goals in each World Cup.

## Libraries Used

- **Pandas**: For data manipulation and cleaning.
- **Seaborn & Matplotlib**: For generating static visualizations.
- **Plotly**: For interactive visualizations of the top goal-scoring teams.
- **WordCloud**: For generating word clouds to highlight the most successful teams.
- **Numpy**: For numerical computations and data transformations.

## Visualizations

- **Bar Charts**: Podium finishes, top-scoring countries, and other tournament metrics.
- **Word Cloud**: A graphical representation of the teams with the most World Cup wins.
- **Stacked Bar Chart**: Visualizing the top-scoring teams over time.
