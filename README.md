# Sports_betting
---

# Purpose

The purpose of this project is to scrape nba statistics for players and use this data to predict players future performance to therefore apply it to Draftkings Fantays sports betting consiting of picking 1 team captain and 5 additonal players for a single game.

# Extracting Data
---

Visits NBA game page and iterates through game data and extracts each players stats in each game and sends their data to a csv into their speicifc team folder 

![image](https://github.com/evanbruno617/Sports_betting/blob/main/images/Screenshot%202023-03-06%20at%204.29.21%20PM.png)

# Analysis
---

## Linear Regression
My first attempt at analyzing and predicting players future performance was using linear regression. By fitting each players scores from their previous games and creating a linear regression to predict their score for their next upcoming game. 

![image](https://github.com/evanbruno617/Sports_betting/blob/main/images/Screenshot%202023-03-06%20at%204.30.35%20PM.png)

After predicting their scores I exported it to a csv file which I will later use in creating the best team for the upcoming game. After graphing players scores over their previous games I realized it was hard to find a correlation with their performance as their scores varied wildly from game to game.

## LSTM
I then decided to try out a LSTM model in predicting players scores and using their past 3 games as the learning interval for the time series model. 

![image](https://github.com/evanbruno617/Sports_betting/blob/main/images/Screenshot%202023-04-15%20at%2010.41.33%20AM.png)

# Application
---

After predicting what the players' scores will be in the next game I next had to find the best combination of players to choose for the game given their preidcitons. 




