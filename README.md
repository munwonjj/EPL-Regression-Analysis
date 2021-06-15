# Market Value of English Premier League Soccer Player

Regression Project

## Goal 

The goal of this project is to use linear regression model to predict market value of a soccer player. Being albe to predict the market value of players is essential
for soccer clubs. The primary dataset that was used in this project was obtained using webscraping from [English Premier League](https://www.premierleague.com/). 
Seondary dataset which consists of market value of players comes from a site called [trasnfermarkt](https://www.transfermarkt.us/). After going through feature 
selection, converting categorical features to dummy variables, and using continous features, I tested out 3 different models: Linear Regression, Ridge Regression, and
Lasso Regression to determine my final model. The final model was the Ridge Regression which had R-squared value of 0.235 with MAE(Mean Absolute Value) error of 0.929.

## Work/Presentation

1. [Web Scraping - BeautifulSoup](https://github.com/munwonjj/EPL-Regression-Analysis/blob/master/All_Seasons.ipynb)
2. [EDA - Jointplot](https://github.com/munwonjj/EPL-Regression-Analysis/blob/master/updated_regression_mvp.pdf)
3. [Regression Modeling](https://github.com/munwonjj/EPL-Regression-Analysis/blob/master/regression_project.ipynb)
4. [Final PPT Presentation](https://github.com/munwonjj/EPL-Regression-Analysis/blob/master/Regression%20Modeling.pdf)

## Tools

* Web Scraping(BeautifulSoup, Selenium)
* Python(Pandas, Numpy)
* Seaborn, Matplotlib for data visualization
* scikitlearn, statsmodel
