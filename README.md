# Predicting-The-Success-of-Kickstarter-campaigns
Scraping Kickstarter and Google Trends to predict the success of crowdfunding campaigns. 

This project was conducted as follows:

First of all I scraped the features of crowdfunding campaigns from Kickstarter and Kicktraq (keeps information about archived projects of Kickstarter), which contains details about project itself and owner of the project.

Additionaly, using Google Trends I calculated the average number of google searches of campaign's category name in a period of project being live in Kickstarter. In that way I included a popularity factor in my analysis.

Using all the scraped data I showed how different factors affect the success of a project.

Second step was to construct machine learning models to predict the success of projects. Random Forest, XGBoost, Logistic Regression and Knn neighbrs models were applied with some iprovements. Parameter optimization tool was used(GridSearch) and models combined with PCA(Principal component analsis.)
