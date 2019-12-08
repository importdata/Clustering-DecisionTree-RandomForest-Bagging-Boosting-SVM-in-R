# Clustering-DecisionTree-RandomForest-Bagging-Boosting-SVM-in-R

Task 1:
- Dataset: Consider the data stored in cereal.csv. It contains measurements on 8 variables (excluding Brand, Manufacturer, and Group) for 43 breakfast cereals.
- Standardized the data
- Hierarchically clustered the cereals using complete linkage and Euclidean distance. Displayed the results using a dendogram.
- Repeated the above using K-Means clustering with K = 2, 3, and 4.

Task 2: 
- Dataset: Consider the Caravan dataset in ISLR package.
- Standardized the predictors and splitted the data into training and test sets.
- Fit a decision tree to the training data. Displayed the tree graphically and describd the regions corresponding to the terminal nodes that provides a partition of the predictor space. 
- Created a confusion matrix and computed the error rate for the unpruend tree using test data.
- Used cross-validation to determine whether pruning is helpful and determine the optimal size for the pruned tree. Compared the pruned and un-pruned trees. Reported the confusion matrix and
error rate for the pruned tree based on the test data. Found out which variables were important to use.
- Used a bagging approach to analyze the data with B = 1000. Computed the confusion matrix and
error rate based on the test data. Found out which variables were important to use.
- Repeated the above with a random forest approach with B = 1000.
- Repeated the above with a boosting approach with B = 1000, d = 1, and lambda = 0.01.
- Repeated the above with a KNN approach with K chosen optimally using the test data.
- Repeated the above with the logistic regression method.
- Compared the results and figured out which method would be the best for this data set.

Task 3:
- Dataset: Business School Admission dataset.
- Splitted the data into training and test set.
- Fitted a support vector classifier to the training data with cost parameter chosen optimally using 10-fold cross-validation. Summarized key features of the itt. Evaluated its performance on the test
data
- Repeated the above using a support vector machine with a polynomial kernel of degree two.
- Repeated the above using a support vector machine with a radial kernel with both gamma and cost parameter chosen optimally.
- Compared the results. 
