# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: Start the program.

## Step 2: Import the necessary Python libraries for data processing and machine learning.

## Step 3: Read the data from a CSV file into a DataFrame for processing.

## Step 4: Separate the input (independent variables) and output (dependent variable) from the dataset.

## Step 5: Initialize a linear regression model from the machine learning library.

## Step 6: Fit the model using the input features and target to learn their relationship.

## Step 7: Retrieve and display the coefficients and intercept that the model has learned.

## Step 8: Use the trained model to predict the target value for a new set of input features.

## step 9: End the program.

## Program:
```
Program by: RAGA SUSANTH
Reg no: 212224230217
```
```
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[["Volume","Weight"]]
y=df[["CO2"]]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))
```
## Output:

![image](https://github.com/user-attachments/assets/3023a576-876a-45a5-b069-adcedee7c6c5)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
