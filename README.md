# Linear-Regression-Analysis
Linear Regression Analysis with Excel

In this project Excel's Add-in feature is used.

The main question is " How can height can predict weight? " 

Multiple R is the correlation coefficient between the two variables of interest. It is a value that tells you how strong the linear correlation between height and weight is. It can get a value between 0 and 1. It is better to close to 1. In this example multiple R is equals to .502 we can say that it is not a bad outcome.

R square is coefficient of determination value. It tells how much varience the dependent variable can be accounted for by the independent variable. When we multiply this value with 100, we can say that 25% of the varience in weight can be acoounted for by the height measures 75% of he varience is therefore caused by other factors such as measurement errors.

Adjusted R square takes into account the number of independent variables in the analysis and corrects for any bias.

Standart error of the regression is the average distance that the observed values are 10.07 pounds from the regression line. The smaller the standart error, the more precise the linear regression model is.

Observation number is just basically number of the subjects.

On Anova table, "significance f" is the p value of the regression model. To be able to interpret this we need our hypothesis. Our null hypothesis is there is no linear relationship between the height and weight measures. Our alternative hypothesis is there is a linear relationship between the height and weight measures. In this example our is p >= 0.05 and our alternative hypothesis is p <= 0.05, our Significance f is = 0 . This means that we have to reject the null hypothesis and accept the alternative hypothesis.

In coefficient section, intercept value is -82.5757. This means regression line intercept y axis while value of x is equals to 0. Second row shows the slope which is 3.083476 in this example. This means in the simple linear reggression model equation which is y = m.x + b, 
" m " is the slope. Also " b " is the intercept.

t statistic is using while compute the p-value. To interpret this p-value we need our hypothesis, which for null hypothesis intercept = 0 and for alternative hypothesis intercept value != 0 . At this point we will accept the alternative hypothesis and we will say that height is a significant effect on weight in this case.

At the residual output table, we can see that predicted values which correnponds to our original data. For example, at the first data of the original weight is equals to 112.9925 and predicted value is equal to 120.2655 . Basically, residual means predicted - actual.

For residual plots graph, we can see height at the x axis, and points of the values are distributed equally on the up and down side of the x axis. There are not any outliers.

Standart residuals in residual output table is the residual divided by an estimate of its standart deviation. More basically, if the values of that column is > than +3 or -3, it means there is an outlier.

At probability output graph, if there is a straight line, it suggest the weight data is normally distributed.
