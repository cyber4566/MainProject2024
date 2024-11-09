# NBA Performance and Prediction Analysis

Machine learning has been implemented into various aspects of life and this project aims to demostrate how machine learning techniques can be utilised in the NBA to determine the set of players 
that perform the best(outliers) and using it to predict the outcome of two teams based on previous history..

## Dataset

Our analysis draws from a rich set of data files containing player, team, and coaching statistics:

1. **Player Data**
   - `Player Regular Season Stats`: Detailed player performance metrics for each season.
   - `Player Regular Season Career Totals`: Aggregated player performance across careers.
   - `Player Playoff Stats`: Player statistics from playoff games.
   - `Player Playoff Career Totals`: Career totals specifically from playoff games.
   - `Player All-Star Game Stats`: Performance data from All-Star games.

2. **Team Data**
   - `Team Regular Season Stats`: Team performance stats across regular seasons.

3. **Draft Data**
   - `Complete Draft History`: Historical data on NBA draft picks, which can help uncover long-term trends.

4. **Coaching Data**
   - `coaches_season.txt`: Coaching records by season, providing insight into coaching effectiveness over time.
   - `coaches_career.txt`: Career records for coaches, including win/loss records and playoff performance.

## Usage Guide

This project contains two main components:

1. **Outcome Prediction Model**
   - A Python-based model to predict game outcomes between two teams based on a range of features from player and team history.

2. **Outlier Detection Model**
   - Identifies standout players who significantly exceed average performance, using machine learning techniques to mark them as outliers. 


