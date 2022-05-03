# Machine Learning Project - Predicting Sales

## Authors
- Leonardo de Figueiredo
- Filipa Alves
- Leonor Candeias
- J. Daniel Conde
- Helena Oliveira

Master in Data Science and Advanced Analytics (Nova IMS, Lisbon) - Winter 2022

## Abstract
With the intention of classifying potential purchases based on their Google Analytics metrics, our project centred itself on creating a predictive model that achieved this with as high an F1-score as possible on the test dataset. We began by completing the requisite data exploration and pre-processing, in which we conducted coherence checks, data splitting, missing values treatment amongst other techniques. We concluded by conducting various feature selection methods as well as oversampled our dataset as it was moderately imbalanced. Our team utilized numerous classifiers; all having been tested with various combinations of datasets using processed and oversampled data as well as data including outliers. The classifier that yielded the best results was the stacking classifier with an F1-score of 0.671 composed of the Neural Network, Logistic Regression, SVM and Random Forest.

## Introduction
As the team of data scientists hired, we have been tasked with the creation of a predictive model capable of predicting the probability of any given prospective customer converting to a sale, through the company’s online sales channel. Our team aims to achieve this by way of applying several supervised learning techniques to a dataset comprising of an initial 9999 records, each containing standard Google Analytics metrics as features, with the target variable being whether a prospective customer converted to a sale, designated by the variable “Buy”. Our aim to achieve the highest F1-score possible, testing our results against a ground truth set of unseen records.

#### Grade: 16.5/20
