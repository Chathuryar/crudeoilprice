# crudeoilprice
Crude oil is the world's most leading fuel. The main advantages of crude oil are it has high density, it is easily available. Oil is used in almost all the industries. Oil is a Constant Power Source. 
The main aim of this project is to find the different models that efficiently fit the data points and predict the price of fuel with the help of machine learning models. 

This project works on comparing the different supervised learning models and brings a conclusion based on the efficiency. We have used 3 supervised learning models namely Random Forest Regression, Linear Regression and Decision Tree Regression to know which gives best in terms of accuracy and performance. These algorithms give a numeric value as output. So we can compare the output of these models with the actual models. 
Now-a-days the oil price has been increasing in leaps and bounds due to certain reasons like inflation throughout the world. Hence these are derived or extracted from petroleum. To predict the values of petroleum like petroleum and Diesel within the future, we've decided to use the Machine Learning algorithms. We use performance metrics to find the performance of the supervised learning models based on their errored value. In this way we can compare different algorithms and find the best one for our problem statement.

This Python code creates a graphical user interface (GUI) for crude oil price prediction using machine learning models. It utilizes the tkinter library for GUI creation, scikit-learn for machine learning, and matplotlib for data visualization. The application reads historical crude oil price data from a file, trains Linear Regression and Support Vector Regression models, and extends the data for future predictions. Users can interact with the GUI to view price predictions for 1 day, 30 days, and 365 days into the future, with results displayed in both the console and the GUI interface. The code combines data analysis, machine learning, and visualization to provide a user-friendly tool for predicting crude oil prices.

1. **Linear Regression (linear):
   - Linear Regression is a simple and widely used supervised machine learning algorithm for regression tasks.
   - In this context, it fits a linear relationship between the feature (in this case, the day) and the target (oil price).
   - The LinearRegression() model from scikit-learn is employed to create this linear model.
   - The model is trained using historical data, and then it's used to make predictions for future days.

2. **Support Vector Regression with Radial Basis Function Kernel (svr_rbf):
   - Support Vector Regression (SVR) is a regression technique based on Support Vector Machines (SVMs).
   - In this code, SVR is used with a Radial Basis Function (RBF) kernel, which allows it to capture non-linear relationships between features and targets.
   - The SVR() model from scikit-learn is configured with the RBF kernel and specific hyperparameters (C and gamma).
   - Like Linear Regression, SVR is trained on historical data and then used to make predictions for future days.

These two algorithms are employed to predict future crude oil prices based on historical data. While Linear Regression assumes a linear relationship, SVR with the RBF kernel can capture more complex, non-linear patterns in the data. The code provides users with predictions from both models and allows them to choose between the two regression techniques for forecasting oil prices.
