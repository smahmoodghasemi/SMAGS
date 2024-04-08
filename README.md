# SMAGS


we have developed an improved regression framework, SMAGS, for binary classification that, for a given specificity, finds the linear decision rule that yields the maximum sensitivity. Furthermore, we employed the method for feature selection to find the features that are satisfying the sensitivity maximization goal.
The main function takes the set of features (X) as well as the set of labels (y) and then returns the following: 
The coefficients for each variable as well as intercept. The threshold (SP), specificity and sensitivity, optimization method, learning rate, and Jacobian approach. The coefficients may also be restricted to have a certain boundary.

Here is the requirement to use this code:
Python 3.9.13
Numpy 1.26.4
Pandas 1.4.4
Matplotlib 3.5.2
sklearn 1.0.2
scipy 1.9.1
joblib 1.1.0
