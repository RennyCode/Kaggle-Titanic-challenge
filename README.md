## Kaggle Titanic challenge

The project is an entry for the Titanic challenge in the Kaggle website, in this challenge we are tasked with creating a pridiction model to predict the survival of an individual.
The work has two parts, matching my own proggress in the subject, the fist part includes the data preperations and usagle of SGD and MLP models for prediction, the seconde part builds upon the the work of the first part and makes use of more advance methonds and models. 

## Workflow
1. Load the data. 
2. Clean and sort data.
3. Create and train modles.
4. Find best version of our model.
5. Submit the best performing model to the competition.

## Liberies
- sklearn
- numpy
- pandas

## Data handling:
- earse feature with high precentage of empty rows
- filling missing values (by median or catigorical)
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

## Theory - TLDR
-MPL, Multilayer perceptron classifier
-SGD, Stochastic gradient descent classifier
-knn based on similarity or distance between the input to the known examples.
-Naive Bayes uses probabilities calculation for classification.
-Feature Selection uses a greedy methonds to create mutiple models with different features and select the best preforming one.
-k-Fold divides the data to k chunks and each model uses a different chuck as the validation.
-Ensemble, the idea of using multiple models to base your prediction on.
-Baggin, combining repetitions with combinations to create multi-sets of the original data.
-Boosting, iterative strategy for adjusting an observation's weight based on the previous classification.
-Grindsearch, sample consistinly along in a specific range to find the best parameters
-randomsearch, sample randomly in a range to find the best parameters
