# Boom Bikes Linear Regression Model
> Aim of this model is to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- A US bike-sharing provider BoomBikes recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. To accelerate it's revenue, once lockdown comes to an end, company wants to understand the demand of these shared bikes among people  
- They have collected large dataset on daily bike demands across the American market based on some factors. 
- We are trying to understand the behaviour of our independent variables on our dependent variable i.e., cnt (Total no of bike rentals)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- NumPy
- Pandas
- matplotlib.pyplot, seaborn
- sklearn
- statsmodels
- scipy


## Conclusions
- Variables that are significant in predicting demand for shared bikes are - 
    - hum
    - season 
        - Summer
        - Winter
    - workingday
        - Working
    - Weekday
        - Mon
    - weathersit
        - Light Rain
        - Mist
    - mnth
        - Jul
        - Sep
    - temp
    - windspeed
    - holiday
    - yr
        - 2019
- variable temp, Winter, 2019 has high coefficient value which means 
    - More people choose rental bikes when temperature is high
    - More people choose rental bikes during Winter
    - More poeple choose rental bikes during 2019
- variable hum, windspeed, Light Rain has high negative coefficients meaning 
    - Less People choose rental bikes during high windspeed
    - Less People choose rental bikes during light rain
    - Less People choose rental bikes during high humidity


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@mahchandra] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->