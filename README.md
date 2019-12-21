# Predict-the-criminal

Hackerearth Problem Link: https://www.hackerearth.com/challenge/competitive/predict-the-criminal/machine-learning/predict-the-criminal/

This repository contains some basic machine learning algorithms that can be used to solve the problem. It can be used as a starting guide or as baseline solution for the problem.

## Problem Statement

There has been a surge in crimes committed in recent years, making crime a top cause of concern for law enforcement. If we are able to estimate whether someone is going to commit a crime in the future, we can take precautions and be prepared. You are given a dataset containing answers to various questions concerning the professional and private lives of several people. A few of them have been arrested for various small and large crimes in the past. Use the given data to predict if the people in the test data will commit a crime. The train data consists of 45718 rows, while the test data consists of 11430 rows.

## Exploratory Data Analysis
Exploratory Data Analysis.ipynb contains initial exploration of the data.

## Approach Used for Feature Selection

* Removing Features with Low Variance <br />
feature selection(low variance).ipynb contains code for removing the features with low variance. It is a simple baseline approach that removes the features that have variance below a certain threshhold.

* Univariate Feature Selection <br />
feature selection(univariate feature selection).ipynb contains code for selecting features using SelectKBest that removes all but the K highest scoring features. Chi sqaure test is used to find out the best features.

## Machine Learning Algorithms used
* Support Vector Machines
* Random Forest Classifier
* Extra tress Classifier
* K Nearest Neighbours Classifier

## Accuracy : 0.946
