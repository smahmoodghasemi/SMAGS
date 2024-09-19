# SMAGS


we have developed an improved regression framework, SMAGS, for binary classification that, for a given specificity, finds the linear decision rule that yields the maximum sensitivity. Furthermore, we employed the method for feature selection to find the features that are satisfying the sensitivity maximization goal.

The main function takes the set of features (X) and the set of labels (y) as inputs and then returns the following outputs: the coefficients for each variable, including the intercept, the threshold (SP), specificity, highest achievable sensitivity, corresponding optimization method, learning rate, and Jacobian. Additionally, the function may restrict the coefficients to have a certain boundary.

Here is the requirement to use this code:
Python 3.9.13
Numpy 1.26.4
Pandas 1.4.4
Matplotlib 3.5.2
sklearn 1.0.2
scipy 1.9.1
joblib 1.1.0

The details for all other requirements can be found in the environment.yml file. 

You can find the SMAGS algorithm in the "SMGAS.ipynb". In the file, you could generate the same synthetic data and the corresponding figures as well. 
In addition, if you download the "CRC_Analysis.xlsx" in the same path as the Jupyter Notebook code, you will be able to run the real data example. 
this data set is from:
"""Cohen, J. D., Li, L., Wang, Y., Thoburn, C., Afsari, B., Danilova, L., ... & Papadopoulos, N. (2018). 
Detection and localization of surgically resectable cancers with a multi-analyte blood test. Science, 359(6378), 926-930"""


The details of the method can be found here:

https://www.biorxiv.org/content/10.1101/2024.04.12.589302v1.full.pdf
