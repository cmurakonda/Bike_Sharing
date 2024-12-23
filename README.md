# Bike Sharing
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Problem Statement 
- You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Conclusion 1
Univariate Analysis inidcates on numerical variables,

Windspeed has outliers. Should we remove outliers? Univariate Analysis of categorical data indicates,
Holiday
Majority of bike hires are on holidays
This information matches with Working day or Not working day
Season, Month, Week
Consistent bike rents across season, month and week.
Weather Situation
Less bike hires on snowy or rainy days.
###  Conclusion 2
Bivariate & Multicollinearity Analysis indicates,

Temp and atemp are highly correlated.
Bike hires count is more on holidays compared to non-holidays.
Bike hires are uniform across all week days.
Weather situation impacts bike hires. Bad weather has less hires.
### Conclusion 3
The Linear regression model indicates demand for bikes is highly dependent on variables such as year, temperature and weather situation.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.10.11
- pandas 2.1.0
- numpy 1.24.2
- matplotlib 3.7.2
- seaborn 0.13.2
- sklearn 1.4.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by Upgrad Assignment 
- With Support from Dinesh J Babu , Associate Professor, IIIT-B


## Contact
Created by [@cmurakonda](https://github.com/cmurakonda/) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->