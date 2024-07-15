E-Commerce Store Dataset Analysis and Linear Regression Modeling

Introduction

This project aims to analyze an e-commerce store dataset using machine learning techniques, specifically implementing a Linear Regression model to predict the yearly amount spent by users based on selected features.

Dataset Description

The dataset includes several key fields:

Avg. Session Length: Average duration of user sessions.
Time on App: Time spent on the mobile app.
Time on Website: Time spent on the website.
Length of Membership: Number of years the user has been a member.
Yearly Amount Spent: Total amount spent annually.
Methodology

Data Exploration and Preparation
The dataset was loaded into a pandas DataFrame for initial exploration. Descriptive statistics and visualizations, such as Seaborn pair plots, were used to understand relationships between selected features and the target variable.

Model Implementation
A Linear Regression model was chosen for its ability to establish relationships between predictor variables and the target variable (Yearly Amount Spent). Features selected for prediction included Avg. Session Length, Time on App, Time on Website, and Length of Membership.

Results and Findings
R^2 Score: 0.9806
Mean Absolute Error: $8.43
Root Mean Square Error: $10.19
The high R^2 score indicates that the model explains approximately 98.06% of the variance in the Yearly Amount Spent. The mean absolute error of $8.43 suggests that, on average, predictions differ by $8.43 from actual values.

Conclusion and Recommendations
Based on the analysis, time spent on the mobile app, time spent on the website, length of membership, and average session length are significant predictors of yearly spending. Strategies to enhance user experience on both platforms and improve membership retention could potentially increase spending.
