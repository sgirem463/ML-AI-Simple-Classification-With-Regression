## Binary Classification with Linear Regression

In this study I used the Bank Marketing dataset from the UCI Machine Learning Repository [[link here]](https://archive.ics.uci.edu/datasets?skip=0&take=10&sort=desc&orderBy=NumHits&search=&Area=Business)

The purpose is to show we can use LinearRegression() to do simple cassification prediction with a small amount of code.

For Data preparation, I did the following:
1. Removed unwanted columns and make sure there is no NaN
2. Converted nonnumerical cloumns to numerical, e.g. loan and housing
3. most importantly, convert the y (campaing successful or not) to 0 and 1 according.

For modeling and prediction I did:
1. Built a LinearRegression model to predict the marketing campaign success probability
2. Created a prediction array/column by assigning 1 to it if the success probability >= 0.5, 0 otherwise.
3. Calculate the prediction accuracy by comparing the prediction to y

The accuracy is 0.89, which is good if not excellent.
