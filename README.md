Polynomial regression
================

Summary
--------
This program predicts the amount of water flowing out of a dam from the water level in a certain resevoir. A predict function is constructed using regularized polynomial regression after training by ex5data1.mat. Two separate sets of data were reserved for test and cross-validation sets. These sets, along with the training set was used to plot the learning curve to study the properties of bias and variance.

LinearRegCostFunction
--------
This method returns a regularized linear regression cost function and corresponding gradient.

LearningCurve
------
This method generates a learning curve.

PolyFeature 
---------
This method maps the provided data into polynomial feature space.

ValidationCurve
------
This method plots a curve from the cross validation set.


Below are the scripts provided by the course:
> ex5.m
> featureNormalization.m
> fmincg.m
> PlotFit.m
> trainLinearReg.m
