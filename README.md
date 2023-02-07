# supervised-machine-learning-challenge

During this project, I used lending data from lending services companies to create machine learning models to classify the risk level of given loans. Specifically, I compared the Logistic Regression model and the Random Forest Classifier. First, I retrieved the data, lending_data.csv by importing the data using Pandas. Next, I created and compared two models on this data: a Logistic Regression, and a Random Forests Classifier. Before I created, fit and scored the models, I made a prediction as to which model I thought would perform better. Next, I created the features DataFrame, X, by removing the loan_status column. Then, I created y, the labels set, by using the loan_status column. Then, I split the data into training and testing datasets by using the train_test_split function. Then, I created a Logistic Regression model and a Random Forest Classifier and fit these to the training data in the previous step. Next, I determined the model's score by using the score function and the testing data from the previous step.

# Resources

This folder contains lending_data.csv, the data that I imported using Pandas.
