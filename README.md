# ReadMe - artificial_intelligence_course
This repository contains samples of code I wrote for my Master's course in Artificial Intelligence.

**AI HW3 Problem 1.ipynb:** This script, when downloaded as problem1_3.py, is called from terminal as "python3 problem1_3.py input1.csv output1.csv". input1.csv is given, and output1.csv is written. It implements the perceptron learning algorithm for a linearly separable dataset using scikit-learn, printing the coefficients and weights for each iteration.

**AI HW3 Problem 2.ipynb:** This script, when downloaded as problem2_3.py, is called from terminal as "python3 problem2_3.py input2.csv output2.csv". input2.csv is given, and output2.csv is written. This script normalizes the input data, and then it employs gradient descent over a variety of learning rates to determine a linear regression, printing the alpha, iterations, and coefficents for each regression model.

**AI HW3 Problem 3.ipynb:** First, this script accepts the input data and it splits it into training and testing using stratefied sampling. 5-fold cross-validation is employed instead of a validation set. The following classification algorithms are employed:

- SVM with Linear Kernel, using a wide variety of C values
- SVM with Polynomial Kernel, with a wide variety of C values, degree values, and gamma values
- SVM with RBF Kernel, with a wide variety of C and gamma values
- Logistic Regression, with a wide variety of C values
- k-Nearest Neighbors, varying the number of neighbors and leaf size
- Decision Trees, over a variety of maximimum depths and minimum splits
- Random Forest, over a variety of maximimum depths and minimum splits
