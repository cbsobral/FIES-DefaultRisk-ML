# The Project 

Our goal is to employ machine learning algorithms to predict loan default probabilities in the context of a Brazilian student loan program called FIES (Financiamento Estudantil). FIES is the most significant student loan program in Brazil. For instance, between 2009 and 2015, more than 2 million students got a loan through FIES. For the initial runs, we employ 5 methods: logistic regression, decision tree, random forest, linear support vector classification (SVC), and artificial neural networks (ANN). Random forest and ANN achieved the highest AUC scores so far. 

Our final objective is to find out which are the best performing models for this task as well as the predictive power of the features. We also expect to discuss the ethical, social, and economic implications of the results obtained.


## Module00
In this module we prepare the data and perform an initial analysis of the features. 

## Module01
In this module, we implement the machine learning methods and provide performance measures for the classification tasks. 

## Module02 a-c
In module 2 a-c, we implement random grid search and sampling strategies to find out which hyperparameters give the best AUC value. 

## Module03
Here we implement a composite predictor consisting of a combination of the three best performing individual models: ANN, RF and LR. This module also evaluates the significance of the features. 

# Conclusions
The overall results showed that Artificial Neural Networks performed best in each context. Moreover, up-sampling and down-sampling strategies did not noticeably improve the performance of the models in terms of AUC score. Finally, with respect to feature importance, we found that loan-related characteristics - rather than individual characteristics - are the most important predictors of default.
