# House_Price_Prediction
1. We start by importing the necessary libraries, including pandas for handling data, matplotlib for data visualization, and sklearn for the machine learning tasks.
2. We fetch the California housing dataset using the `fetch_california_housing()` function from `sklearn.datasets`.
3. The fetched data is converted into a pandas DataFrame for easier manipulation and analysis.
4. We split the data into training and testing sets using the `train_test_split()` function from `sklearn.model_selection`.
5. A Linear Regression model is built and trained using the `LinearRegression()` class from `sklearn.linear_model`.
6. We make predictions on the testing data using the trained model.
7. The mean squared error (MSE) is calculated using the `mean_squared_error()` function from `sklearn.metrics` to evaluate the model's performance.
8. Exploratory analysis graphs are plotted using matplotlib. In this case, we are plotting a scatter plot of actual vs. predicted prices.
9. Finally, an example prediction is made for a new set of data (`example_data`), and the result is printed as `example_prediction[0]`.
