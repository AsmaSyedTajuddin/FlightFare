# FlightFare


<img width="867" alt="Screenshot 2022-07-18 at 03 33 10" src="https://user-images.githubusercontent.com/100385953/179433846-4a9c89d7-ea31-47d1-9892-90a297f4f86c.png">

Project Name: Flight Fare Prediction

using ML and Auto SK Learn(Auto ML)

In this project we will be predicting the Fare of a flight a person has to give on inputting the data using the normal Machine Learning techniques then we will see how we can do the same thing with the help of using Auto SK Learn which is a Auto ML Library.
Context :
We have often heared travellers saying Flight TIckets are often very unpredictable and are very hard to guess. If one might see a price today and checks the same flight price tommorow it's a whole different story by then.
Let us create a Machine Learning Model which will help us in predicting the prices of a flight on inputting some of the attributes. Here we will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities.
We will do the following things in our Notebook:

Data Analysis
Feature Engineering
Feature Selection
Model Building using ML
Modle Building using Auto SK Learn(Auto ML)


auto-sklearn
auto-sklearn is an automated machine learning toolkit and a drop-in replacement for a scikit-learn estimator:

import autosklearn.classification
cls = autosklearn.classification.AutoSklearnClassifier()
cls.fit(X_train, y_train)
predictions = cls.predict(X_test)
auto-sklearn frees a machine learning user from algorithm selection and hyperparameter tuning. It leverages recent advantages in Bayesian optimization, meta-learning and ensemble construction. Learn more about the technology behind auto-sklearn by reading our paper published at NeurIPS 2015 .

NEW: Auto-sklearn 2.0

Auto-sklearn 2.0 includes latest research on automatically configuring the AutoML system itself and contains a multitude of improvements which speed up the fitting the AutoML system.
auto-sklearn 2.0 works the same way as regular auto-sklearn and you can use it via

from autosklearn.experimental.askl2 import AutoSklearn2Classifier
