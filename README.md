# AutoMPG_Dashboard
An EDA and Multi-variate Regression Dashboard on the Auto-MPG dataset to predict fuel efficiency

This project essentially has two primary components - EDA(Exploratory Data Analysis) and simple linear regression, to predict the fuel efficiency of a particular vehicle, given various parameters like horsepower, number of cylinders, etc. Firstly, using the EDA we try to visualise the relationship between various variables using several types of graphs - scatterplots, box-and-whisker plots, violin plots, etc. Then, we move on to prediction, specifically regression and visualise a trendline. In addition, we can also compare results for various types of regression(Simple linear, Ridge, Lasso, XG Boost, ElasticNet).

The implementation has been primarily done in Python, using Scikit-Learn for prediction and Python Dash to create the dashboard and implement its components like graphs, dropdowns and so on. The Auto-MPG dataset [(https://archive.ics.uci.edu/dataset/9/auto+mpg)], containing information about various car models released in the United States between 1970 and 1982.
