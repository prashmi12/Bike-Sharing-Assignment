# Project Name : Rental Bike sharing assignment
> This is the case study for a basic understanding of we have to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Libraries Used in Python](#libraries-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements) 
* [Team Members](#teammembers)


## General Information <a name="general-information"></a>
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

The company want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

**Goal:**
We need to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

**We are going to solve the problem in 4 sections i.e. :**
- Data understanding and exploration
- Data Visualisation 
- Data preparation
- Model building and evaluation

## Libraries Used in Python <a name="libraries-used"></a>
- numpy 
- pandas
- matplotlib.pyplot
- seaborn 
- missingno
- sklearn
- statsmodels

## Conclusions <a name="conclusions"></a>
  **Assumptions of Linear Regression:**

* The error terms are normally distributed.
* The training and testing accuracy are nearly equal hence there is no Overfit/Underfit situation.
* The predicted values have linear relationship with the actual values.
* The distribution plot of error term shows the normal distribution with mean at Zero.

  **Major points:**
 - Following are the top 5 variables which is recomendeded to give utmost importance while planning to achieve maximum demand.
 
| Spring season| Temperature | Mist and Cloudy | Wednesday | Working day |
| --- | --- | --- | --- | --- |
| -0.684 | 0.400 | -0.365 | 0.275 | 0.233 |

  - From R-Sqaured and adj R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain more than 80% of bike demand.**

## Acknowledgements <a name="acknowledgements"></a>
- This project is given by Upgrad as an assignment case study
- All the data and requirements are provided by Upgrad.

## Team Members <a name="teammembers"></a>
Assignment done solely by Preity Rashmi
