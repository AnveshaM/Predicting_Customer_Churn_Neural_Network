# Predicting_Customer_Churn_Neural_Network
A Comparative Study in Customer Churn Prediction through Multilayer Perceptrons and Support Vector Machines
The purpose of this project is to provide a critical assessment of two algorithm models used in a supervised pattern recognition job for customer churn prediction. 
Feedforward Multilayer Perceptron (MLP) and Support Vector Machines are the two algorithms being compared (SVM). 
Hyperparameters of the base models are tuned and optimised by cross-validated grid search. 
The best-evaluated models are compared using Confusion Matrix and Receiver Operating Curves(ROC). 
For this classification task, the MLP model had better performance.

Dataset - 
This data set is taken from Kaggle and contains information about a bank's customers, with the target variable indicating whether the customer left the bank (closed his account) or remained a customer. It contains 10001 customer data points with 14 attributes. There are no "null" values in the dataset. The two categorical features are encoded into numerical features. 
All the features are scaled using the MinMaxScaler(). The target column had values 0 for Not Exited and 1 for Exited. Row Number, Customer Name and Surname are dropped from the dataset as they are not needed in the analysis. There is a class imbalance in the dataset.
Out of the 10001 data points, 6356 data points are customers who have not exited while 1644 data points are of customers who have exited. About 79.63% of the data belong to 'Not Exited' customers while 20.37% of the data belong to 'Exited' customers.

Jupyter Notebook Contents -
1. Initial Exploratory Data Analysis
2. Feature Selection using Logistic Regression 
3. Removing Class Imbalance using SMOTE + ENN hybrid technique
4. MultiLayer Perceptron and Hyperparameter Tuning 
5. Support Vector Machines and Hyperparameter Tuning 
6. Plotting ROC curves 
7. Voting Classifier (Additional Technique to get the best out of the two models)

Repository Contents :
1. Churn_Modelling.csv - CSV file containing the dataset.
2. Predicting_Customer_Churn_Neural_Network.html - HTML version of the Jupyter Notebook 

