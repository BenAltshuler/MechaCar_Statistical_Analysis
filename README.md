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

A 1 sample T Test determined whether or not PSI across all 3 lots was statistically different from the population mean of 1500 PSI. 

Visualization of the distribution is below, showing that this dataset suggests an even distribution. 

PUT VIZ HERE

For all t-tests conducted, the significance level was 0.05 percent.  The t-test compared the means of the Suspension Coil dataset, which was 1498.78, against a mean of 1500. All t-tests conducted resulted in the means being statistically similar.

A t-test across all suspension coil manufacturing lots gave a p-value of 0.06 Since this is above the significance level, the two means are statistically similar. 

Individual lot tests returned similar results

PUT LOT VIZ HERE

# Study Design: MechaCar vs the Competition

## Overview of Study 

Mileage and suspension optimization are critical design considerations for any automotive manufacturer. Another factor that consumers will consider is reliability.

- Metric: average cost of maintenance on the vehicle over its first five years? 

- Hypotheses
    - Null: Average maintenance cost is ~ equal to MechaCar's competition
    - Alternative Hypothesis: Avg maintenance cost is not ~ equal to the competition

- Statistical Test 
    - Multiple Linear Regression to predict maintenance cost over first five years.

- Data Needed
    - Count of sold vehicles, price and frequency of common parts and labor on each



