# Binary-Logistic-Regression Example.
## Description
Binary Logistic Regression is a type of classification Machine Learning algorithm used to determine the impact of multiple independent variables presented to predict a categorical variable(two outcomes) or he likelihood of an event/scenario.
Some of the examples of binary outcome cases include:
- Whether a person is **satisfied** with a product or **not satisfied**.
- Consumers make a decision to **buy** or **not buy** a product.
- Whether a comapny is **making profit** or **not making profit**.
- Whether there are **good** or **poor** credit risks.
---
## Assumptions
- Binary logistic regression requires the dependent variable to be binary.
- For a binary regression, the factor level 1 of the dependent variable should represent the desired outcome.
- Only the meaningful variables should be included.
- The independent variables should be independent of each other. That is, the model should have little or no multicollinearity.
- The independent variables are linearly related to the log odds.
---
##Steps
- Importing the necessary scikit-learn library packages.
- Data cleaning and Exploration.
- Splitting the data into Independent and Dependent variables.
- Changing the categorical code of a character variable to 0 and 1.
- Splitting the data set into **Train** and **Test** sets with a high percentage of Train set.
- Fitting the Logistic model using the **Train** set.
- Predicting the **Test** set results and getting the accuracy of the model.
- Build a Confusion Matrix - Used to determine the perfomance of the algorithm.




