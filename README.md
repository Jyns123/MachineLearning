Overview
Dataset: EEG of genetic predisposition to alcoholism
This data arises from a large study to examine EEG correlates of genetic predisposition to alcoholism. It contains measurements from 64 electrodes placed on subject's scalps which were sampled at 256 Hz (3.9-msec epoch) for 1 second.

There were two groups of subjects: alcoholic and control. Each subject was exposed to either a single stimulus (S1) or to two stimuli (S1 and S2) which were pictures of objects chosen from the 1980 Snodgrass and Vanderwart picture set. When two stimuli were shown, they were presented in either a matched condition where S1 was identical to S2 or in a non-matched condition where S1 differed from S2.

The time series record the voltage over time and are averaged over 10 trials for the single stimulus condition. There were 122 subjects and each subject completed 120 trials where different stimuli were shown. The electrode positions were located at standard sites (Standard Electrode Position Nomenclature, American Electroencephalographic Association 1990). Zhang et al. (1995) describe in detail the data collection process.

Instructions

Analyze the features of the dataset pertinent to the problem you selected in the previous step. Review the following libraries to extract features of time series. Justify your decisions.

PyTS:        https://pyts.readthedocs.io/en/latest/modules/transformation.html
TsFresh:     https://github.com/blue-yonder/tsfresh

Implement two classification methods (e.g. logistic regression, SVM, KNN, decision trees and so on). Justify your decisions.

Report the classification metrics: F-Score, Accuracy, Confusion Matrix. Analyze and discuss the results of each method.