# Support Vector Machines with Synthetic Data
 Support Vector Machines with Synthetic Data

1.For this problem, we will generate synthetic data for a nonlinear binary classification problem and partition it into
training, validation and test sets. 
Our goal is to understand the behavior of SVMs with Radial-Basis Function
(RBF) kernels with different values of C and γ.


2.For this problem, we will use the Wisconsin Breast Cancer
  (https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) data set, which has already
  been pre-processed and partitioned into training, validation and test sets.
  
  a.Used scikit-learn's SVC (https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html) function to learn
    SVM models with radial-basis kernels for each combination of C{10^-2, 10^-1,..,10^4} and γ{10^-3,10^-2,...10^2}.
    The tables corresponding to the training and validation errors are generated.
    Used the validation set to select the best the classifier corresponding to the best
    parameter values,C and γ. Reported the accuracy on the test set for this selected best SVM model. 
  
  b.Used scikit-learn's k-nearest neighbor (https://scikitlearn.
    org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html) classifier to learn models for
    Breast Cancer Diagnosis with k {1,5,11,15,21}, with the kd-tree algorithm.
    The tables corresponding to the training and validation errors are generated.
    Used the validation set to select the best the classifier corresponding to the best
    parameter value, k.

