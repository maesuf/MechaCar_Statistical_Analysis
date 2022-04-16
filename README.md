# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
* Vehicle Length and the Ground Clearance provided a non-random amount of variance to the mpg values in the dataset
* The slope of the linear model is not zero because the p-value is 5.35x10-11. Therefore, we have to reject the null hypothesis
* The model does predict prototypes effectively to 71% accuracy based on the R-squared value of 0.7149<img width="590" alt="Screen Shot 2022-04-15 at 8 24 01 PM" src="https://user-images.githubusercontent.com/97330455/163661445-ca865053-137c-4758-af6c-c18f9a191474.png">

## Summary Statistics on Suspension Coil
* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. 
* The overall variance is under 100 psi and meets  the design specifications. However, Lot 3 exceeds the variance of 170.28.

## T-Tests on Suspension Coils
* The T-test for the suspension coils for all three lots show that there is no statistical difference from the mean, and the p-value (0.0603)  is not low enough to reject the null hypothesis.
* The T-test for the suspension coils for Lot 1 show that there is no statistical difference from the mean, and the p-value (1)  is not low enough to reject the null hypothesis.
* The T-test for the suspension coils for Lot 2 show that there is no statistical difference from the mean, and the p-value (0.6072)  is not low enough to reject the null hypothesis.
* The T-test for the suspension coils for Lot 3 show that there is no statistical difference from the mean, and the p-value (0.0417) is low enough to reject the null hypothesis.
<img width="673" alt="Screen Shot 2022-04-15 at 8 27 39 PM" src="https://user-images.githubusercontent.com/97330455/163661613-4c00addc-b723-47a6-9163-bce3b3cc8791.png">
<img width="645" alt="Screen Shot 2022-04-15 at 9 47 50 PM" src="https://user-images.githubusercontent.com/97330455/163661887-2356b8b1-f9e4-46ab-b71c-20bb801915e7.png">


## Study Design
Develop a MechaCar Vehicle to have the best fuel efficiency when compared to the other vehicles in the marketplace. Thereby saving the consumer money in the long run 

### Metrics To Test
Average miles driven in a given city throughout all 4 seasons of the year
Average size of the vehicles fuel tank capacity 

### Null and Alternate Hypothesis
Null Hypothesis - There is no statistical difference between MechaCars average mpg vs the other manufacturers
Alternate Hypothesis -  The MechaCar average mpg is statistically greater than the other manufacturers mpg

### Statistical Test Used 
The best statistical test for this would be two-sample t-tests

### What data is needed?
We would need to gather the average mpg data for all the major car manufacturers and the average mpg for MechaCar
