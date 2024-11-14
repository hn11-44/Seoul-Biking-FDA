# Summary

Functional data analysis (FDA) is a statistical framework that enables us to convert discretely
measured count of bike rented and weather conditions for the city of Seoul into functional curves
in a manner that breaks away from the conventional multivariate statistic analysis. Our aim is to
predict bike rental demand given the weather condition and the different seasons that are observed
within the city. In this paper we cover the foundational concept of smoothing, smoothing with a
roughness penalization, derivatives of our functional curves, and automatic data registration with
phase variation through the time warping method and functional principal component analysis. After
pre-processing our functional curves we conduct functional regression on our aligned and unaligned
curves to compare the results. Results from scalar on function regression indicate that the unaligned
model without contstant performs better than the rest in terms of the R2, RMSE with a significant F-
ratio. Subsequently we conducted a FPCA on the best performing model and inspected the confidence
interval. Findings inidicate that most of the covariates confidence interval band includes zero, except
for solar, rainfall and winspeed for certain hours of the day. Moreover, we have conducted FANOVA
by taking the different seasons that occur in a year. We have evaluated the confidence interval of the
regression estimates and determined the pointwise F-test to deterimine that our observed statistic is
significant for all of the hours of the day. Our last analysis consisted of a pointwise t-test between
two seasons, namely Winter and Summer. Results of observed statistic is above our critical value
deeming the difference statistcially significant for all of the hours of the day.


# Files 

FDA_final.html -> contains R markdown code in hmtl format

FDA_final.RMD -> conatins code 

Function Data Analysis Report -> report including methodology and discussion or results 

Seoul Bike Rentals Presentation -> a canva presentation of the project 

SeoulBikeData.csv -> the data used for the project. 


