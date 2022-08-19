# Credit Risk Analysis

## Project Overview
Performed data analysis on credit card credit dataset from LendingClubs, a peer-to-peer lending services company. 
1) First, we'll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm.  
2) Then, we'll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. 
3) Finally, we'll compare the new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Resources
- Data Source: LoanStats_2019Q1.csv
- Software: Jupyter Notebook, sklearn, imblearn

## Summary

### <u>Naive Random Oversampling</u>

![Oversampling](https://github.com/frlinh/credit-risk-analysis/blob/31ec26b79ae17c4fe7468609ef09a0b1548261e2/Resources/Oversampling.png)
- The balanced accuracy score is 0.64
- The recall of high-risk classification is 0.61
- The recall of low-risk classification is 0.66

### <u>SMOTE Oversampling</u>

![SMOTEoversampling](https://github.com/frlinh/credit-risk-analysis/blob/31ec26b79ae17c4fe7468609ef09a0b1548261e2/Resources/SMOTEoversampling.png)
- The balanced accuracy score is 0.64
- The recall of high-risk classification is 0.63
- The recall of low-risk classification is 0.69

### <u>Combination (Over and Under) Sampling</u>

![Combosampling](https://github.com/frlinh/credit-risk-analysis/blob/31ec26b79ae17c4fe7468609ef09a0b1548261e2/Resources/Combosampling.png)
- The balanced accuracy score is 0.54
- The recall of high-risk classification is 0.72
- The recall of low-risk classification is 0.57

### <u>Undersampling</u>

![Undersampling](https://github.com/frlinh/credit-risk-analysis/blob/31ec26b79ae17c4fe7468609ef09a0b1548261e2/Resources/Undersampling.png)
- The balanced accuracy score is 0.64
- The recall of high-risk classification is 0.69
- The recall of low-risk classification is 0.40

### <u>Ensemble Classifier</u>

![Ensembling](https://github.com/frlinh/credit-risk-analysis/blob/31ec26b79ae17c4fe7468609ef09a0b1548261e2/Resources/Ensembling.png)
- The balanced accuracy score is 0.93
- The recall of high-risk classification is 0.92
- The recall of low-risk classification is 0.94

# <u>Conclusion</u>
