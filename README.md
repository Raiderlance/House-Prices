# House-Prices Predictions
This project aims to identify key features influencing  sale price and develop a model to predict the sale price (class variable) of a house.
In this project, we used BORUTA to remove less important features and select the top features using random forest variable importance.
Subsquently, we split the data into train (80%) and test(20%) set and we trained the various machine learning models such as multi-linear regression, support vector machines and random forest to 
Then we test on the dataset.
Insight: Houses with larger garage area and larger total average area tend to fetch a higher price. E.g. When garage area increases by 3 times, the price will tend to rise by 3 times.

Source: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
