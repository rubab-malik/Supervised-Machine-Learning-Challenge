# Supervised-Machine-Learning-Challenge
Import the data from 'lending_data.csv' using Pandas.

Make a prediction as to which model will perform better between Logistic Regression and Random Forests Classifier.

Create a feature DataFrame X by removing the 'loan_status' column and a label set y using the 'loan_status' column. Split the data into training and testing datasets using the train_test_split function.

Create a Logistic Regression model, fit it to the training data, and determine its score using the testing data. Repeat the process for a Random Forest Classifier, using any starting hyperparameters you like.

Compare the scores of both models and determine which one performed better. Compare your prediction with the actual result and write down your thoughts and results in a designated markdown cell.
## Write down your prediction in the designated cells in your Jupyter Notebook, and provide justification for your educated guess.
The data has seven features including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable is loan status, which is whether the loan was paid back or not.According to my understanding, the features and target variable may have complex relationships with each other, such as the borrower's income and debt-to-income ratio affecting the likelihood of loan default. There may also be interactions between features, like the relationship between loan size and interest rate. Due to these complexities, the random forest model may perform better than the logistic regression model, as it is better at handling complex relationships and interactions. However, the best way to determine which model performs better is to create, fit, and score both models on the specific data and compare their performance.
## Which model performed better? How does that compare to your prediction? Replace the text in this markdown cell with your answers to these questions.
The logistic regression model had a slightly better score of 0.9924680148576145 compared to 0.9921068922822947 for the Random Forest Classifier. This result is different from what I predicted, but it's important to consider that machine learning models' performance can depend on many factors, such as the data, features, and hyperparameters. The logistic regression model may have learned the relationship between the features and target variable better than the random forest model in this case, and it's essential to use appropriate evaluation metrics to choose the best model. Further analysis and experimentation are recommended to validate these results and find the optimal model for this problem.
