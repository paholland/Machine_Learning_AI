## Machine Learning Project - Exoplanet Exploration

    The deployed assignment utilizes the sklearn library to train models on a set of data and used to make predictions. 
      
Preprocess the raw data (Preprocessed the dataset prior to fitting the model. Performed feature selection and removed unnecessary features. Used MinMaxScaler to scale the numerical data. Separated the data into training and testing data), 

tuned the models (Used GridSearch to tune model parameters. Tuned and compared two different classifiers), and 

compared models (Created a README that reports a comparison of each model's performance as well as a summary about findings and any assumptions based on a model).
    
    
Data Preprocessing (Unnecessary Columns are removed; All rows containing NaN are removed; Data is correctly split into a
training and test set; Numerical data is scaled accordingly)

Model Creation (Creates, trains, and tests at least 2 different classification models; Correctly sets X and y (koi_disposition) variables
Feature Selection (Uses some form of feature selection method to identify insignificant variables [feature_importance, RFE,
backwards elimination, etc.] Remove insignificant variables and retrain models with thesignificant features)

Model Tuning ( Uses GridSearch or some hyperparameter tuning to find the best parameters for the model; The tuned model is used to make the final exoplanet prediction)

Model Accuracy (Model scores greater than 85% accuracy on test data)

Reporting (README compares each of the models’ performances and predictions. README summarizes the findings and makes assumptions based on the data and their
models. README discusses the predictions of the possible exoplanets with their models.
 
