Loading and Preparing Data: Load the training data and prepare the features (X) and target (y).
Splitting Data: Split the data into training and validation sets.
To generate different models and potentially achieve a better F1 score, i tried several approaches i.e. using different algorithms
Training Models: Trained different models and sumitted it by numbering like submission1,submission2.....
the models used for training are Logistic Regression, Random Forest, Gradient Boosting, Hyperparameter tuning for Random Forest,XGBoost,LightGBM and evaluate their F1 scores.
Hyperparameter Tuning: Perform hyperparameter tuning on the Random Forest model using GridSearchCV.
Loading the test data and then applied the models to predict the target on test data and save the results to a CSV file.
