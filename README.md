**Problem Statement:** Using machine learning techniques have the potential to identify hidden
patterns that we did not see before and can be used to make accurate predictions to detect stock
market trends. Our project, we will be looking at technical analysis and focusing on the Simple
linear regression techniques to predict stock prices.

![yes-bank](https://user-images.githubusercontent.com/96189065/200250371-7589e8e9-f264-4bbe-958f-947f40646568.jpg)

Approaches:
1. Starts from the analysis of Dataset and its statistics, identified the number of rows and columns in 
data set. The first step involve is Data preparation, Data Cleaning & Basic Analysis 
2. Understands the data and is statistics involves data inspection, data description, data summary 
statistics 
3. Data processing involves conversion of date column into Date time index format. No null values 
present in dataset.
4. Use technical indicator exponential moving average.
5. Used Another feature as dependent variables such a make Next month column and target column 
for prediction.
6. Exploratory Data Analysis\
7. Train and Test of Data
8. Apply Linear Regression
9. Predicting Training and Testing Data
10. Regression Model Evaluation Metrics
11. Simple linear regression techniques to predict stock prices. Additionally, we’ll utilize Lasso 
regression, Ridge regression and elastic net to build a predictive model and compare its 
performance against our technical analysis
12. Use Evaluation matrices and find out model is best fit to yes bank stock prediction model.


**Conclusion:** Linear regression is a simple technique and quite easy to interpret, but there are a few 
obvious disadvantages. One problem in using regression algorithms is that the model over fits to the month 
column. Instead of taking into account the previous values from the point of prediction, the model will 
consider the value from the same a month from year ago. As seen from the plot graph, for January 2016 
and January 2017, there was a drop in the stock price. The model has predicted the same for January 2018. 
A linear regression technique can perform well for problems such as Big Mart sales where the independent 
features are useful for determining the target value. So we can conclude that as our prediction line does not 
match the actual line and R2 score is 45 %. So linear regression model does not perform well
