# Classification Project 

Predict metal or rock objects from sonar return data.

In this case a predictive modeling machine learning is applied. Important knoelwdge from this case:

- [x] How to work through a classification predictive modeling problem end-to-end.
- [x] How to use data transforms to improve model performance.
- [x] How to use algorithm tuning to improve model performance.
- [x] How to use ensemble methods and tuning of ensemble methods to improve model performance.

## Problem Definition

The focus of this project will be the Sonar Mines vs Rocks dataset1. The problem is to predict metal or rock objects from sonar return data. Each pattern is a set of 60 numbers in the range 0.0 to 1.0. Each number represents the energy within a particular frequency band, integrated over a certain period of time. The label associated with each record contains the letter R if the object is a rock and M if it is a mine (metal cylinder). The numbers in the labels are in increasing order of aspect angle, but they do not encode the angle directly.

## Summary

- [x] Analyze Data (same scale but different distributions of data)
- [x] Evaluate Algorithms (KNN looked good)
- [x] Evaluate Algorithms with Standardization (KNN and SVM looked good)
- [x] Algorithm Tuning (K=1 for KNN was good, SVM with an RBF kernel and C=1.5 was best)
- [x] Ensemble Methods (Bagging and Boosting, not quite as good as SVM)
- [x] Finalize Model (use all training data and confirm using validation dataset) 


