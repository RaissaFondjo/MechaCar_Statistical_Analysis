# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG:
This is a short summary using a screenshot of the output from the linear regression, and it address the following questions:

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
2. Is the slope of the linear model considered to be zero? Why or why not?
3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

![Resulting Model 1](https://user-images.githubusercontent.com/80492376/124935866-0b440500-dfd4-11eb-9577-3fbb90760f17.png)

From the above output we can see that:

1. The vehicle length, and vehicle ground clearance are statistically likely to provide non-random amounts of variance to the model. That is to say, the vehicle length and vehicle ground clearance have a significant impact on miles per gallon on the MechaCar prototype. Conversely, the vehicle weight, spoiler angle, and All Wheel Drive (AWD) have p-Values that indicate a random amount of variance with the dataset.

2. The p-Value for this model, p-Value: 5.35e-11, is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis, which further indcates that the slope of this linear model is not zero.

3. This linear model has an r-squared value of 0.7149, which means that approximately 71% of all mpg predictions will be determined by this model. Relatively speaking, his multiple regression model does predict mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils
This is a short summary using a screenshot from the total_summary and lot_summary dataframes, and address the following question:
* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

![Resulting Model 1](https://user-images.githubusercontent.com/80492376/124939771-675c5880-dfd7-11eb-98ad-a07d7b77057a.png)

When looking at the entire population of the production lot, the variance of the coils is 62.29 PSI, which is well within the 100 PSI variance requirement.

![Resulting Model 1](https://user-images.githubusercontent.com/80492376/124939893-7f33dc80-dfd7-11eb-9662-cbebf293d0f7.png)


Similarly, but significantly more consistent, Lot 1 and Lot 2 are well within the 100 PSI variance requirement; with variances of 0.98 and 7.47 respectively. However, it is Lot 3 that is showing much larger variance in performance and consistency, with a variance of 170.29. It is Lot 3 that is disproportionately causing the variance at the full lot level.
