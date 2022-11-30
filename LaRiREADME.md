# House Price Prediction - Advanced regression Assignment

---
### A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
---
---
## Business Goal 

 Required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
-  The project is about how to analyze the data and giving the prediction for the House price prediction and explaining what all variables affect the business and how much of an imapact they have on the target of the business of selecting a house 
---
## Process included in the assignment are :
1) Load & Read and understand the data 

2) Cleaning the data 

3)EDA

4)Visualizing the data 

5)Data preparation

6)Model Building

7)Splitting the data into Train and test data set 

8) RFE

9) Lasso and Ridge Regression

10) Final Model



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Best alpha value for Lasso Regression is when alpha = 0.001

- Best alpha value for Ridge Regression is when alpha = 0.9

-Comparing both the models these features explain the most factors that affect the data set 
-Exterior1st_AsphShn	0.691411
-RoofMatl_Membran	0.615088
-MSZoning_RH	0.443455
-RoofMatl_WdShake	0.439597
-RoofMatl_WdShngl	0.424570
-SaleCondition_Family	0.416064
-Neighborhood_Timber	0.37901

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

---
- This code import s following libraries
``` python
 import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt


import statsmodels
import statsmodels.api as sm
import sklearn
import sklearn.metrics as metrics 
from sklearn.linear_model import LinearRegression
from sklearn.linear_model import Ridge
from sklearn.linear_model import Lasso
from sklearn.model_selection import GridSearchCV
from sklearn.preprocessing import PolynomialFeatures
from sklearn.preprocessing import MinMaxScaler
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.feature_selection import RFE
from sklearn.metrics import r2_score

import statsmodels.api as sm
from statsmodels.stats.outliers_influence import variance_inflation_factor
```


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

