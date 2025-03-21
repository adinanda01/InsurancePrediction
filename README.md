# InsurancePrediction

Overview: This project implements a medical insurance price prediction model using Machine Learning techniques. The model is built using Linear Regression and Polynomial Regression. The primary objective is to predict insurance costs based on various input features such as age, BMI, number of dependents, and smoking habits.

Dataset: The dataset used for this project consists of features that influence medical insurance costs. The key features include:

Age: Age of the individual BMI: Body Mass Index Children: Number of dependents Smoker: Whether the person is a smoker or not Region: Geographic location of the individual Charges: The insurance cost (target variable)

Features: Data Preprocessing: Handling missing values, encoding categorical features, and feature scaling. Exploratory Data Analysis (EDA): Visualizing relationships between variables. Polynomial Regression Model: Training and evaluating a regression model for price prediction. Model Performance Metrics: Measuring accuracy using Mean Absolute Error (MAE) and R-squared Score. Predictions on New Data: Allowing users to input new values for prediction.

Model Evaluation: The model is evaluated using: R-squared Score: Measures how well the model explains variance. Mean Absolute Error (MAE): Measures average prediction error.

Results: Polynomial regression improves prediction accuracy compared to linear regression. Key factors affecting insurance costs: age, BMI, and smoking status. Smokers tend to have significantly higher insurance costs
