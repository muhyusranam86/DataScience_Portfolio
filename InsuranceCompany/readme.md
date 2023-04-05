# Project Description:
The Sure Tomorrow insurance company wants to solve several tasks with the help of Machine Learning.

## Project Goals
* Find customers who are similar to a given customer. This will help the company's agents with marketing.
* Predict whether a new customer is likely to receive an insurance benefit. Can a prediction model do better than a dummy model?
* Predict the number of insurance benefits a new customer is likely to receive using a linear regression model.
* Protect clients' personal data without breaking the model from the previous task.

## Data Obfuscation
Develop a data transformation algorithm that would make it hard to recover personal information if the data fell into the wrong hands. 
This is called data masking, or data obfuscation. But the data should be protected in such a way that the quality of machine learning models doesn't suffer. 
You don't need to pick the best model, just prove that the algorithm works correctly.

## Data Description
Features: insured person's gender, age, salary, and number of family members.
Target: number of insurance benefits received by the insured person over the last five years

## Libraries Used
* Pandas
* Matplotlib.pyplot
* numpy
* sklearn

## Models Evaluated
* LinearRegression
* KNearestNeighbhors
