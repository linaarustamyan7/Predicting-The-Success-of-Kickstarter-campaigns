# Predicting-The-Success-of-Kickstarter-campaigns
Scraping Kickstarter and Google Trends to predict the success of crowdfunding campaigns.

This project was conducted as follows:

First of all I scraped the features of crowdfunding campaigns from three main webpages and combined them for further analysis (project profile page in Kickstarter, project profile page in Kicktraq and creator's profile page). For that purpose, I mainly used scrapy, pandas and regex libraries in Python.

Additionaly, using Google Trends (pytrends library) I calculated the average number of google searches of campaign's category name made in a period of project being live in Kickstarter. In that way I included a popularity factor in my analysis.

Using all the scraped data I showed how different factors affect the success of a project (by using different visualisation tools) .

Next step was to construct machine learning models to predict the success of projects. Random Forest, XGBoost, Logistic Regression and kNN neighbors models were applied with some improvements. Parameter optimization tool was used(GridSearch) and models combined with PCA(Principal component analysis).
