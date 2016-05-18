# Classification-and-Regression

Two data sets are provided:
1. A 2D sample data set in the le \sample.pickle" along with the class assignment.
2. A medical data set is provided in the le \diabetes.pickle" along with the target assignment. The input variables 
correspond to measurements (physical, physiological, and blood related) for a given patient and the target variable 
corresponds to the level of diabetic condition in the patient. It contains:
• xtrain (242 * 64) and ytrain (242 * 1) for training.
• xtest (200 * 64) and ytest (200 *  1) for testing.

# Task -

Problem 1: Experiment with Gaussian discriminators

Implemented Linear Discriminant Analysis (LDA) and Quadratic Discriminant Analysis (QDA). Implemented two functions 
in Python: ldaLearn and qdaLearn which take a training data set (a feature matrix and labels) and return the means 
and covariance matrix (or matrices). Implemented two functions ldaTest and qdaTest which return the true labels for
a given test data set and the accuracy using the true labels for the test data.

Problem 2 : Experiment with Linear Regression

Implemented ordinary least squares method to estimate regression parameters by minimizing the squared loss in 
learnOLERegression method. Also implemented the function testOLERegression to apply the learnt weights for prediction 
on both training and testing data and to calculate the root mean squared error (RMSE).

Problem 3 : Experiment with Ridge Regression

Implemented parameter estimation for ridge regression by minimizing the regularized squared loss in learnRidgeRegression
method. Calculateed the RMSE for training and test data using ridge regression parameters using the the testOLERegression 
function.

Problem 4 : Using Gradient Descent for Ridge Regression Learning

Implemented the gradient descent procedure for estimating the weights w. Used the minimize function (from the scipy 
library). Implemented a function regressionObjVal to compute the regularized squared error and its gradient with 
respect to w. In the main script, this objective function will be used within the minimizer.

Problem 5 : Non-linear Regression

Investigated the impact of using higher order polynomials for the input features. Implement the function mapNonLinear.m
which converts a single attribute x into a vector of p attributes, 1; x; x^2; . . . x^p.

Problem 6 : Interpreting Results

Using the results obtained for previous 4 problems, made final recommendations for anyone using regression for predicting 
diabetes level using the input features.
