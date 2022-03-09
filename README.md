# House Price Prediction
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularization in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
 - Which variables are significant in predicting the price of a house, and
 - How well those variables describe the price of a house.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We have done Data cleaning, Exploratory data analysis and built different types of Model to get better insights of data and accuracy to predict.

Observation are as follows -
- Out of all the models we applied, **Lasso Regression** with alpha = 0.001, gave us the **best** and the **lowest** RMSLE value **0.1548**

- Hence based on Lasso, the factors that generally affect the price are the Physical locations within Ames city limits(`Neighborhood`), Overall quality and finishing of the house(`OverallQual`), Exterior covering on house(`Exterior1st`), on which year the house was built(`YearBuilt`).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.1.5
- Numpy - version 1.18.5
- Matplotlib - version 3.1.3
- Seaborn - version 0.10.1
- Scikit-learn - version 1.0.2
- Statsmodels - 0.11.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by Upgrad.


## Contact
Created by [@Ray0705](https://github.com/Ray0705) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
