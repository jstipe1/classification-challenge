# classification-challenge
Module_13_Challenge

__Purpose__: In this Challenge we use two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models to be used are logistic regression model and a random forest model.

  &nbsp; &nbsp; __Step 1__: Read in the designated data(https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv)  
  &nbsp; &nbsp; __Step 2__: Predict which of the two models will perform better  
  &nbsp; &nbsp;__Step 3__: Split the Data into Training and Testing Sets  
  &nbsp; &nbsp;__Step 4__: Scale the Features  
  &nbsp; &nbsp;__Step 5__: Create and score a Logistic Regression Model  
  &nbsp; &nbsp;__Step 6__: Create and score a Random Forest Model  
  &nbsp; &nbsp;__Step 7__: Evaluate the Models 

__Intalls__: A number of installations are needed (and provided) to run the code necessary to complete this project  
  
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression

[Python Documentation] (https://docs.python.org/)  
[Jupyter Notebook Documentation] (https://jupyter-notebook.readthedocs.io/)  
[sklearn Documentation]  (https://scikit-learn.org/0.21/documentation.html)

__Resources__:  
[Xpert Learning Assistance]  
[README.md formatting] (https://medium.com/analytics-vidhya/writing-github-readme-e593f278a796)  

