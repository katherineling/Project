# Project

For my final Ironhack project, I worked on a Data Science competition that Zillow hosted a few years back. 

In this competition, Zillow asks to predict the log-error between their Zestimate and the actual sale price, given all the features of a home. The idea is to try to create an algorithm that will beat their home prediction algorithm (the Zestimate).

The log error is defined as:

logerror=log(Zestimate)−log(SalePrice)

Zillow provides the datasets, and the logerror data is provided in the transactions file "train.csv". 

The competition was hosted on Kaggle:

https://www.kaggle.com/c/zillow-prize-1/data

I merged the training dataset together with the "properties" dataset (which contains data on several characteristics of a home) in order to do exploratory data analysis, data cleaning, and model building.

As this was a supervised, numerical regression machine learning problem, I used the linear regression, KKN, and random forest models to try to build my algorithm. I used SQL to merge the datasets, and Python to conduct the exploratory data analysis, data cleaning, and algorithm building.    

 
