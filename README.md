This Readme explains the intent and usage of this project

The project uses pandas library and python as main technology . sklearn library is imported for various Classifiers like LogistcRegression ,SVC, KNN , DecisionTree.

This Data Science / ML project intends to Credit Card fraud data , create ML classifeir models which can be used to predict class as Yes or No for fraud causing. The Data set is analysed and formatted first to remove unwanted and erroneous factors. The numerical and categorical data is also handled such that they can be used together for training the model.

The approach taken is to pick single parameter first and use liner Regression to observe the predictions.  
The dataset is split into train and test data set and models are trained and values are predicted. The Mean Sqaured Error and HyperParameter like alpha are calculated and fine tuned.

Different set of data/features are iterated through with various models.
 
Basic DUmmy model provides the base accuracy needed.
The LogisticRegression , KNN , DecisionTrees and SVC are used to fit and predict.

GridSearch CV is used to fine tune the hyper paramaters to find the best estimator.

The model and features suggested are determined on accuracy and processing speed of the model .


Ensemble techniques and prediction scores:

RandomForestClassifier
print(oob_scores)
0.6838154863443716[n_tree = 1 - ]
0.9946116103617466[n_tree = 10]

GradientBoostingRegressor
0.9986728211259185


BaggingClassifier
0.9996541394814437

AdaBoostClassifier 
0.9995779329265075

Acccuracy obtained from Classifiers are not much different from ensemble techniques appied.
