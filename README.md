# task-5-Decision-tree-randomforest
AI & ML Internship - task 5-Decision tree-randomforest


_ Objective_

The objective of this task is to understand and implement tree-based machine learning models for classification.
In this project, I trained and evaluated a Decision Tree Classifier and a Random Forest Classifier using the Breast Cancer dataset.



> Dataset Used



Dataset: Breast Cancer Wisconsin Dataset

Source: Built-in dataset from sklearn.datasets

Type: Classification

Target Variable: Malignant (0) / Benign (1)




> Tools & Libraries Used





Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🔹 Steps Performed
1️> Data Loading




Loaded the Breast Cancer dataset using load_breast_cancer()

Converted it into a Pandas DataFrame

2️> Train-Test Split



Split data into 80% training and 20% testing

3️> Decision Tree Model



Trained a Decision Tree Classifier

Evaluated accuracy on test data

Visualized the tree structure

4️> Overfitting Control



Limited tree depth using max_depth=3

Compared performance with full tree

5️> Random Forest Model



Trained Random Forest Classifier

Compared accuracy with Decision Tree

6️> Feature Importance



Extracted feature importance from Random Forest

Visualized top important features

7️> Cross Validation



Performed 5-fold cross-validation

Calculated mean accuracy score

. Results



Decision Tree achieved high accuracy.

Limited-depth tree reduced overfitting.

Random Forest performed better and more stable.

Cross-validation confirmed consistent model performance.

. Key Learnings



How Decision Trees split data using feature conditions.

How overfitting occurs in deep trees.

How Random Forest reduces overfitting using bagging.

Importance of feature importance analysis.

How to evaluate models using cross-validation.

> Project Structure


> Conclusion

Random Forest provides better generalization compared to a single Decision Tree. Ensemble learning improves stability and accuracy of the model.
