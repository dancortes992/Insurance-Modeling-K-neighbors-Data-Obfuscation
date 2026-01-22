# Insurance-Modeling-K-neighbors-Data-Obfuscation
### Background

This project is part of the Tripleten data science practium. Focuses of the project is machine learning using K-neighbors algorithm and data obfuscation.

## Project Description

Objective of project is to develop an algorithm capable of finding similar costumers for marketing purposes. In addition to develop a model that can predict costumers most likely to recieve insurance along with how many benefits a costumer is likely to recieve.
Finally to protect client data by obfuscation without breaking the developed model.

## Data

Features available in our data consist of:
- Gender
- Age
- Income
- Family members
- Insurance benefits

**Models evaluated:** LinearRegression

## Findings

**KNN vs Dummy model:** Dummy model testing with different probabilities suggests a KNN clissifier can predict similar costumers better than dummy model based on F1 scores. Scaled data is to be used.

**Linear Regression with Obfuscated Data:** Testing shows linear regression model can be performed with obfuscated data without breaking model. Results show predictions using both original and obfuscated data match.

## Software

**Tools:** _python_, _jupyter_

**Libraries:** _NumPy_, _pandas_, _sklearn_
