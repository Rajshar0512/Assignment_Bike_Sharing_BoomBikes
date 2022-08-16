# Business Solution for a Bike Sharing Company, BoomBikes
> This is a programming assignment wherein we have built a multiple linear regression model for the prediction of demand for shared bikes - BoomBikes. BoomBikes aspires to understand the demand for shared bikes among the people after the ongoing quarantine situation ends across the nation due to Covid-19.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This is a programming assignment wherein we have built a multiple linear regression model for the prediction of demand for shared bikes - BoomBikes. BoomBikes aspires to understand the demand for shared bikes among the people after the ongoing quarantine situation ends across the nation due to Covid-19.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
- BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
a. Which variables are significant in predicting the demand for shared bikes.
b. How well those variables describe the bike demands
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
Jupyter

## Conclusions
As per the final model, the top 5 predictor variables that influences bike booking are:

Temperature (Temp)
A coefficient value of ‘0.5499’ indicated that a temperature has significant impact on bike rentals
Light Rain & Snow (weathersit =3)
A coefficient value of ‘-0.2871 indicated that the light snow and rain deters people from renting out bikes
Year (yr)
A coefficient value of ‘0.2331’ indicated that a year wise the rental numbers are increasing
It is recommended to give utmost importance to these three variables while planning to achieve maximum bike rental booking.
As high temperature and good weather positively impacts bike rentals, it is recommended that bike availability and promotions to be increased during summer months to further increase bike rentals.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- matplotlib.pyplot
- seaborn
- sklearn.model_selection
- sklearn.preprocessing
- sklearn.feature_selection
- sklearn.linear_model
- statsmodels.api
- statsmodels.stats.outliers_influence
- sklearn.metrics

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@Rajshar0512] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->