# House Price Prediction
Predicting house prices using Gradient Boosting Regressor

Firstly, we have made necessary imports.
Then we loaded dataset into a dataframe.
We are then dropping the columns which we are not using. We have dropped a total of 9 columns from the given 21 columns in the dataset.

After that, we started with dataset refining. For this step, first of all, we checked whether there is any NA values present in our dataset. As there are no values present, so there is no need to do anything in this case.

Then, we are removing the irrelevant rows from the dataset like where sq. feet living area is more than sq. feet lot area. Data entries with no. of bathrooms two more than no. of bedrooms is also removed since usually no. of bathrooms are not more than the no. of bedrooms. So we treated it as an outlier and removed all such data entries.
Next step is to add a new column to dataframe which is showing the price of house in lakhs. Another new column price_per_sqft is also introduced.
Then, we are visualising the different factors that are affecting the house prices using python libraries. 

Finally, we started with building a prediction model. We have kept 80% of data for training purpose and rest 20% for testing.
We have used gradient boosting regression. It is giving the prediction score of 98.12%.
