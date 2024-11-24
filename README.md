# Project Name
> This project aims to develop a predictive model to forecast the demand for shared bikes in the American market, focusing on key factors that influence bike usage. BoomBikes, a leading bike-sharing provider, has faced challenges due to the ongoing pandemic and seeks to leverage data to understand shifting customer needs. By analyzing historical usage data, this project will identify important variables such as weather, temperature, day of the week, and season that impact bike demand.

Using linear regression, the project will explore how these factors affect demand fluctuations and help predict future trends. The insights gained will enable BoomBikes to optimize operations, adjust fleet distribution, refine pricing strategies, and tailor marketing efforts to align with expected demand.

Ultimately, the goal is to provide BoomBikes with a data-driven approach to better anticipate demand, enhance customer satisfaction, and improve operational efficiency. By understanding these demand dynamics, BoomBikes can strengthen its position in the competitive bike-sharing market as the economy recovers.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)


## General Information
- This project aims to model and predict the demand for shared bikes in the American market using various factors such as weather, temperature, and day of the week. The goal is to understand how these variables influence bike usage and help BoomBikes optimize its operations post-pandemic.
- BoomBikes, a bike-sharing provider in the US, has faced a significant decline in revenue due to the COVID-19 pandemic. The company aims to develop a strategy to forecast bike demand as the economy recovers, ensuring it can meet customer needs effectively.
- The business problem being addressed is predicting the demand for shared bikes in a post-pandemic market. The goal is to help BoomBikes adapt its strategies based on demand fluctuations, optimize operations, and increase profitability as the economy stabilizes.
- The dataset being used contains daily bike demand data across the American market, influenced by various factors such as weather, temperature, and people's behavior patterns. This data will be analyzed to model and predict future bike demand.


## Conclusions
- The features used in the prediction of the target variable cnt (bike bookings) are:
yr, temp, Jul, Sep, Sun, misty/cloudy, snow/rain/thunderstorm, spring, summer, winter

- As per the absolute values of the coefficients or weights of the linear regression model, the top 3 features contributing significantly towards the demand of shared bikes are as follows:

1. temp : A one-unit increase in temp leads to 0.5044 increase in bike bookings. This suggests that warmer weather significantly drives bike demand.

2. yr : A unit increase in yr variable increases the bike hirings by 0.2328 units. This reflects a rising trend in demand over time, indicating business growth.


3. snow/rain/thunderstorm: : A unit increase in snow/rain/thunderstorm decreases bike bookings by 0.3004 units. This indicates that adverse weather conditions negatively impact bike demand.

The analysis reveals that bike demand is mainly positively influenced by warmer temperatures and an increasing trend over the years, while adverse weather conditions (snow/rain/thunderstorm) tend to decrease bike bookings. Besides, other factors like Sun, Jul, Sep, misty/cloudy, spring, summer, winter also influence bike booking demands.






## Technologies Used
- pandas version: 2.2.2
- numpy version: 1.26.4
- matplotlib version: 3.8.0
- seaborn version: 0.13.2
- scikit-learn version: 1.5.2
- statsmodels version: 0.14.4



## Contact
Created by Anusha Chaudhuri [@anusha761]


