# MultipleLinearRegression

## Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

## The company wants to know the followings
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

## Technologies Used
* numpy
* pandas
* seaborn
* matplotlib
* sklearn
* statsmodels

# Final conclusions
*.The final varibales list are 'yr', 'holiday', 'temp', 'windspeed', 'season_summer', 'season_winter', 'mnth_Sep', 'weathersit_LightSnow', 'weathersit_Mist'
R2 and Adjusted R2Square are petty close to each other both in training and test data.
* Variables selected are having high significance and p-values are almost 0.
* Varibale multicolinerality has been reduced significantly.
* Removing now any varibales is causin R square to decrease hence thois proves the selected varibales are significant enough.
* Error terms are normally distributed.
* Error terms do not form any pattern.
* Pred vs expected as a MSE of 0.009 which is good.

##Contact
Created by [@ashwinkpes] - feel free to contact me!
