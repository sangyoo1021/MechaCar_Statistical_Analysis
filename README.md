# MechaCar_Statistical_Analysis


## Linear Regression to Predict MPG

![Linear_Regression_to_Predict](https://github.com/sangyoo1021/MechaCar_Statistical_Analysis/blob/main/Linear_Regression_to_Predict.png)

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Looking at  the data, both vehicle length and ground clearance shows impact on mpg values. 

### Is the slope of the linear model considered to be zero? Why or why not?
Since the p-value is 5.35e-11 and it is smaller than the significance value of 0.05, the slope of the linear model can not conclude to be zero. 

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linder model prediction seems to be fairly effective since R-squared is 0.7149. The model is 71.49% effective. 


## Summary Statistics on Suspension Coils
![Total_Summary](https://github.com/sangyoo1021/MechaCar_Statistical_Analysis/blob/main/Total_Summary.png)
![Lot_Summary](https://github.com/sangyoo1021/MechaCar_Statistical_Analysis/blob/main/Lot_Summary.png)
Looking at the total summary result, the pounds per square inch variance is 62.29356. This satisfies the design specific requirement. However, Lot 3 does not meet the requirement.

## T-Tests on Suspension Coils
The results of the T-Test are listed below. 
![T-test](https://github.com/sangyoo1021/MechaCar_Statistical_Analysis/blob/main/T-test.png)
![T-test_lot1](https://github.com/sangyoo1021/MechaCar_Statistical_Analysis/blob/main/T-test_lot1.png)
![T-test_lot2](https://github.com/sangyoo1021/MechaCar_Statistical_Analysis/blob/main/T-test_lot2.png)
![T-test_lot3](https://github.com/sangyoo1021/MechaCar_Statistical_Analysis/blob/main/T-test_lot3.png)


## Study Design: MechaCar vs Competition
### What metric or metrics are you going to test?
By calculating fuel efficiency and comparing between the competitors.

### What is the null hypothesis or alternative hypothesis?
Null hypothesis would be that fuel efficiency does not affect the price of a car.  
Alternative hypothesis would be fuel efficiency does influence cost of the car. 

### What statistical test would you use to test the hypothesis? And why?
Linear regression that shows fuel efficiency in relation to cost. 

### What data is needed to run the statistical test?
We need data that shows the fuel efficiency of an individual car and the cost of a car. 
