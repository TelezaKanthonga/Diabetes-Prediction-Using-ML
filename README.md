# Machine Learning Model for Diabetes Classification in MATLAB

This repository contains a machine learning model implemented in MATLAB for the purpose of classification. 
The model was trained using a dataset and the `fitcsvm` algorithm provided by MATLAB's Statistics and Machine Learning Toolbox. 

## Dataset

The dataset used in this project is Prima Indians Diabetes Database.

## Model Training

The model was trained using a single CPU machine. The training process involved splitting the dataset into training and testing sets, 
and using the `fitcsvm` algorithm to train a support vector machine (SVM) classifier on the training set. The SVM hyper parameters were
optimized using a grid search approach with cross-validation. 

## Model Evaluation

The accuracy of the trained model was evaluated on the testing set, and an accuracy of 80.86% was achieved.
The results indicate that the model is able to classify the samples with a reasonable accuracy.

## Usage

To use the trained model for classification of new samples, you can load the model from the provided MAT file, and call the `predict` function on the new samples.

## Acknowledgments

This project was inspired by a tutorial video on YouTube and was implemented using MATLAB's Statistics and Machine Learning Toolbox.
The tutorial video can be found at: https://www.youtube.com/watch?v=lY7C_lbe1dA.
