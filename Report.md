## Credit Overview Report
Lending institutions access whether an individual can repay a loan or the asset which is being lent. Credit risk is used by institutions to evaluate whether an individual (the borrower) can repay the money or asset over an agreed period. Machine learning can be used to analyse a dataset to evaluate weather there is a trench which can be used to inform the decision.

The purpose of this credit risk classification assessment is to use machine learning models to train and evaluate loan risks. The dataset contains historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The data set contained the following information:
- Loan size
- Interest size
- Borrower income
- Number of accounts
- Dergatory marks
- Total debt
- Loan status

This assessment will use machine learning to determine whether loan applicants are low-risk or high-risk. In order to determine which catagory loan appliants fall into a logistic regression algorithm is used.

The following processes were used:
- Split the data into training and testing datasets.
- Fit a logistic regression model by using the training data.
- Fit a logistic regression model by using the training data and fitted model.
- Evaluate the model’s performance: 
  - Generate a confusion matrix.
  - Generate a classification report.
  - Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Logistic Regression Model using the training data

 precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
    macro avg       0.92      0.95      0.94     19384
    weighted avg       0.99      0.99      0.99     19384

## Summary

The results indicate that linear regression model provides an accuracy of 95% which is acceptable for this analyses. The high risk loan accuracy may increase if more data was avaliable for this high risk loans.
