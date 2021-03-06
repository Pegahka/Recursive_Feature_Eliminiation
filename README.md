# Recursive_Feature_Elimination
Recursive Feature Elimination for MATLAB's fitcsvm

This code combines Rescursive Feature Elimination (RFE) as described in Guyon et al. 2002: Gene Selection for Cancer 
Classification using Support Vector Machines, with Matlab's newest Support Vector Machine (SVM) Implementation: fitcsvm.

The final output of this approach delivers a ranking of the features, as estimated by using a combined approach of feature selection
and classification.

The code is based on KE YAN's code where RFE was combined with the older Matlab SVM implementation (svmtrain):
https://ch.mathworks.com/matlabcentral/fileexchange/50701-feature-selection-with-svm-rfe

