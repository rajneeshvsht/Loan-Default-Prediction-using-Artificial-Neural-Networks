# Loan-Default-Prediction-using-Artificial-Neural-Networks
Loan default prediction is a common problem in the financial industry, as it can help lenders or banks identify borrowers who are likely to default on their loans. This information can be further used to adjust loan terms/conditions, reserve additional funds to cover potential losses, or even deny/refuse loans to high-risk borrowers. In this article, we will develop a machine learning-based solution to predict loan default.

__Aim__ - The goal of this project is to build a __Deep Learning__ model that can predict if a person will default on the loan based on the loan and personal information provided. The model is intended to be used as a reference tool for the client and the financial institutions to help make decisions on issuing loans, so that the risk can be lowered, and the profit can be maximized.

# Steps Performed
1.	Checking for null values present in dataset.
2.	Univariate Analysis of all feature columns. Observations of same has been mentioned in source code file.
3.	Bivariate Analysis of all feature columns. Observations of same has been mentioned in source code file.
4.	Multivariate Analysis of all feature columns. Observations of same has been mentioned in source code file.
5.	Separating and Scaling the Numerical Columns of dataset using Standard Scaler.
6.	Separating the categorical columns of dataset.
7.	Concatenating Numerical and Categorical columns.
8.	Creating dummies for the ‘Purpose’ Column.
9.	Separating Features and Target variable.
10.	Applying SMOTE technique to rectify class imbalance in Target variable.
11.	Dividing the data into training and testing.
12.	ANN Model building.
13.	Analyzing accuracy, loss, precision and recall curves.
14.	Saving the model.


# Tools and Technologies used
1) __Language__ : Python
2) __IDE__ : Jupyter Notebook
3) __Pandas__ : For loading the dataset and performing data wrangling
4) __Matplotlib__: For data visualization.
5) __Seaborn__: For data visualization.
5) __NumPy__: For some math operations in predictions.
6) __Sklearn__: For the purpose of analysis,prediction and evaluation
7) __TensorFlow and Keras__: For building ANN model


# Conclusion

Finally a Deep Learning model has been prepared to predict Loan Default with an accuracy of __82%.__
