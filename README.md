# MechaCar Statistical Analysis

The goal of this project is to review the production data of AutosRUs’ newest prototype, 
the MechaCar, for insights that may help the manufacturing team. 
In this challenge the data analytics team will do the following:

- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of 
MechaCar prototypes.

- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the 
manufacturing lots.

- Run t-tests to determine if the manufacturing lots are statistically different from the mean population.

- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from 
other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.


## Linear Regression to Predict MPG
![This is an image](https://github.com/DanielBergan/MechaCar_Statistical_Analysis-/blob/main/resources/linear%20regression%20summary.png)
- By performing linear regression analysis on a set of variables including vehicle weight, vehicle length, spoiler 
angle, ground clearence, and drivetrain we discover that two variables provide a non random amount of variance to
the mpg values in the dataset being the ground clearence and the vehicle length.

- Given that the p-value is lower than any level of importance the null hypothesis is rejected and we can safely assume
there is a correlation between our variables and the miles per gallon of the prototype. Thus the slope of our linear model is 
not considered to be zero.

- With an r-squared result higher than 71% in conjunction with the above results this model does predict mpg of MechaCar prototypes 
effectively.

## Summary Statistics on Suspension Coils
![This is an image](https://github.com/DanielBergan/MechaCar_Statistical_Analysis-/blob/main/resources/total%20summary.png)
![This is an image](https://github.com/DanielBergan/MechaCar_Statistical_Analysis-/blob/main/resources/lot%20summary.png)
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Although the variance across the combined manufacturing lots is within the acceptable range when analysized individually the third lot 
has a variance which is way above the specified maximum.

## T-Tests on Suspension Coils

- A T-test performed on the combined manufacturing lots indicate there is not a statistically significant difference form the population mean
and the p-value does not meet the requirement for rejecting the null hypothesis.

![This is an image](https://github.com/DanielBergan/MechaCar_Statistical_Analysis-/blob/main/resources/lot%20summary.png)

- The T-test performed on lot 1 showed that it was well within acceptable variance.

![This is an image](https://github.com/DanielBergan/MechaCar_Statistical_Analysis-/blob/main/resources/lot%201%20t%20test.png)

- The T-test performed on lot 2 showed that it was also well within acceptable variance.

![This is an image](https://github.com/DanielBergan/MechaCar_Statistical_Analysis-/blob/main/resources/lot%202%20t%20test.png)

- The T-test performed on lot 3  confirmed our previous analysis and showed that it did not meet the standards of production.

![This is an image](https://github.com/DanielBergan/MechaCar_Statistical_Analysis-/blob/main/resources/lot%203%20t%20test.png)

## Study Design: MechaCar vs Competition

