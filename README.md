# Recession_Prediction_USA
This project aims to develop a robust model to predict recessions in USA by analyzing key economic indicators such as Debt-to-GDP ratio, Federal Funds rate, Inflation CPI, Manufacturing O/P, Unemployment Rate and 5 other indicators.
The dataset contains 50 years of historical US economic data, which was obtained from the official websites of the US govt.
After cleaning and doing EDA on data, we created three ML models: Logistic regression, Random Forest and Gradient Boost.
We used GridSearchCV to find the optimal Hyperparameters and then trained the models by using these hyperparameters.
We created a local server using Flask in python and deployed our model on Amazon EC2 instance which will make server run indefinitely.
Technologies used: Python-pandas, matplotlib, Seaborn, Amazon EC2 and Tableau.
