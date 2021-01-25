# Regression Project
# Predicting Total Movie Grosses 

#### OBJECTIVE:
Build a regression model to predict movie theater grosses throughout the calendar year.

#### APPROACH:
The target data is the total gross revenue for movies released in movie theaters. The features used in the model were the monthly movie gross, the number of theaters the movie was released in, the release month, and the release year. After the test-train split of the data, Linear, LASSO, and Ridge regression models were performed and evaluated. Standard scaling was also applied to the data to further examine the eval metricis: R2, MSE and MAE values.


#### FEATURED TECHNIQUES:
- BeautifulSoup web scraping
- Feature Engineering
- Standard Scaling
- Linear Regression
- LASSO Regression
- Ridge Regression
- Ridge Cross Validation

#### DATA:
All data from roughly 3,000 movies was scrapped from [Box Office Mojo](https://www.boxofficemojo.com/month/?grossesOption=calendarGrosses) for the years 2019-2020.

#### TOOLS:
BeautifulSoup, Seaborn, Matplotlib, SkLearn, Numpy, Pandas

#### RESULTS SUMMARY:
The model with the best predictive results for total movie gross was a simple linear regression model. The final features used in getting the best predictive model for this target were monthly movie gross, the number of theaters the movie was released in, the release month, and the release year. This final model was evaluated baed upon on the results of R2, MSE and MAE values. The resulting values are: R2 =.50, MSE = .97, and MAE = .37

Possible impacts of these results would allow movie producers to make more informed decisions on how to maximize their total movie gross. However, this model is limited and further feature engineering is needed to produce an even more accurate model. Adding additional features and iteraction terms would be helpful, and more regressions (such as polynomial regresion) would greatly improve prediction accuracy. 
