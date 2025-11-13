# data_acquisition

Research Question of Interest: 
How much does money impact an NFL teams success? Are the highest paying teams consistently the best, even with a salary cap?

Data pulled from spotrac.com looks at team spending each of the last 7 seasons (2019-2025). 

Data was also pulled from pro football reference to help gather information about each team's success from the 2019-2025 seasons. This data includes W - total wins, L - total losses, T - tied games, win_pct - win percentage, win_loss_diff - win loss differential, PF - points scored by a team in a season, and lastly a year column to indicate the season.

The final dataset consists of salary totals from each season, the team, season, average age, how much the dead cap value was, how much the active roster was paid, team win percentage, differential, wins, losses, tied games, and points scored in that season.

This data can be used to see both how salaries differ for the leagues top running backs and wide receivers, as well as to determine whether a team should invest more in an elite running back or a elite wide receiver based of wins and points scored.

The repository consists of downloaded csv files from both websites, as well as the cleaning and wrangling that was performed on the data to create the final data set, "nfl_cap_data.csv". The csv files were available to download on https://www.pro-football-reference.com/years/2025/index.html. These make up the season{year}.csv files in the repo. 

Exploratory Data Analysis was performed in the EDA.ipynb file.