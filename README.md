Customer Churn Prediction

This project is an ML classification problem geared towards building a classifier model which would help a telecom corporation to predict whether a customer will churn or not.

This dataset contains 243,553 rows of customer data from four major telecom partners of India: Airtel, Reliance Jio, Vodafone, and BSNL. The dataset includes various demographic, 
location, and usage pattern variables for each customer, as well as a binary variable indicating whether the customer has churned or not.
After Business and Data Understanding, Exploratory Data Analysis was conducted .Then,the feature processing for our ML modelling stage began. Numerical features or variables were scaled using the Standard Scaler
whereas the categorical columns were encoded using getdummies.At this point the dataset was ready to be used for our ML modelling.
However, it was realized that the target variable was imbalanced.As a result, after splitting dataset into train and evaluation sets, it was necessary to perform an oversampling on the train set using the 
SMOTE technique to increase the count of the minority class in the target variables. 

In this project, 5classifiers were built:

1.KNN
2.Naive Bayes
3.Decision Tree Clasifier
4.Random Forest
5.Logistic Regressor

 The two best performing models were the logistic regression model and the Random forest  classifier.
