# Bike Sharing - Linear Regression Assignment
> Building a Linear Regression Model for a Bike Sharing Company helping them in identifing factors driving bike rentals.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.

A US bike-sharing provider BoomBikes has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing covid lockdown comes to an end, and the economy restores to a healthy state.

BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.

Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demand

**Input Data** - Based on various meteorological surveys and people's styles, we are proided a large dataset on daily bike demands across the American market based on some factors.

## Conclusions
- Based on the linear regression analysis done on the data set we can see that for the training data adjusted R-square comes to be .811 which means that the model is able to explain 81.1% variance in target variable cnt.
- Using the same model for the test data set the adjusted R-square comes out to be .787 which is very close to .811 hence there is no overfitting present in the model.
- On plotting a histogram of the error values considering the final model, we can see that the error distribution is a normal distribution with a mean a 0. Hence, we validated the assumptions of the linear regression model.
- Looking at the coefficients of features selected in the final model we can see that these are the top 3 features contributing the most towards explaining the demand of shared bikes.
1. atemp – Demand goes up as the feels like temperature goes up.
2.	Year – The demand is increasing with time.
3.	Weather Situation – There is negative correlation between demand and weather indicating that if the weather is bad (e.g. Heavy Rain, Ice Pallets, etc.) the demand goes down.

## Technologies Used
* pandas
* numpy
* matplotlib
* seaborn
* sklearn
* statsmodels

## Contact
Created by [@singh-anshuman]