# Machine-Learning
A repository data analysis using ML

LINEAR REGRESSION :

Linear regression is a statistical method for modeling the relationship between a dependent variable and one or more independent variables. It assumes a linear relationship between the dependent variable and the independent variable(s), meaning that the change in the dependent variable is proportional to the change in the independent variable(s).

In simple linear regression, there is only one independent variable, and the relationship between the independent and dependent variables can be represented by a straight line. The goal is to find the best-fitting line that represents the relationship between the variables.

The equation for a simple linear regression model is:

y = b0 + b1 * x

where y is the dependent variable, x is the independent variable, b0 is the y-intercept (the value of y when x = 0), and b1 is the slope of the line (the change in y for a unit change in x).

The goal is to find the values of b0 and b1 that minimize the sum of the squared errors between the predicted values and the actual values. This is usually done using the method of least squares.

Once the coefficients have been estimated, the model can be used to make predictions for new values of x. The accuracy of the model can be assessed using various metrics, such as the coefficient of determination (R-squared) or the root mean squared error (RMSE).

LOGISTIC REGRESSION:

Logistic regression is a type of regression analysis that is used when the dependent variable is categorical (i.e., binary or ordinal) rather than continuous. It is commonly used in predictive modeling and classification problems.

The goal of logistic regression is to model the probability of an event occurring based on one or more predictor variables. The logistic regression model estimates the probability of the dependent variable (i.e., the event) taking on a certain value, given the values of the predictor variables. The model uses a logistic function (also known as a sigmoid function) to transform a linear combination of the predictor variables into a value between 0 and 1, which represents the probability of the event occurring.

The logistic function used in logistic regression is:

P(Y=1) = 1 / (1 + exp(-(β0 + β1X1 + β2X2 + ... + βpXp)))

where P(Y=1) is the probability of the event occurring, X1, X2, ..., Xp are the predictor variables, β0, β1, β2, ..., βp are the coefficients that correspond to each predictor variable, and exp() represents the exponential function.

Logistic regression is a popular method for modeling binary outcomes (e.g., whether a customer will purchase a product or not), but it can also be used for ordinal outcomes (e.g., predicting the likelihood of a customer rating a product as "excellent", "good", "fair", or "poor"). Logistic regression can be applied in various fields such as finance, marketing, healthcare, and social sciences.
