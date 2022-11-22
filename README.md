# Credit Card Fraud Detection using Machine Learning
The challenge is to recognize fraudulent credit card transactions so that the customers of credit card companies are not charged for items that they did not purchase

## How Frauds are recognized
- Location- Purchase made from different location
- Items you buy- If you deviate from your regular buying pattern or time
- Frequency- Make a large number of transactions in short time
- Amount- Suddenly if the costly items are purchased

## Main Challenges Involved In Credit Card Fraud Detection

- Enormous Data is processed every day and the model build must be fast enough to respond to the scam in time
- Imbalanced Data i.e most of the transactions (99.8%) are not fraudulent which makes it really hard for detecting the fraudulent ones
- Data availability as the data is mostly private
- Misclassified Data can be another major issue, as not every fraudulent transaction is caught and reported
- Adaptive techniques used against the model by the scammers

## PROJECT WORKFLOW
- Importing all the necessary Libraries
- Exploratory Data Analysis
- Splitting the data into train and test data
- Model Building
  - Logistic Regression
- Hyperparameter Tuning
- Conclusion & Result

## EXPLORATORY DATA ANALYSIS
- Loading the Data
- Understanding the Data
- Handling the Imbalance in the Data
 - Only 0.17% fraudulent transaction out all the transactions. 
 - The data is highly Unbalanced.
- Training and Testing Data Bifurcation

## Logistic Regression Classifier

- Logistic Regression is a statistical method for analysing a dataset in which there are one or more independent variables that determine an outcome. The outcome is measured with a dichotomous variable, where there are only two possible outcomes
- The goal of logistic regression is to find the best fitting model to describe the relationship between the dichotomous characteristic of interest, and a set of independent variables
- Logistic Regression generates the coefficients of a formula to predict a Logit Transformation of the probability of presence of the characteristic of interest

## Conclusion
- The highly imbalanced dataset is sampled in a hybrid approach where the positive class is oversampled and the negative class under-sampled, achieving two sets of data distributions
- The highly imbalanced dataset is sampled in a hybrid approach where the positive class is oversampled and the negative class under-sampled, achieving two sets of data distributions
 


