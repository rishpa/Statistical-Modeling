# Statistical-Modeling
R Studio exercise on statistical modeling


Exercise 1
An environmental protection agency is mapping air quality across a large European region. The researchers
collect annual average data from n= 45 different urban and suburban monitoring stations. For each station,
they record the average concentration of two distinct pollutants: Nitrogen Dioxide (NO2) and Particulate
Matter (PM10). Both are measured in µg/m^3.

1. Calculate the main descriptive statistics for NO2 and PM10 concentrations, and provide a brief
interpretation of the results, explicitly taking into account the application context.
2. Provide the quantile-quantile (Q-Q) plot for the PM10 variable. Based on the visual inspection of this
plot, discuss whether the assumption of normality is plausible for this pollutant.
3. Present the data using a scatterplot and discuss the direction and strength of the association between
NO2 and PM10 concentrations across monitoring stations. Then, compute the point estimate of the
linear correlation coefficient to quantify this association.
4. Apply the nonparametric bootstrap method using B = 2000 replications to estimate the standard error
of the correlation coefficient. Then, comment on the magnitude of the standard error relative to the
point estimate.
5. Compute a 90% confidence interval for the correlation coefficient using the bootstrap quantile method.
Then, comment on the result.
6. Display the histogram of the bootstrap distribution of the correlation coefficient, including vertical lines
for the original sample estimate, the mean of the bootstrap replications, and the confidence interval
bounds. Provide an appropriate legend and an interpretation of the plot.
