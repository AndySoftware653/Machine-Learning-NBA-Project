# Machine-Learning-NBA-Project

Group Members: Jian Nan (Andy) Huang, Mohammed Hasan

#Formulation:<br>
This code was written to predict the NBA average playoff scores. The average playoff scores were predicted given seasonal stats and knowing who will play in the playoffs. All data was taken from https://www.basketball-reference.com/.

#Approach:<br>
The approach used was multiple linear regression. We applied this method twice, once for predicting seasonal player stats, and once more for predicting the average playoff scores.<br>
Our chosen predictors for predicting seasonal player stats are:<br>
['FG','FGA','FG%','3P','3PA','3P%','2P','2PA','2P%','eFG%','FT','FTA','FT%','STL','MP','TOV','ORB','DRB','BLK','PF']<br>
Field Goals<br>
Field Goal Attempts<br>
Field Goal Percentage<br>
Three Pointers<br>
Three Point Attempts<br>
Three Point Percentage<br>
Two Pointers<br>
Two Point Attempts<br>
Two Point Percentage<br>
Effective Field Goal Percentage<br>
Free Throws<br>
Free Throw Attempts<br>
Free Throw Percentage<br>
Steals<br>
Minutes Played<br>
Turn Overs<br>
Offensive Rebounds<br>
Defensive Rebounds<br>
Blocks<br>
Personal Fouls<br>

Our target variables for seasonal player stats are:<br>
['PS/G','AST','TRB']<br>
Points per Game<br>
Assists<br>
Total Rebounds<br>

We found the team target variables by summing the target variables respectively for all the players in their respective playoff team. <br>
The sums are then used as training predictors, while the average playoff score is the target variable. 

Code:
https://github.com/AndySoftware653/Machine-Learning-NBA-Project/blob/master/NBA_ML_Project.ipynb

Report:



