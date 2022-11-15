# House Price Prediction

Predicting house prices using Gradient Boosting Regressor

Firstly, we have made necessary imports.
Then we loaded dataset into a dataframe.
We are then dropping the columns which we are not using.

We then started with dataset refining.
We are checking whether there are any NA values present in our dataset.
Then, we are removing the irrelevant rows from the dataset like where sq. feet living area is more than sq. feet lot area.
A new column is added to dataframe which is showing the price of house in lakhs.
Then, we are visualising the different factors that are affecting the house prices.

For building a prediction model , we have used gradient boosting regression. It is giving the prediction score of 84.84%.
