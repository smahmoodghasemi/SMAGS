## SMAGS: Sensitivity Maximization At Given Specificity
We have developed a novel binary classification framework, Sensitivity Maximization At Given Specificity (SMAGS), which identifies the optimal linear decision rule that maximizes sensitivity for a user-defined specificity level. Beyond classification, SMAGS can also be used for feature selection, enabling the identification of variables that best meet the sensitivity maximization objective.

# Function Overview
The main function accepts:

X: Feature matrix

y: Binary label vector

SP: Specificity threshold


And returns:

Coefficients for each feature (including intercept)

SN: Maximum Sensitivity that we Achieved 

Optimization method used

Learning rate

Jacobian

Optional coefficient bounds

# System Requirements
To use SMAGS, ensure the following Python environment:

Python: 3.9.13

NumPy: 1.26.4

Pandas: 1.4.4

Matplotlib: 3.5.2

scikit-learn: 1.0.2

SciPy: 1.9.1

Joblib: 1.1.0

For full dependencies, please refer to the provided environment.yml file.

# Code and Data
The SMAGS algorithm is implemented in the notebook: SMAGS.ipynb

Within the notebook, you can:

Generate synthetic data

Recreate associated figures

Run a real-data example using CRC_Analysis.xlsx (ensure it is placed in the same directory)

Real Data Source
The real-world dataset is based on:

Cohen, J. D., Li, L., Wang, Y., Thoburn, C., Afsari, B., Danilova, L., ... & Papadopoulos, N. (2018).
Detection and localization of surgically resectable cancers with a multi-analyte blood test.
Science, 359(6378), 926-930

Additional Information
For more details on the methodology, please see our publication in Cancer Prevention Research:
[SMAGS: A Novel Sensitivity Maximization at a Given Specificity Method](https://aacrjournals.org/cancerpreventionresearch/article-abstract/18/3/117/751974/A-Novel-Sensitivity-Maximization-at-a-Given?redirectedFrom=fulltext)
