# Project 2 Code Review

## TA: Chris Doenlen

## Code review notes

* Scraping: WCD_Leg_Scraper.ipynb contains mostly functions to help scrape - consider moving this to a separate .py file import into your notebook to scrape
* Repo organization -- I'd like to see more of a write-up in the readme - a few examples: 
  * an introduction
  * sources & references
  * Results -- what are key findings? Impacts? 
* EDA 
  * Overall very light on content with little explanation of what we're looking at
  * Used excel to get season averages - would like to have seen this done with python and showning more of the data cleaning process
* Charts notebook -- would have liked to have seen more exploration of the data through different charts/visualizations. Histograms are certainly helpful, but maybe some relations to other features? 
* Regresssion
  * R2 scores are good, but we should compare training and validation scores together to see whether or not the model is under/over-fitting
  * Would have liked more of a write up to understand the thought process between changing models and implementing regularization 
  * Which model is the best? 
  * What are some other metrics which might make this model's results more interpretable? MAE? RMSE? How should we think about these? 
  * Would have liked exploration of residuals and other visualations of results
