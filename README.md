### Introduction
Classification in Machine Learning refers to a Supervised predictive modelling problem used to categorize a set of data into classes or predict a class label for a
given input data.
1. **Binary Logistic Regression** is a type of classification Machine Learning algorithm used to determine the impact of multiple independent variables presented to predict a categorical variable(two outcomes) or he likelihood of an event/scenario.
2. **Decision Tree** is a surpervised machine learning algorithm used for solving both regression and classification problems. The data is continuously split according to a certain parameter.
A decision tree consists of nodes (that test for the value of a certain attribute), edges/branch (that correspond to the outcome of a test and connect to the next node or leaf) & leaf nodes (the terminal nodes that predict the outcome) that makes it a complete structure.
3. **Random Forest** is supervised machine learning algorithm widely used for both classification and regression problems. It builds different decison trees on different samples and takes their majority votes for classification and average in case of regression.
The Random Forest leverages the power of multiple decison trees and does not rely on the feature importance given by a single decison tree, hence can generalize over the data in a better way making it more accurate than decison tree.
More about the two algorithms can be found here: [Website](https://www.analyticsvidhya.com/blog/2020/05/decision-tree-vs-random-forest-algorithm/)
 ## Binary-Logistic-Regression
The data had 683 observations and 11 features, of which one is a binary target variable. I performed data cleaning to remove duplicate observations, data had no missing
values. I performed Ordinal encoding for each unique category in the target variable. Evaluation of the model was based on the Classification report that entails the
accuracy score, F1 score and the Recall.
 ## Decision Tree
Data had 683 observations and 9 columns with no missing values. All duplicates rows were removed. I created a function to find and impute outliers using the
Interquartile Range (IQR). Evaluations of the model was based on the confusion matrix, ROC Curve and the Class Probability distribution Curve. 
 ## Random Forest
 The data had 614 observations and 13 features, of which one is a binary target variable. All missing values were found and imputed using the InterQuartile Range, median.
I then performed Ordinal Encoding for each of the unique category in the target variable. Evaluation of the algorithm was based on the confusion matrix, ROC Curve and the Class Probability Distribution Curve.





