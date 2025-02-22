# Bike demand prediction
> This project's purpose is to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


- **Business Goal**:
This project builds a model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- the dataset that is being used: day.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The following variables do affect the demand for bikes:
**Positive Effect**: workingday,atemp.
 - 2019 has seen more demand than 2018.
 - Following months will positive affect the demand: March,May, October, September
 - Sunday seems to have more demand compared other days.
 **Negative Effect**:hum,windspeed, spring season, Light weather (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds), Mist weather(Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist), July month
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- sklearn
- statsmodel api
- seaborn
- matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

## Contact
Created by [Mohak Pingle](https://github.com/mohakp) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->