# Performing simple linear regression in R.

I used the Auto dataset to perform simple linear regression in R, with "mpg" as the response variable and "horsepower" as the predictor.

# Interpretation of R-output: 

Beta0 = 39.935861, B1= -0.157845. This means that for every increase in horsepower by 0.157845 units, there will be an equivalent decrease in mpg by the same amount due to the negative slope. In addition, p-value for horsepower was less than 0.05. This means it is statistically significant, which means that a significant p-value for horsepower indicates that it will give a reliable guess of mpg. To test for a linear relationship, we use the null hypothesis of B1=0 with alternative hypothesis B1 is not equal to 0. By the coefficients of linear regression, we can see that B1= -0.157845 with p-value <2e-16, which allows us to reject the null hypothesis. This means there is some basis that mpg and horsepower share a linear relationship. Testing for a 98% confidence interval yields: B0 [38.2598, 41.6119] and B1 [-0.1729, -0.1428].
