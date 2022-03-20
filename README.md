# Introduction-

In this notebook, we will explore using Bayesian Logistic Regression in order to predict whether or not a patient has diabetes. The task is supervised - we are given labeled training data to fit our model - and it is a classification task because the lables are binary. Typically this is a task that is approached with supervised machine learning techniques such as logistic regression, support vector machines, or tree based methods. We will take a slightly different approach and use a Bayesian Framework to fit a logistic regression model and then intrepret the resulting model parameters

# Diabetes-Prediction-

Predict whether or not the patient has diabetes. To accomplish this task, we will use a set of real-world data collected on females 21 years of age and over collected by a national health institution in the United States.

# Diabetes Confusion Matrix -  Confusion Matrix
![Diabetes Confusion Matrix](https://user-images.githubusercontent.com/88205480/159169926-d0efe8fa-363e-48bd-9ca9-50572adb98ef.png)

# BMI vs Glucose for Test Data - 
![BMI vs Glucose for Test Data](https://user-images.githubusercontent.com/88205480/159170056-b7456396-f090-4383-abfc-8cd3f09614d3.png)

# Posterior Probabilites and Test Data - Colormap
![Posterior Probabilites and Test Data](https://user-images.githubusercontent.com/88205480/159170120-02c84860-da8f-4660-9892-3d2cef42c163.png)

# CONCLUSION

we explored whether it was possible to create a useful model using only two input features. While the model did outperform the naive baseline, it was not as performant as the model that used all eight of the features. We plotted the data points in two-dimensions and saw that this is not a linearly separable classification problem.
