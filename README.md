# Predictive Analytics Exercise 
## Task Description:
### Logistic Regression for Diabetes Prediction:
- Use a logistic regression model to predict the "Outcome", in a dataset with potential diabetes patients, where 0 indicates the patient has diabetes, and 1 indicates the absence of diabetes.
- Evaluate the model's accuracy and explore the impact of regularization (L1 and L2 penalties).
### Age-based Analysis:
- Generate a bar plot to showcase the accuracy of the model across different age groups (0-40 and 40-100) in the test set.
- Repeat the process, altering the regularization parameter to 'l1' and adjusting the solver to 'liblinear'.
### Linear Regression for Blood Pressure Prediction:
- Implement linear regression using features like Age, BMI, and Pregnancies to predict the variable BloodPressure.
- Split the dataset into a 70/30 train-test set and measure the model accuracy using Mean Absolute Error (MAE).
### Descriptive Statistics:
- Calculate the mean (μ) and standard deviation (σ) of the BloodPressure variable for both the Train Set and Test Set.
- Compare the distributions by creating histograms for BloodPressure in the Train and Test Sets.
### Stochastic Gradient Descent (SGD) Comparison:
- Replace the Least Squares method with Stochastic Gradient Descent (SGD) using the SGDRegressor model.
- Experiment with penalty parameters (l2, l1, elasticnet, None) and create a table to compare MAE across different methods.
