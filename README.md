# Data Science Analysis

Author - Eshan Arora

Here is a brief summary of each part:

PART 1:
* The dataset comprises of ratings given by people to various movies. I removed all null and the missing values. Then, I performed some data statistics as per the specification. After performing data statistics, I did some visualization followed by detection and removal of outliers.   


PART 2:
* Used the same dataset as part 1, without the null values, missing values and the outliers. Divided the dataset into training and testing sets and performed 4 linear regressions with different testing set sizes and independent features. Evaluated these models based on MSE/RMSE values and r-squared. At the end, plotted some visuals to compare the MSE and RMSE values of the models.

PART 3: 
* In the final part, I used the same dataset but the "Feedback" column feature was changed to a binary classified column. It showed whether a person likes a particular movie. While preparing data, I encoded some categorical features to numerical features through OrdinalEncoder. Since, It was a binary classification problem so I performed a logistic regression model as a simple baseline model followed by KNN classifier model, an advanced model. Compared the accuracy score of both the models. KNN got a higher accuracy score than logistic regression model.

***