### Table of Contents

1. [Installation](#installation)
2. [Instructions](#instructions)
2. [Project Motivation](#motivation)
3. [File Description](#files)


## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*. Additionly please install: python3 install pydot

## Instructions <a name ="instructions"></a>
1. Run load_and_clean.ipynb
2. Run home_team_prediction.ipynb and away_team_prediction.ipynb
3. Run result.ipynb

## Project Motivation<a name="motivation"></a>

This is the final DS340W Project for Prithvi Kamath.

Football stats have been around since the invention of football in the 19th century. The English Premier League is by far the most-watched soccer league attracting 3.2 billion viewers worldwide. In the Premier League, there are a total of 20 teams and only one team can win the title. 3 points are awarded for a win, 1 point for a draw, and 0 for a loss. Intuitively, the team with the most points at the end of the season wins. Every team will face each other team in the league twice, one home and one away game making it a total of 380 games a season. 

Given the growing trend on the application of machine learning on sports data, we here are going to build a random forest model to predict the match outcome of the English Premier League games. 

The questions We will target:

 Can we predict the number of goals correctly for any given team.



## File Descriptions <a name="files"></a>

1. 21-22pl.csv: contains match related data from all football matches from the current Premier League Season. (ENGL 1)
2. 20-21PL.csv: contains match related data from all football matches from the last Premier League Season. (ENGL 1)
3. 20-21CH.csv: contains match related data from all football matches from the last English FA Championship season. (ENGL 2) 
4. df_both_seasons_essentials: pickle file with results from load_and_clean.ipynb; contains clean and merged data from 21-22pl.csv, 20-21PL.csv and 20-21CH.csv
5. df_both_seasons_home.xlsx: goal prediction from home teams
6. df_both_seasons_away.xlsx: goal prediction from away teams


References
1. https://www.github.com/nichohelmut/bookie
2. https://www.github.com/Lisandro79/BeatTheBookie 
3. https://dashee87.github.io/football/python/predicting-football-results-with-statistical-modelling/
4. https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74
5. https://arxiv.org/pdf/1710.02824.pdf
6. https://towardsdatascience.com/random-forest-in-python-24d0893d51c0
7. https://towardsdatascience.com/improving-random-forest-in-python-part-1-893916666cd