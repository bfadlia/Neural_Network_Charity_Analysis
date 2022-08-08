# Neural_Network_Charity_Analysis

## Overview of the Analysis
The purpose of this machine learning analysis was to have a binary classifer that can predict ifr applicants will be successful if funded by Alphabet Soup charity.

## Results
1. What variable(s) are considered the target for your model?
The target for the model is the "Is-Successful" column. It indicates the money was use effectively.

2. What variable(s) are considered to be the features for your model?
The feature variables are the NAME, APPLICATION, TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT,SPECIAL_CONSIDERATIONS, STATUS, and ASK_AMT

3. What variable(s) are neither and should be removed from the input data? 
EIN , Name and USE_CASE were not useful for the model and were drtopped.

4. How many neurons, layers, and and activation functions did you select for your neural network model, and why?
- We made several attempts to improve the model. I started with two layers, first layer of 30 nodes and hidden layer of 20 nodes with relu activation function and sigmoid activation function in the output layer.
- Second attempt I added another hidden layer so the three layers had 80, 50 and 20 nodes.
- Third attempt changed the output activation function from sigmoid to tanh.
- Fourth attempt tried increasing both the number of nodes again and the number of epochs (100 epochs instead of 40)

5. Were you able to achieve the target model performance?
No. With all the attempts there was little improvement hovering between 70 and 72 percent accuracy.  We were not able to reach the 75% target

6. What steps did you take to try and increase model performance?
I covered this in question 4 above too.

## Summary

- This neural network model did not reach the target of 75% accuracy. It does not seem like the best model to get rliable results.
- Since this is a binary classification type of data, we suggest using a supervised machine learning model such as the Random Forest Classification which has an advantage of being less influenced by outliers so it may reach our target performance.
