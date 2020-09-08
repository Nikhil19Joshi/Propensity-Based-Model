# Propensity-Based-Model
## Purchase Propensity Modelling

This project is an attempt to build a Purchase propensity based model using UCI data set. Perform Exploratory data analysis on the data, clean the data, balance the dataset and divide the dataset into test and train. Finally, apply different classification algorithms on test and train to come up with the best classification algorithm for our use case.

## Dataset Link:
http://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset# 

## Classification Algorithms
In our project we have used 5 classification algorithms:
1) Logistic Regression CV (AUC: 89.93% , Recall: 58.36%)
2) Support Vector Classifier (AUC: 83.03% , Recall: 27.32%)
3) Random Forest (AUC: 91.77% , Recall: 57.29%)
4) **Gradient Boosting (AUC: 98.88% , Recall: 91.09%)**
5) Extreme Gradient Boosting (AUC: 97.77%, Recall: 87.98%)

As we can see from above Gradient Boosting algorithm has given us the best results and we have used this Algorithm for our model to predict the propensity of our customers.

## Web Application
I have created a web Application on flask for which I have considered Gradient Boosting Algorithm as the primary model at the backend to perform the prediction. Code for the web application can be found in the folder Web_Interface_Code. Below is the screenshot of the UI of the web application.


