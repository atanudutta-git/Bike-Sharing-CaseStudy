## BoomBikes BikeSharing Case Study

#### Problem Statement:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## The company wants to know
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Goal
- Develop a model to find the variables which are significant the demand for shared bikes with the available independent variables.
- It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## OLS Regression Results

|                    | Coef       | Std Err    | t           | P>|t|       | [0.025     | 0.975]     |
|--------------------|------------|------------|-------------|------------|------------|------------|
| const              | 2302.882   | 199.381    | 11.550      | 0.000      | 1911.158   | 2694.606   |
| year               | 2100.9047  | 82.511     | 25.462      | 0.000      | 1938.796   | 2263.013   |
| workingday         | 397.8633   | 111.886    | 3.556       | 0.000      | 178.041    | 617.686    |
| temp               | 3296.6004  | 232.367    | 14.187      | 0.000      | 2840.069   | 3753.132   |
| windspeed          | -1581.327  | 247.240    | -6.396      | 0.000      | -2067.080  | -1095.574  |
| season_spring      | -1226.8587 | 120.689    | -10.165     | 0.000      | -1463.976  | -989.742   |
| weekday_sat        | 493.2493   | 144.395    | 3.416       | 0.001      | 209.556    | 776.942    |
| weathersit_moderate| -567.0713  | 87.014     | -6.517      | 0.000      | -738.027   | -396.115   |

- **R-squared:** 0.779
- **Adj. R-squared:** 0.775
- **F-statistic:** 252.2
- **Prob (F-statistic):** 7.38e-160
- **Log-Likelihood:** -4202.8
- **AIC:** 8422.0
- **BIC:** 8456.0
- **Omnibus:** 112.748
- **Durbin-Watson:** 2.030
- **Prob(Omnibus):** 0.000
- **Jarque-Bera (JB):** 347.158
- **Skew:** -1.031
- **Prob(JB):** 4.13e-76
- **Kurtosis:** 6.477
- **Cond. No.:** 11.8

**Notes:**
- Standard Errors assume that the covariance matrix of the errors is correctly specified.
- VIF:
  - temp: 5.12
  - workingday: 4.21
  - windspeed: 3.82
  - year: 2.03
  - weekday_sat: 1.72
  - season_spring: 1.62
  - weathersit_moderate: 1.48


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.21.5
- pandas - version 1.4.4
- matplotlib - version 3.5.2
- seaborn - version 0.13.2.0
- summarytools - version 0.2.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by live session of upGrad & IIIT_B o
- EDA by [Atanu Dutta](https://www.linkedin.com/in/atanudutta/)

## Contact
Created by [@atanudutta-git](https://github.com/atanudutta-git/) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
