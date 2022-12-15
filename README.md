## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/111898553/207760605-d78410f9-5b10-4067-8e2e-1bde3908e0d3.png)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The vehicle length, and vehicle ground clearance are statistically likely to provide non-random amounts of variance to the model. That is to say, the vehicle length and vehicle ground clearance have a significant impact on miles per gallon on the MechaCar prototype. Conversely, the vehicle weight, spoiler angle, and All Wheel Drive (AWD) have p-Values that indicate a random amount of variance with the dataset.

- Is the slope of the linear model considered to be zero? Why or why not?
The p-Value for this model, p-Value: 5.35e-11, is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis, which further indcates that the slope of this linear model is not zero.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This linear model has an r-squared value of 0.7149, which means that approximately 71% of all mpg predictions will be determined by this model. Relatively speaking, his multiple regression model does predict mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils

First looking at all manufacturing lots:
![image](https://user-images.githubusercontent.com/111898553/207761912-ac1b033a-9866-42c0-979d-d3258539f9b3.png)

Diving a little deeper into each of the 3 lots:
![image](https://user-images.githubusercontent.com/111898553/207762013-12d9b6c4-af20-43e3-8b60-f809b1e4f7f0.png)

With the understanding that the design specifications for the MechaCar suspension coils mandate that the variance of the suspension coils cannot exceed 100 pounds per square inch (PSI) .

Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

When looking at the entire population of the production lot, the variance of the coils is 62.29 PSI, which is well within the 100 PSI variance requirement.

Similarly, but significantly more consistent, Lot 1 and Lot 2 are well within the 100 PSI variance requirement; with variances of 0.98 and 7.47 respectively. However, it is Lot 3 that is showing much larger variance in performance and consistency, with a variance of 170.29. It is Lot 3 that is disproportionately causing the variance at the full lot level.

