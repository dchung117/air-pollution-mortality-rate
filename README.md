# air-pollution-mortality-rate
Multiple linear regression analysis of air pollution and mortality rate data for 60 U.S. cities

Air pollution data for 60 cities in the United States from 1960 are collected. The dataset contains information on the total age-adjusted mortality rate (y), mean annual precipitation in inches (x1), median number of school years completed for those over 25 in 1960 SMSA (x2), percentage of urbanized area population that is nonwhite (x3), relative pollution potential of oxides of nitrogen (NOx) (x4), and relative pollution potential of sulfur dioxide (SO2) (x5).

The all-possible-regressions variable selection method was used to build a multiple linear regression model that predicted a city’s total age-adjusted mortality rate using the most significant air pollution regressors (annual precipitation, median number of completed school years, nonwhite percentage of population, and pollution potential of sulfur dioxide). 

Afterwards, the residual plots were examined to confirm that the data were in compliance with the regression model's linearity and normality assumptions. Logarithmic variable transformations were applied to two regressors (nonwhite percentage of population and pollution potential of sulfur dioxide) so that linearity assumption was satisfied. 

Two-fold cross-validation was conducted using the training set of air pollution data. The computed PRESS statistics conveyed the model's prediction accuracy of 57%.

### CONTENTS ###
