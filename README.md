# Churn-Modelling
A machine learning model capable of modelling churn based on the various individual factors.

# Dataset
The dataset 'Churn_data.csv' was collected from Kaggle.
The columns in the csv file are as follows:
customerID,
gender,
SeniorCitizen,
Partner,
Dependents,
tenure,
PhoneService,
MultipleLines,
InternetService,
OnlineSecurity,
OnlineBackup,
DeviceProtection,
TechSupport,
StreamingTV,
StreamingMovies,
Contract,
PaperlessBilling,
PaymentMethod,
MonthlyCharges,
TotalCharges,
Churn.

Churn modelling is an extrapolation of the existing data to predict what category of employees show higher tendency of quitting their jobs.
It is a predictive problem which can be solved by machine learning algorithms.

# MODELS

After the data was visualized with several powerful methods leveraged from the matplotlib library of python, we dive right into the machine learning models.

#1: Random Forest Classification:
This method fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting(sklearn).

#2: Logistic Regression:
It is a maximum entropy classifier. The possibilities describing the outcome of a single trial are modeled using a logistic function

#3: AdaBoost Classifier:
Fit a sequence of weak learners on a contantly modified versions of the data.

#4: Deep learning model:
A fully connected model using tensorflow that is supposedly more powerful than sklearn models.
Using tf.keras.layers.Dense model.


In a comparison among the models, we obseve that the AdaBoost method gave the highest accuracy, to which, one conclusion can be made. The data is complex and needs a complex algorithm to resolve the complexities and difficulties.
