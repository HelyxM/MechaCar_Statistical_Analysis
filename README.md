# MechaCar_Statistical_Analysis

###

## **Overview**:

## **Summary of Results**:

### *Linear Regression to Predict MPG*:
- ![mpg_linreg](mpg_linreg.png)
The summary created from the linear regression function provided useful insight into which key factors influenced the car's resulting MPG rating. The main findings from creating this summary were:
  - The vehicle's length (at a p-value of 2.6 * 10^-12) and the vehicle's ground clearance (at a p-value of 5.21 * 10^-8) were two variables that provided non-random amounts of variance to the MPG values based on this dataset.
  - The slope of the linear model is not considered to be zero because the returned p-value of 5.35 * 10^-11 is below the necessary p-value threshold of 0.05. This shows there is enough evidence to reject the null hypothesis, and to claim the linear model has a slope that can predict the data points with a sufficient degree of accuracy.
  - This linear model does predict the MPG rating of MechaCar prototypes effectively due to the R-squared value of 0.715, indicating a high correlation coefficient. With the R-squared value showing a greater closer value to 1.0 than 0.5, it predicts the MPG values with a much higher degree of accuracy than random chance. With this R-squared value combined with the p-value supporting a much greater probability of accuracy than random chance, this linear model can certainly be considered effective in predicting the MPG values. Despite these pieces of evidence, however, the p-values for the different variables shown in the summary indicate there are not many significant variables that can be identified as key factors in the model. This means the model can predict with some efficiency the known data values, but the accuracy of predicting future values that are not yet known is questionable and can't necessarily be considered reliable.

### * *:

### * *:

### * *:

## **Conclusions**:
