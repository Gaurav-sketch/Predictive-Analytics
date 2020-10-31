# Predictive-Analytics using 


<img src ="https://ih1.redbubble.net/image.512523322.6908/st,small,507x507-pad,600x600,f8f8f8.u1.jpg" />



**Analysis of the House dataset having information on sales of home in Dublin.**

The variables available in the dataset are as below :
- Price (Target Variable)
- Size
- Lot 
- Bath 
- Bed 
- Year 
- Garage
- School

# Work Done on this :

- Exploratory Data Analysis : 
1) Boxplot , Histogram , Summary , Distribution of Sales price of the house. 
2) Converting categorical variable to factors. 
3) Used Summary , Correlation and pair plots in order to find out the relation between response variable and predictor variables.

- Regression Model :
1) Fitted multiple regression model to the data with price as the response variable and rest all as the predictor variable 
2) Interpretation of the estimates/coefficients of all the predictor variables.
3) Analyzed and found the effect of predictor variables on the expected value of the house price.
4) Found what all predictor variables are significantly contributing to the expected value of House price.
5) Plotted the residuals and found that points are spread across mean standardised error and thus can be said as a good model.
6) Checked the Adjusted R-Squared value which showed that 51% of the variation in Y is explained by the predictor variables.
7) Checked the F Statistics and P-Value , found that the null hypothesis is rejected as the p-values was less than 0.05

# Anova :

- Anova(Type 1)
1) In this each predictor variable is added step by step , and the significance is calculated for each of them.
2) Based on the P value , the variable that is less significant is removed.

- Anove(Type 2)
1) Compare the Full model with reduced model.
2) In the Anova 2 output ,the difference is significant or not is being tested by F Test which says that the F value is 2.7064 and the probability is 0.10 greater than 0.05 .
3) Thus, we fail to reject the null hypothesis.Therefore we can remove the predictor variable Year from the model.

# Diagnostics :

1) Created and interpreted the added variable plots and Component-plus-residual plots .
2) Checked the slope of the fitted line , if this is not zero , the variable must be contributing/significant.
3) In the component residual plot , the fitted pink line deviates from the original line ,so indicates the presence of outlier and that variable should be removed.
4) Durbin Watson test statistics to check the presence of Auto-Correlation , so the variables cannot be classed as independent.
5) This can be corrected using Mixed effect model.
6) Variation Inflation Factor and Correlation plot to check the presence of Correlated variables.
7) Check the Normality assumption by interpreting the histogram and quantilequantile plot of the studentized residuals.It was normal but if not then go for transformation.

# Leverage , Influence and Outliers:

1) Found the leverage point having unusual X Value.
2) Found Influential point and removed it.
3) Outlier was present and that was identified using outlier and leverage diagnostics plot.

# Confidence Interval and Prediction Interval 

1) With the plot saw that the fitted values were in the prediction interval.So , overall model was giving good estimation of House price.








