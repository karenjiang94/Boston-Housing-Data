# Boston-Housing-Data
Project 3- EDA and Data Preparation


### Domain
This is a natural data set acquired from UCI Machine Learning Database[/housing](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/). It is originally derived from a 1970 census conducted by U.S. Census Service regarding housing in the Boston Massachusettes 

The original data set can be found in the publication by Harrison, D. and Rubinfeld, D.L. _'Hedonic prices and the demand for clean air'_, J. Environ. Economics & Management, vol. 5, 81-102, 1978. 

### Problem Statement

The target feature is `MEDV`.

### Dataset Description
The dataset consists of 506 instances and 14 attributes, with no missing values.

13 attributes are continous numeric values, and 1 attribute is binary (`CHAS`).

    1. CRIM      per capita crime rate by town
    2. ZN        proportion of residential land zoned for lots over 
                 25,000 sq.ft.
    3. INDUS     proportion of non-retail business acres per town
    4. CHAS      Charles River dummy variable (= 1 if tract bounds 
                 river; 0 otherwise)
    5. NOX       nitric oxides concentration (parts per 10 million)
    6. RM        average number of rooms per dwelling
    7. AGE       proportion of owner-occupied units built prior to 1940
    8. DIS       weighted distances to five Boston employment centres
    9. RAD       index of accessibility to radial highways
    10. TAX      full-value property-tax rate per $10,000
    11. PTRATIO  pupil-teacher ratio by town
    12. B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks 
                 by town
    13. LSTAT    % lower status of the population
    14. MEDV     Median value of owner-occupied homes in $1000's


### Solution
This is a supervised machine learning problem. We will conduct a PCA to construct a linear regression model based on the features. 

### Benchmark Model
Our benchmark will be a regression to the median.

### Performance Metric
Will will calculate the RMSE to evaluate the performance of our model. 
