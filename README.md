# Beat-The-House

<b>IN PROGRESS</b>

looked at over 4000 regular season nfl games using python to clean, mine and feature engineer several factors relevant to the bookmakers' Over/Under line for each game as well as the spread such as pythagorean expected win percentage, win percentage upto that point as well as overall record and per game stats (offensive and defensive ppg)

training a neural network on over 4500 games worth of data (125,000+ data points) to estimate the total points scored based on both teams' points per game, oppositions points per game, as well as the O/U line with:

      - an MSE of 182.57, which is barely over to the bookmakers' of 182.23 (error of 0.58309 ppg compared to odds) 
      - an MAE of 10.69, yet to determine the percentage of games the model was able to correctly predict O/U outcomes on
    
    
progressing towards training a neural network on a similar number of games to predict if the spread is covered (both winner and cover)


## Tools Used:

### Data Cleaning/Mining/Processing:
- Pandas
- NumPy
- BeautifulSoup

### ANN:
- keras
- scikit-learn

