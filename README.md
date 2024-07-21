# Formative-Assessment-Supervised-Learning
The objective of this assessment is to evaluate your understanding and ability to apply supervised learning techniques to a real-world dataset.
Objective:

Dataset:
Use the breast cancer dataset  that is import from sklearn library.

Key Components:
1. Loading and Preprocessing
Load the breast cancer dataset from sklearn.

Preprocess the data to handle any missing values and perform necessary feature scaling.

Loading the breast cancer dataset from sklearn and preprocessing . here , first we import the StandardScaler which is used for standardizing features. Fits the scaler to the data and transforms it and then we prints the Scaled data and give Rounds the scaled values to 2 decimal places to display data for better readabitiy.This preprocessing step ensures that the features are standardized to have a mean of zero and a standard deviation of one. Such standardization is a common requirement for many machine learning algorithms, as it helps them perform more effectively

2.Classification Algorithm Implementation:

Implement the following five classification algorithms:

1.Logistic Regression
2.Decision Tree Classifier
3.Random Forest Classifier
4.Support Vector Machine (SVM)
5.k-Nearest Neighbors (k-NN)

Logistic Regression is a statistical method for predicting a binary outcome. It models the probability that an instance belongs to a particular class using a logistic function. The algorithm finds the best fitting model by maximizing the likelihood function. It's suitable for the breast cancer dataset because:

It works well with numerical features, which this dataset primarily consists of. It provides interpretable coefficients for each feature, allowing doctors to understand the impact of each measurement on the diagnosis. It's computationally efficient and works well for linearly separable classes.

Decision Tree Classifier: A Decision Tree is a flowchart-like structure where each internal node represents a "test" on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label. The paths from root to leaf represent classification rules. It's appropriate for this dataset because:

It can capture non-linear relationships between features and the target variable. It provides a clear visual representation of the decision-making process, which can be valuable for medical professionals. It can handle both numerical and categorical data, making it versatile for various types of medical data.

Random Forest Classifier: Random Forest is an ensemble learning method that constructs a multitude of decision trees at training time and outputs the class that is the mode of the classes of the individual trees. It uses bagging and feature randomness when building each tree. It's excellent for the breast cancer dataset because:

It can handle the relatively high number of features without overfitting. It captures complex interactions between features. It provides feature importance rankings, which can be crucial in understanding key diagnostic factors. It's less prone to overfitting compared to a single decision tree.

Support Vector Machine (SVM): SVM finds the hyperplane that best separates the classes in a high-dimensional space. It maximizes the margin between the classes, using support vectors to define the decision boundary. It's well-suited for this dataset because:

It performs well with many features and can capture complex relationships. It's effective when there's a clear margin of separation between classes. It works well for binary classification problems like this one. It's less prone to overfitting in high-dimensional spaces.

k-Nearest Neighbors (k-NN): k-NN classifies a data point based on the majority class of its k nearest neighbors in the feature space. It's a non-parametric method that stores all available cases and classifies new cases based on a similarity measure. It can work well with this dataset because:

It can capture local patterns in the feature space. It's intuitive and doesn't make strong assumptions about the overall structure of the data. It works well when decision boundaries are irregular. It's effective when the relationship between features and outcome is complex or unknown.

3.Finding the best and worst algoritham:

Best Model: Logistic Regression
F1-score: 1.0000
Accuracy: 1.0000
Precision: 1.0000
Recall: 1.0000

Worst Model: k-Nearest Neighbors (k-NN)
F1-score: 0.9926
Accuracy: 0.9912
Precision: 0.9853
Recall: 1.0000

Here, all the models performed well.By comparing the models Logistic Regression preform the best due to its perfect scores across all metrics. On the other hand, k-NN, was the worst , still shows strong performance with a high F1-score, indicating that it is also a viable option but slightly less optimal compared to the others.

Conclusion:

Loading and Preprocessing:

First we Load the dataset that import from sklearn and preprocess it by confirming there are no missing values and performing feature scaling to standardize the data.

Classification Algorithm Implementation:

Implement five different classification algorithms, providing a brief description of each and explaining why it might be suitable for the breast cancer dataset.

This assessment will demonstrate your ability to handle data preprocessing and apply various supervised learning algorithms to a real-world dataset, evaluating their effectiveness based on performance metrics.


