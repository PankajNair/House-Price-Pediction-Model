# House-Price-Pediction-Model
## Problem Statement
A house is one of the biggest investments that most people make in their lifetime. Therefore, accurate predictions of house prices are essential for prospective buyers, sellers, and investors. A house price prediction model can be a valuable tool for these stakeholders. A house price prediction model can be used by homebuyers to determine when it may be best to purchase a home. By analyzing factors such as interest rates, employment rates, and housing supply and demand, these models can predict future house prices. This information can help potential buyers determine when they should purchase a home and whether they are getting a good deal. For home sellers, a house price prediction model can help them determine the best time to put their home on the market. By knowing when the market is likely to be strong, sellers can optimize their sale price and avoid waiting too long for the market to change.
## Data Information
We have used the California Housing Dataset which is available in sklearn.datasets().

The dataset contains various attributes of a house such as the number of bedrooms, age of the house, size and location.
## Project Pipeline
* Understanding the Data:  We load the data into a dataframe using Pandas and understand the features present in it. This helps in choosing the features that will be needed for the final model.
* Data Preprocessing: Data preprocessing is the essential step of cleaning and transforming raw data to make it suitable for machine learning models. As the current dataset is numerical and balanced, it can be used as is.
* Train/Test Split: The data is split into two sets: one for training the model and the other for testing its performance. We use the train_test_split function available in the sklearn library to perform the operation.
* Model Training and Evaluation: Here we can try different models until we get the desired level of performance on the given dataset. We use the XGBRegressor as our model available in the xgboost library. We also need to evaluate the models using appropriate evaluation metrics.
