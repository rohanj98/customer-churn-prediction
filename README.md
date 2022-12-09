# Customer-Churn-Prediction

*Churn* is when customers stop using the services of a company. Thus, churn prediction is about identifying customers who are likely to cancel their contracts soon so that we can offer discounts on these services in an effort to keep the users.

This is a binary classification problem. The target variable that we want to predict is categorical and has only two possible outcomes: churn or not churn.

The plan for the project follows:
1. First, we download the dataset and do some initial preparation: rename columns and change values inside columns to be consistent throughout the entire dataset.
2. Then we split the data into train, validation, and test so we can validate our models.
3. As part of the initial data analysis, we look at feature importance to identify which features are important in our data.
4. We transform categorical variables into numeric variables so we can use them in the model.
5. Finally, we train a logistic regression model.
6. Use Pickle to save and load the model
7. Serve [churn model](https://github.com/rohanj98/customer-churn-prediction/blob/main/churn_serving.py) using Flask
8. To manage python library dependencies, use `pipenv` file. 
9. Use `docker` to manage OS dependencies.

A walkthrough notebook for the project can be found [here](https://github.com/rohanj98/customer-churn-prediction/blob/main/churn-prediction.ipynb)

