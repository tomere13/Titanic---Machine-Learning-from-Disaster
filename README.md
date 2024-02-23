# Titanic Survival Prediction

This repository contains a solution for the Titanic Survival Prediction competition on Kaggle. The goal of this competition is to use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

## Dataset

The dataset is provided by Kaggle and includes different kinds of information about the passengers such as their age, sex, passenger class, the fare they paid, and whether they survived or not.

## Solution

The solution uses a RandomForestClassifier from sklearn. The code includes preprocessing steps for both numeric and categorical features. The numeric features are normalized and the categorical features are encoded as one-hot vectors.

Feature engineering is applied to create new features from the existing ones. For example, a 'Title' feature is extracted from the 'Name' column, a 'FamilySize' feature is created from 'SibSp' and 'Parch', and an 'IsAlone' feature is created to indicate whether the passenger was alone or not.

GridSearchCV is used to tune the hyperparameters of the model. The best model is then used to make predictions on the test set.

## Usage

1. Clone this repository.
2. Download the dataset from the Titanic competition page on Kaggle.
3. Run the Python script to train the model and make predictions.

## Results

The performance of the model can be evaluated by submitting the predictions to Kaggle.

## License

This project is licensed under the MIT License.
