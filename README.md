# data_acquisition

Research Question of Interest: 
Is it better for NFL teams to invest more money on a WR1 (a top wide receiver) or an RB1 (a top running back)

Data pulled from overthecap.com looks at the WR and RB salaries from 2019-2025 . I used requests and beautiful soup to scrape the data from this website

Data was also pulled from pro football reference to help gather information about each team's success from the 2019-2025 seasons. This data includes W - total wins, L - total losses, T - tied games, win_pct - win percentage, win_loss_diff - win loss differential, PF - points scored by a team in a season, and lastly a year column to indicate the season.

The final dataset consists of the highest paid receiver and running back from each season, the team, season, how much their cap value was, how much money they were paid, their teams win percentage, differential, wins, losses, tied games, and points scored in that season.

This data can be used to see both how salaries differ for the leagues top running backs and wide receivers, as well as to determine whether a team should invest more in an elite running back or a elite wide receiver based of wins and points scored.

The repository consists of the code used to scrape data and read in downloaded csv files, as well as the cleaning and wrangling that was performed on the data to create the final data set, "nflWrRb_data.csv". The csv files were available to download on https://www.pro-football-reference.com/years/2025/index.html. These make up the season{year}.csv files in the repo. 

Exploratory Data Analysis was performed in the EDA.ipynb file.