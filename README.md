# Beat-The-House

<b>IN PROGRESS</b>

looked at over 4000 regular season nfl games using python to clean, mine and feature engineer several factors relevant to the bookmakers' Over/Under line for each game as well as the spread

training a neural network on over 4500 games to estimate the total points scored based on both teams' points per game, oppositions points per game, as well as the O/U line with:
      - an MSE of 182.57, which is comparable to the bookmakers'
      - an MAE of 10.69, <b> yet to determine the percentage the model was able to correctly predict O/U outcomes </b> 
    
    
progessing towards training a similar neural network on a similar number of games to predict if the spread is covered (both winner and cover)


## Tools Used:

### Data Mining/Cleaning/Processing:
- Pandas
- NumPy
- BeautifulSoup

### ANN:
- keras
- scikit-learn

