# Quantile-Regression
This code is a section of the article: "Linear and nonlinear regression with stable errors", wrote by John.P Nolan. 
This paper believe that, This algorithm can help us to have robust data.

1- Perform an initial OLS fit to the data.

2- Using the residuals from the previous step, perform a trimmed OLS fit. 

3- Two quantiles are used to select a trimmed data set. The defaults are p1 = 0.1 and p2 = 0.9, i.e. the lowest and highest 10% are trimmed away. A second OLS fit is performed on the trimmed data to find an initial estimate of the regression.
