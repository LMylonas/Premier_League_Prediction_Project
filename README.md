# Premier League Prediction Project Overview

The purpose of this project is to predict the winner of football matches in the English Premier League using machine learning.

#### Project Steps

* Scrape match data for several seasons using Requests, Pandas & BeautifulSoup.
* Prepare and clean the data for machine learning using Pandas.
* Make predictions about match winners using Scikit-learn.
* Measure the precision of our predictions and improve by creating more predictors and retraining the model.

## File Overview

* `scraping.ipynb` - a Jupyter notebook that scrapes our data from [FBref](https://fbref.com/en/).
* `prediction.ipynb` - a Jupyter notebook that train the model and makes predictions.
* `matches.csv` - the output of our scraped data for the 21/22, 22/23 seasons of the English Premier League.
