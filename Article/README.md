# ARTICLE

-INTRODUCTION

Basically, time series is a sequence of data points that are indexed and ordered chronologically over time. Time series data can be observed at regular or irregular intervals and can be collected over any time period, ranging from seconds to decades or even centuries. Time series data can be univariate (i.e., a single variable is recorded over time) or multivariate (i.e., multiple variables are recorded over time).Favorita Corporation is an Ecuadorian company that creates and invests in the commercial, industrial and real estate areas. Its subsidiaries have activities in six countries in the region, including Panama, Paraguay, Peru, Colombia, Costa Rica and Chile. They offer the best products, services and experiences in an efficient, sustainable and responsible way to improve the quality of life.




- OBJECTIVES

The objective of this analysis is to select the best prediction model from the different ML algorithms tested. This model will be the solution to be adopted by the company to help Favorita Corporation make insightful decisions in relation to their retail sales ,promotion and customer statisfaction.




- AIM

The aim of this project is to forecast the unit sales of the products across different stores. This is to optimize their inventory management , marketing strategies  and pricing  decisions. To achieve this results, we employed the use of time series in collaboration with different machine learning algorithms via the CRISP-DM framework.




# HYPOTHESIS

- Null Hypothesis:

Promotional activities have a significant impact on the store sales at Corporation Favorita.




- Alternate Hypothesis:

Promotional activities does not have a significant impact on the store sales at Corporation Favorita.




# HYPOTHESIS TESTING

In testing the hypothesis, we used the ordinary least squared regression analysis from the statmodel library in python to perform our hypothesis. it was inferred that;

- The OLS regression results indicate that promotional activities have a positive impact on sales, while certain types of days (Event, Holiday, Transfer, and Work Day) have a negative impact. The R-squared value of 0.175 suggests that 17.5% of the variance in sales can be explained by the independent variables.




- The R-squared value of the model is 0.223, meaning 22.3% of the variation in sales can be explained by the predictors. The coefficients for each predictor indicate how much the dependent variable is expected to change when the predictor changes by one unit. The model is statistically significant in predicting sales, with all three predictors having p-values less than 0.05 and a high F-statistic.Hence, our hypothesis is true. However, the condition number is large, suggesting further investigation is needed




## Questions

Q1. which city had the highest stores?

-- From the plot above, it can be catergorically inferred that, Quito recorded the highest, followed by Guayaqui.




Q2.which month did we have the highest?

-- from the visual, it was noticed that, The highest sale (per unit product sold) was recorded in April of 2016.




Q3.which store had the highest transaction?

-- the plot indicates that, store number 44 had the highest transactions.




Q4.which store had the highest sale?

-- obviously from the visualisation above, store number 44 again had the highest sales.




Q5.what is the most bought product per unit sale?

-- bread and bakery had the highest sales.




## Author

## RICHARD AUSBEL FIAGBEATI