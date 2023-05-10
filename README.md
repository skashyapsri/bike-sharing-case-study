# Bike Sharing Case Study
> BoomBikes is a US bike-sharing provider. They use a bike share system which allows people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock of BoomBikes.


## Table of Contents
- [Bike Sharing Case Study](#bike-sharing-case-study)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Problem statement](#problem-statement)
  - [Conclusions](#conclusions)
  - [Final model from linear regression](#final-model-from-linear-regression)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)


## General Information
### Problem statement
> BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. It has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end.
> The company wants to know:

> - Which variables are significant in predicting the demand for shared bikes.
> - How well those variables describe the bike demands


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Based on the model, the sales of bikes are influenced by different variables, each with varying levels of impact.

- yr: With a coefficient of 0.233233, a one-unit increase in the year leads to a corresponding increase of 0.233233 units in the dependent variable (unit sales of bikes).
- holiday: The coefficient for this variable is -0.084826, indicating that on holidays, the dependent variable decreases by 0.084826 units, assuming all other factors remain constant.
- temp: The coefficient of 0.546436 indicates that a one-unit rise in temperature results in a 0.546436 unit increase in the dependent variable.
- windspeed: A coefficient of -0.142707 suggests that a one-unit increase in windspeed leads to a decrease of 0.142707 units in the dependent variable.
- season_2: The coefficient of 0.090521 implies that during season 2, the dependent variable increases by 0.090521 units compared to other seasons, assuming all other factors remain constant.
- season_4: With a coefficient of 0.131612, season 4 contributes to a 0.131612 unit increase in the dependent variable compared to other seasons, assuming all else remains equal.
- mnth_8: The coefficient of 0.039352 indicates that in August, the dependent variable increases by 0.039352 units compared to other months, assuming all other factors remain constant.
- mnth_9: A coefficient of 0.100173 suggests that in September, the dependent variable increases by 0.100173 units compared to other months, assuming all other factors remain constant.
- weathersit_3: With a coefficient of -0.251998, the dependent variable decreases by 0.251998 units during bad weather (weathersit_3) compared to good weather (weathersit_1), assuming all other factors remain constant.


## Final model from linear regression
> - total_bookings(cnt) = 0.0750 + 0.2331 * (year) + 0.0561 * (workingday) + 0.5499 * (temp) - 0.1552 * (windspeed) + 0.0886 * (season_summer) + 0.1307 * (season_winter) -0.0800 * (weathersit_2) - 0.2871 * (weatthersit_3) + 0.0974 * (mnth_sep) + 0.0675 * (weekend_6)



## Technologies Used
- Jupyter notebook - version 6.4.12
- Python - version 3.10.0
- Pandas - version 2.0
- Numpy - version 1.24.2
- Matplotlib.pyplot - version - 3.7.1
- seaborn - version - 0.12.2
- statsmodel - version - 0.14.0
- sklearn - version - 1.2.2

## Acknowledgements
- Upgrad


## Contact
Created by [@skashyapsri] - feel free to contact me!