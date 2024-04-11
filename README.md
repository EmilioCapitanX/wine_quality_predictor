## Wine Quality Predictor
This project aims to predict the quality of a wine based on various features.
## Dataset
There are two datasets used in this project, one for white wine and another one for red wine. The variables in the dataset are the following (detail of each feature included in the python notebook): fixed acidity, volatile acidity, citric acid, residual sugar, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol. 
## Algorithm
For this project only RandomForestClassifier was used as an algorithm, and using grid search, hyperparameter tunning was done to find the best values for hyperparameters: number of estimators, minimum samples split, minimum samples leaf, maximum features, maximum depth, criterion.
## Results
The results of the evaluation metrics can be seen in the python notebook, and the predictions made by the model can be consulted in the predictions.csv file
