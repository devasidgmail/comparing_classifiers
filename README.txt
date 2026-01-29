Comparing Classifiers

This is a practical application to compare the performance of different models of classifiers (K Nearest Neighbor, Logistic Regression, Decision Trees and Support Vector Machines) . This project predicts whether a customer will subscribe to a bank term deposit using demographic, financial, and campaign-related features. The dataset is highly imbalanced, so the focus is on F1 score optimization rather than accuracy alone.

The pipeline begins with preprocessing. Numerical features are scaled, categorical variables are one-hot encoded, and all transformations are applied consistently using a ColumnTransformer. 


The following classification models are implemented and compared. 
Logistic Regression
Decision Trees
K-Nearest Neighbors
Support Vector Machines
A baseline model is first established, followed by hyperparameter tuning. Each model is evaluated and metrics tabulated. 

The results show that tuning significantly improves F1 score, even when accuracy does not increase.
This project showcases practical application of feature engineering, model evaluation, handling imbgit push alanced data, and performance optimization.

Summary 
-------
While the SVM and KNN models achieved higher overall accuracy, the recall was not good. The Tuned Logistic Regression and Tuned Decision Tree models are more effective for the business objective because they significantly improved recall and F1 scores, making them better at identifying potential customers despite a lower overall accuracy.


https://github.com/devasidgmail/comparing_classifiers
