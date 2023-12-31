# Credit-Risk-Classification Report

## Overview of Analysis

  - The purpose of this analysis is to build a model in order to determine the creditworthiness of borrowers.
  - The financial information the data is based on is from historical lending activity from a peer to peer lending services company.
  - The dependent variable used in this model (y_value) was the 'loan_status' which indicated if the loan is healthy or at risk.
  - The independent variables used in this model (x_values) were the 'loan_size', 'interest_rate', 'borrower_income', 'debt_to_income_ratio', 'number_of_accounts', and 'derogatory_marks'.
  - In this analysis, we first separated the y_value and the x_values. Then we split the data into training and test sets. Then we created a logistic regression model and fit our original data to the model we created. Then we used the trained model to create predictions of our data set. Lastly we evaluated the model's performance using the balanced accuracy score, precision, recall, and accuracy.
  - In this analysis I created two different logistic regression models. One was created using the original data and the other was created using randomly oversampled data. This is so we could get rid of any imbalances in the data and then we compared the first logistic regression model to the second logistic regression model.

## Results

  - Logistic Regression Model Created with Original Data

    <img width="377" alt="Screenshot 2023-07-26 at 5 17 24 PM" src="https://github.com/jgillas/Credit-Risk-Classification/assets/125215083/04c2ccd1-08d7-436e-8aa6-bddac2c388c4">

    <img width="476" alt="Screenshot 2023-07-26 at 5 18 47 PM" src="https://github.com/jgillas/Credit-Risk-Classification/assets/125215083/7b71ab6c-65b1-4ef4-91c6-ad52459c78b3">

  - Logistic Regression Model Created with Randomly Oversampled Data

    <img width="374" alt="Screenshot 2023-07-26 at 5 21 02 PM" src="https://github.com/jgillas/Credit-Risk-Classification/assets/125215083/a20af522-3b21-4cf1-be7c-d58d82c8a745">

    <img width="474" alt="Screenshot 2023-07-26 at 5 22 53 PM" src="https://github.com/jgillas/Credit-Risk-Classification/assets/125215083/00e591e0-1566-49b1-9751-29c0dffbee26">

## Summary 

In summary the model created with the randomly oversampled data increases the balanced accuracy score. This means that it helps to improve on the model created with the original data. The increase in the balanced accuracy score means it can help to better predict the true positives. That means that it is better at finding the high risk loans and it also helps with a high recall accuraccy. 

Both models have high accuracy which means that both models are good at correctly predicting high risk loans and healthy loans. 

Both models also have a high precision score which means that both models are good at telling which loans are really hgih risk ones and which ones are healthy. It means that the models have a low rate of producing false positives. 

Both models also have a high recall score which means that both models are good giving a comprehensive output about the high risk loans and the healthy loans. Having a high recall score means there is a low chance of a false negative result. 

Overall, both these models are good at telling which loans are high risk loans and which ones are healthy loans. The model created with randomly oversampled data builds on the first model created with the original data. 
