# FIES Student Loan Default Prediction
## Project Overview
The primary focus of this project is to leverage machine learning algorithms to predict loan default probabilities within the Brazilian student loan program, FIES (Financiamento Estudantil). As the largest student loan program in Brazil, FIES provided loans to over 2 million students from 2009 to 2015. The project employs five machine learning methods—logistic regression, decision tree, random forest, linear support vector classification (SVC), and artificial neural networks (ANN)—with random forest and ANN yielding the highest AUC scores to date.

The ultimate aim is to discern the best performing models and the predictive power of various features. Additionally, the project seeks to engage in discussions about the ethical, social, and economic implications of the obtained results.

## Code Modules
The codebase is divided into a series of modules, each with a specific focus:

### Module00: This module is dedicated to data preparation and preliminary feature analysis.

### Module01: This module executes the machine learning methods and provides performance measures for the classification tasks.

### Module02 a-c: These modules apply random grid search and sampling strategies to determine the hyperparameters that yield the best AUC value.

### Module03: This module implements a composite predictor using a combination of the three best performing models: ANN, RF, and LR. It also evaluates the significance of the features.

## Conclusions
The results indicate that Artificial Neural Networks consistently outperform other models in each context. Furthermore, both up-sampling and down-sampling strategies did not produce significant improvements in model performance in terms of AUC score. As for feature importance, loan-related characteristics were found to be more crucial predictors of default than individual characteristics.
