# MechaCar_Statistical_Analysis by Ben Altshuler

## Overview
Automotive startup AutosRUs' newest model requires a few more analyses before it enters production. 

This project currently encompasses the following deliverables:

- Multiple linear regression analysis to determine which variables in our set can predict MPG of the new MechaCar

- Summary statistics on PSI of the suspension coils for MechaCar

- T-Test on mean population to statistically differentiate manufacturing lots

- Statistical comparison of MechaCar vs other automotive manufacturers

## Linear Regression to Predict MPG

- Vehicle Length, Weight, and Ground Clearance provided a non-random amount of variance to the MPG values in this data set. That's intuitive as we imagine a truck's mileage versus a small roadster.

- P-value of this analysis is 5.35 x 10(-11). This allows the team to reject the null hypothesis since the slope of the linear model is not zero. 

- The current linear model predicts that about 71% of MPG predictions of MechaCar will be correct when using it. R-value of .71 suggests a negative correlation between mileage and vehicle length, weight, spoiler angle, ground clearance, and AWD. For instance, a heavier vehicle (more weight) will log lower miles per gallon (low mileage numbers). 

## Summary Statistics on Suspension Coils

MechaCar's design dictates that variance among suspension coils across manufacturers not exceed 100 PSI. 

Lots 1-3, when examined together, are within spec with variance of 62.3. 

HOWEVER, individual analysis indicates the variance of Lot 3 is 170.3, putting Lot 3 outside spec. 

## T-Tests on Suspension Coils

