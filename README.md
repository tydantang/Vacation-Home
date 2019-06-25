# Vacation-Home
This project focused on predicting the likelihood of individuals purchasing vacation home using various machine learning approaches including logistic regression, random forest, gradient boosting, and neural network. One or more packages of each machine learning approach were evaluated.

The project started with exploratory data analysis and data preprocessing. Specifically, data distribution, variable correlation, missing value and information value were examined. Additionally, data imputation, feature scaling and data splitting were performed.

Before carrying out machine learning model evaluation, grid search on a representative package, random forest in this case, was performed for optimal hyperparameter selection. The results from grid search were applied to all machine learning model evaluation. All models were evaluated based on ROC_AUC scores, accuracy and computing speed. Incremental and cumulative lifts of selected models were calculated as a measure of the effectiveness.

Model defining, compiling and fitting of neural network were demonstrated. Neural network performed suprisingly well and comparable to other machine learning algorithms.
