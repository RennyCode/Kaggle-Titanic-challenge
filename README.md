## Kaggle Titanic challenge

The project is an entry for the Titanic challenge in the Kaggle website, in this challenge we are tasked with creating a classification model to predict the survival of an individual.
The work has two parts, matching my own progress in the subject, the first part includes the data preparations and usage of SGD and MLP models for prediction, the second part builds upon the work of the first part and makes use of more advance methods and models. 

## Workflow
1. Load the data. 
2. Clean and sort data.
3. Create and train models.
4. Find the best version of our model.
5. Submit the best performing model to the competition.

## Libraries
- sklearn
- numpy
- pandas

## Data handling:
- erase feature with high  of empty rows
- filling missing values (by median or categorical)
- removing features with low correlation to our target
- test the grouping features with high correlation 

## Models
- MPL
- SGD
- KNN
- Naive Bayes

## Methods
- Feature Selection
- K-Fold
- Ensembles: Bagging, Boosting
- Hyper-Parameters Searches: Gridsearch, randomSearch

## Technical Terms - TLDR
- MPL, Multilayer perceptron classifier.
- SGD, Stochastic gradient descent classifier.
- knn based on similarity or distance between the input to the known examples.
- Naive Bayes uses probabilities calculation for classification.
- Feature Selection uses a greedy methods to create multiple models with different features and select the best preforming one.
- k-Fold divides the data to k chunks, and each model uses a different chuck as the validation.
- Ensemble, the idea of using multiple models to base your prediction on.
- Bagging, combining repetitions with combinations to create multi-sets of the original data.
- Boosting, iterative strategy for adjusting an observation's weight based on the previous classification.
- Grindsearch, sample consistently along in a specific range to find the best parameters.
- randomsearch, sample randomly in a range to find the best parameters.
