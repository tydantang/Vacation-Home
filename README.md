# Vacation-Home
This project focused on predicting the likelihood of individuals purchasing vacation home using various machine learning approaches including logistic regression, random forest, gradient boosting, and neural network. One or more packages of each approach were evaluated given their availabilities.

The project started with exploratory data analysis and data preprocessing. Specifically, data distribution, variable correlation, missing value, and information value were examined. Additionally, data imputation, feature scaling, and data splitting were performed.

Before carrying out machine learning package evaluations, a grid search on a representative package, random forest in this case, was performed for optimal hyperparameter selection. The results from grid search applied to all applicable packages during evaluation. All packages were evaluated based on ROC_AUC scores, accuracy, and speed. Incremental and cumulative lift of selected packages were calculated as a measure of their effectiveness.

Model defining, compiling, and fitting of neural network were demonstrated. The performance of neural network was suprisingly good and comparable to other machine learning algorithms.
