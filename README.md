# diabetes-classification
This repository contains my first machine learning project designed to address diabetes classification using supervised learning techniques. The data used for this problem is sourced from Kaggle.


About Dataset: This dataset is originally from the National Institute of Diabetes and Digestive and Kidney
Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes,
based on certain diagnostic measurements included in the dataset. Several constraints were placed
on the selection of these instances from a larger database. In particular, all patients here are females
at least 21 years old of Pima Indian heritage.2
From the data set in the (.csv) File We can find several variables, some of them are independent
(several medical predictor variables) and only one target dependent variable (Outcome).


About Project: After preparing the dataset, I proceeded to test different models for this classification problem, such as Support Vector Machine, Logistic Regression, Random Forest and Gradient Boosting. After experimenting with the models, I analyzed that the one that produced the best results was the Gradient Boosting model, so I began tuning its hyperparameters, achieving an accuracy of 0.85 for the dataset. I used the scikit-learn library for modeling and its functions, as well as matplotlib for visualizing both the confusion matrix and representing data classification in 3D using PCA techniques.
