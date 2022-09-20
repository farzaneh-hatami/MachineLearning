# Detecting Parkinkson disease using signal of speach data
## Description:
In this project several Machine Learning have been used on signal of speach data to detect parkinksn diseas as a binary classification task.
we used data from following article by Jefferson S.Almeida et al:

"Detecting Parkinson’s disease with sustained phonation and speech signals using machine learning techniques".

For data preprocessing and dimentionality reduction, we implemented the methods that have been used in this paper.
For model training several methods have been implemented as you can see below:
1. Generative classifier
- Parzen windows
- KNN
- GMM

2.Discriminative classifier:
* Logistic regression
* SVM
* Decision Tree
* KNN(K=1)
* MLP 
To reaching better perforamnce we also implemented ensemble models.

3. ensemble models
* RandomForest
* Bagging with Decision Tree
* Bagging with SVM
* Bagging with KNN
* Adaboost
* voiting classifier with different classifiers


## Result:
The best performance was related to the ensemble model using KNN algorithm, whose accuracy was equal to 96,10%. The results of the rest of the models are available in the table below.


            | Algorithms      | Accuracy% |
------------| ----------- | ----------- |
 Generative | Parzen windows
 Classifier | KNN
            | GMM
------------|-----------------------------
            | Logistic regression      | 87,23       |
            | SVM   | 93,97        |
            | Decision Tree   | 84,04        |
            | KNN(K=1)   | 94,33        |
            | MLP   | 91,84        |
            | RBF   | 93,26        |
            | Ensemble   | 96,10        |
