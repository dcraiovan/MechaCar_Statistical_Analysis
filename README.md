## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/111898553/207760605-d78410f9-5b10-4067-8e2e-1bde3908e0d3.png)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The vehicle length, and vehicle ground clearance are statistically likely to provide non-random amounts of variance to the model. That is to say, the vehicle length and vehicle ground clearance have a significant impact on miles per gallon on the MechaCar prototype. Conversely, the vehicle weight, spoiler angle, and All Wheel Drive (AWD) have p-Values that indicate a random amount of variance with the dataset.

- Is the slope of the linear model considered to be zero? Why or why not?
The p-Value for this model, p-Value: 5.35e-11, is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis, which further indcates that the slope of this linear model is not zero.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This linear model has an r-squared value of 0.7149, which means that approximately 71% of all mpg predictions will be determined by this model. Relatively speaking, his multiple regression model does predict mpg of MechaCar prototypes effectively.
