# Statistical-Inference-on-Lyft-Fare-Price

## Summary
The primary objective of this statistical study is to measure the effects of time, temperature, weather,
distance of the ride, and surge multiplier on Lyft’s fare price. In other words, the goal is to identify the
statistically significant predictors for fare price. The secondary objective is to evaluate the impact of time,
temperature, weather, and destination on surge multiplier. The study began with Exploratory Data Analysis
(EDA) with the goal of checking the associations of predictor variables and the response variable, and
highlight the preliminary concerns based on the results of EDA. Through careful analysis of the results from
EDA, transformation of variables is performed and interactions are added to improve the fit of the model.
Next, stepwise selection method was implemented to identify the optimal model with the lowest AIC score.
To decide whether to drop predictors and/or interaction, F-test was implemented to assess the impact of
variables/interactions on the predictive model. Finally, model validation was performed to ensure the final
model fulfilled the linear regression assumptions, and there were no multicollinearity and influential points.
The outcome of the study shows that time, distance of the ride, and surge multiplier are significant predictors
for fare price. In addition, there is enough evidence to conclude that the association between surge multiplier
and fare price differs by rush hour and by destination.

Fore more details about the project, please refer to the [report]().
