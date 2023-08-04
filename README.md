# House-Price-Prediction-Deployment
Deployment of the House Price Sales prediction Using Flask

I will be using linear regression to predict the sales value in the third month using rate of interest and sales of the first two months.

# What is Linear Regression
The objective of a linear regression model is to find a relationship between one or more features(independent variables) and a continuous target variable(dependent variable). When there is only one feature it is called Uni-variate Linear Regression and if there are multiple features, it is called Multiple Linear Regression.

# Why Flask?
* Easy to use.
* Built in development server and debugger.
* Integrated unit testing support.
* RESTful request dispatching.
* Extensively documented.

# Project Structure
This project has four parts :
* model.py — This contains code for the machine learning model to predict sales in the third month based on the sales in the first two months.
* app.py — This contains Flask APIs that receives sales details through GUI or API calls, computes the predicted value based on our model and returns it.
* request.py — This uses requests module to call APIs defined in app.py and displays the returned value.
* HTML/CSS — This contains the HTML template and CSS styling to allow user to enter sales detail and displays the predicted sales in the third month.
