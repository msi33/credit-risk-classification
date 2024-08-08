# credit-risk-classification

## Background

In this Challenge, I use various techniques to train and evaluate a model based on loan risk. I use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. The task is to divide the data into training and testing sets. Then use a Logistic Regression Model with the Original Data and then a Credit Risk Analysis Report


## Split the Data into Training and Testing Sets
The initial starter code notebook provided was used to accomplish this steps. First the lending_data.csv data from the Resources folder was read into a Pandas DataFrame. This was then followed by creating the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns. A value of 0 in the “loan_status” column was considered that the loan was healthy while a value of 1 meant that the loan had a high risk of defaulting. The data was then split into training and testing datasets by using train_test_split.


## Create a Logistic Regression Model with the Original Data
First a logistic regression model was fitted using the training data (X_train and y_train). This was then saved as the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model. The model performance was evaluated using a confusion matrix, printing of the classification report and then determine How well the logistic regression model predicted both the 0 (healthy loan) and 1 (high-risk loan) labels. 


## Write a Credit Risk Analysis Report
A brief report in response to question asked was written describing the confusion matrix results as well as classification report.






