# Machine_Learning_Assignments
This repository contains my machine learning assignments which were done through semester 9 
These assignments were done in pairs

## Assignment 1 (Polynomial Regression Assignment)

The objective of this assignment is to apply polynomial regression on the provided data using 3 regularization techniques

### Steps Done:

- Cleaned the data
- Applied Feature scale 
- Evaluated different degrees of lasso CV polynomial regression
- Evaluated different degrees of Ridge CV polynomial regression.
- Evaluated different degrees of ElasticNet CV polynomial regression.
- Compared the models 

### The Conclusion

We found that the best degree of lasso is the 1st degree, the best degree of ridge is the 6th degree, 
and the best degree of elasticNet is the 4th degree. We also found that the best model for this dataset is the Ridge CV polynomial regression.

## Assignment2

The objective of this assignment is to apply logistic regression, KNN, and SVM on the provided dataset

### Steps Done:

- Cleaned the data
- Applied Feature Scaling
- Trained and tested 3 different classification models 
(logistic regression, KNN, SVM) on each dataset separately
- Compared the models

### The Conclusion
 
For the gene dataset, KNN and RBF performed the best providing the same accuracy [0.92] and f1-score macro average [0.92]. However, when comparing their precision and recall, SVM model using an rbf kernel outperformed KNN, making it the best model for this dataset. This is due to the fact that the gene dataset is small in size making SVM an optimal model for it.
For the income dataset, KNN and SVM with RBF kernel performed the best. They both produced the same accuracy [0.85] and macro average f1-score [0.77]. As for precision and recall, both had the same recall but RBF had a higher precision set at [0.82]. Therefore, if all metrics are to be counted, the SVM model with an RBF kernel once again performed the best. Due to the average size of the dataset, both SVM and KNN gave similar performances.
For the heart disease dataset, the logistic regression model worked the best providing an accuracy of 0.91 and macroaverage f1-score of 0.58. The rbf kernel model performed the second best with equivalent accuracy but a lower f1-score. However, the RBF model took the longest running time out of all the previous models, where it took 1000 minutes+ to run with no output in the end. This made us resort to cropping the heart disease dataset into half in order to obtain output from the RBF model, making it's running time a huge drawback. The SVM model with an RBF kernel performed horribly in this scenario due to the large dataset size.
