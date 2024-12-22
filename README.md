# regression-on-diamond-price

# Overview

In the notebook you will perform a complete pipeline of machine learning - regression task. First, you will:
- split the data into training, validation, and test;
- standardize the data.

You will then be asked to learn various SVM models, in particular:
- for each of the kernels *linear*, *poly*, *rbf*, and *sigmoid*, you will learn the best model, choosing among some fixed values of the considered hyperparameters. In particular, the choice of hyperparameters must be done with **5-fold cross-validation**, as we have seen in the labs.

Then, from the models trained with the best hyperparameters selected as above, you will:
- choose the best kernel, using a validation approach (not cross-validation), and
- learn the best SVM model overall.

Furthermore, you will then be asked to estimate the generalization error of the best SVM model you report.

At the end, just for comparison, you will also be asked to learn a standard linear regression model (with squared loss), and estimate its generalization error.

### IMPORTANT
- Note that in each of the above steps you will have to choose the appropriate split of the data (see the first bullet point above);
- The code should run without requiring modifications even if some best choice of parameters, changes; for example, you should not pass the best value of hyperparameters "manually" (i.e., passing the values as input parameters to the models). The only exception is in the TO DO titled 'ANSWER THE FOLLOWING'
- $\texttt{epsilon}$ parameter: For SVM, since the values to be predicted are all in the thousands of dollars, you will need to always set $\texttt{epsilon} = 100$
- Do not change the printing instructions (other than adding the correct variable name for your code), and do not add printing instructions!
