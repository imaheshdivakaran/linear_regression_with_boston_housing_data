# Linear Regression with Boston Housing Data-set

# Linear Regression 
Regression involves using one or more variables, labelled independent variables, to predict the values of another variable, the dependent variable. Variables that are strongly correlated with the dependent variable will be used for predicting that variable.


# Boston Housing Dataset
Housing data contains 506 census tracts of Boston from the 1970 census. The dataframe `BostonHousing` contains the original data by Harrison and Rubinfeld (1979), the dataframe BostonHousing2 the corrected version with additional spatial information.

You can include this data by installing `mlbench` library. The data has following features, `medv` being the target variable:

 * crim   - per capita crime rate by town
 * zn     - proportion of residential land zoned for lots over 25,000 sq.ft
 * indus	- proportion of non-retail business acres per town
 * chas	  - Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
 * nox	  - nitric oxides concentration (parts per 10 million)
 * rm	    - average number of rooms per dwelling
 * age	  - proportion of owner-occupied units built prior to 1940
 * dis	  - weighted distances to five Boston employment centres
 * rad	  - index of accessibility to radial highways
 * tax	  - full-value property-tax rate per USD 10,000
 * ptratio- pupil-teacher ratio by town
 * b	1000(B - 0.63)^2, where B is the proportion of blacks by town
 * lstat  - percentage of lower status of the population
 * medv	  - median value of owner-occupied homes in USD 1000's
