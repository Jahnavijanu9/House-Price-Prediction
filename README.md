# House-Price-Prediction
Predicting the price of the houses using the dataset from kaggle.com
House Price Prediction Using Linear Regression 🏠📊
Project Overview
This project aims to predict house prices using a linear regression model. By analyzing various features like square footage, number of bedrooms, and bathrooms, we can estimate the sale price of houses. The project demonstrates the complete data science pipeline, from data preprocessing to model evaluation and prediction.
Dataset
The project utilizes the Ames Housing dataset, which includes detailed information on various house features. The dataset is split into two files:

train.csv: Contains the training data with house features and corresponding sale prices.
test.csv: Contains the test data with house features (without sale prices).
Features
The following features were selected to train the model:

GrLivArea: Above ground living area in square feet.
BedroomAbvGr: Number of bedrooms above ground.
FullBath: Number of full bathrooms above ground.
Steps Involved
Data Preprocessing:

Handled missing values by imputing the median for numerical columns (LotFrontage) and the mode for categorical columns (MSZoning, SaleType).
Scaled the features using StandardScaler to ensure consistent model performance.
Model Training:

Split the training data into training and validation sets.
Trained a linear regression model using the selected features.
Model Evaluation:

Evaluated the model on the validation set using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared metrics.
Prediction:

Made predictions on the test data and added the predicted prices to the test dataset.
