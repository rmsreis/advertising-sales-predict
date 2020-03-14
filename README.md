
## Predict Sales Revenue with scikit-learn
-------------------------------------------------

This is an example of simple linear regression model to predict sales and revenue using Python. 
I employed scikit-learn module for calculating the linear regression, while using pandas for data management, and seaborn for plotting.

The first dataset 

in the second part I will work with the advertising data of a marketing agency to develop a machine learning algorithm that predicts if a particular user will click on an advertisement.

### Simple Linear Regression
------------------------------------------------

Linear Regression is a useful tool for predicting a quantitative response.

We have an input vector `X^T = (X_1, X_2,...,X_p)` , and want to predict a real-valued output `Y`. The linear regression model has the form.

`f(x) = \beta_0 + \sum_{j=1}^p X_j \beta_j`

The linear model either assumes that the regression function `E(Y|X)` is linear, or that the linear model is a reasonable approximation.

Here the `\beta_j`'s are unknown parameters or coefficients, and the variables `X_j` can come from different sources. No matter the source of `X_j`, the model is linear in the parameters.


### Dataset:
-------------------------------------------------
1. The adverstiting dataset captures sales revenue generated with respect to advertisement spends across multiple channles like radio, tv and newspaper. <a href='http://faculty.marshall.usc.edu/gareth-james/'> Source</a>

2. The second dataset consists of 10 variables: 'Daily Time Spent on Site', 'Age', 'Area Income', 'Daily Internet Usage', 'Ad Topic Line', 'City', 'Male', 'Country', Timestamp' and 'Clicked on Ad'. <a href='https://www.kaggle.com/fayomi/advertising/download'> Source</a>


robertomsreis@gmail.com

