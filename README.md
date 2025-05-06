# Absenteeism-Prediction
In this projec we want to predict absenteeism for a company employees.

The problem is that which employee has the high probability of absenteeism?

At first, we should clean data, check every single feature and change categorical variables to numerical variables using dummy variable technique.

I use Logistic Regression implemented by SciKit-Learn for building the main model. At the end of this step I used pickle to create 2 files; 'model' and 'scaler' that have the main method of making prediction based on this implementation.

Then I created absenteeism_module that uses 'model' and 'scaler' for making predictions. You can also see the using of this module in 'Integration.ipynb'.

In app.py I use streamlit to create a simple web app that uses 'Absenteeism_new_data.csv' for making predictions. In URL file there is also an url that you can see the app globally in share.streamlit.io 
