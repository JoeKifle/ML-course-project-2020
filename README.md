# Machine Learning 2020
This project is for the course Machine Learning course(654AA) at university of Pisa A.Y 2020/2021.

The project contains two different datasets. Namely [Monk](https://archive.ics.uci.edu/ml/datasets/MONK's+Problems) and Cup dataset. The Monk dataset is the bench mark dataset used to compare different models. Since our aim on this project is to try to explore available model and compare their performaces, this dataset was a good start for us. The cup dataset is provided to us by our Professor and its a multi-target regression task.


## Models for the Monk in a nutshel.

1. MLP NN (Multi Layer perceptron neural networks)
2. SVC (Support Vector Machine Classifier)
3. KNN classifier

## Models for the CUP in a nutshel.

1.  RR(Ridge Regressor)
2.  SVR(Support vector regressor)
3.  KNR(K neighbors regressor)
4.  RFR(Random forest regressor)
5.  DTR(Decision tree regressor)
6.  ETR(Extra tree regressor)
7.  LR(Lasso regressor)
8.  RR(Ridge regressor)
9.  ENR(Elastic net regressor)
10. BRR(Bayesian ridge regressor)
11. SGDR(Stochastic gradient descent regressor)
12. GBR(Gradient boosting regressor)
13. MPLR(Multi-layer Perceptron regressor). 

## Summary

After optimizing and evaluating each model performance we selected 5 of them. We then, applied the 5 estimators as a transformer to our dataset and used one final model(KNN) to make the final prediction. Can be found at ChainedRegressors.ipynb
