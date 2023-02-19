# Sampling
Assignment on Sampling for UCS654

## Description - 
This assignment has a dataset regarding credit cards. It is a binary classification problem. The dataset is imbalanced and hence it is balanced by using random over sampling technique. After balancing the dataset, different sampling techniques are used and 5 different models have been applied to get the accuracy on testing set. The dataset is divided into a 25-75 ratio of testing and training set.

## Methodology -
1. Balancing Dataset
2. Creating different types of samples
3. Training different machine learning models
4. Testing the models
5. Analysing the Result obtained

## Final Table -

|    |  Models | Simple Random | Stratified | Systematic | Cluster | Multi-Stage |
|----|----------|-------|-------|-----------|------------|---------|
| 0  | Logistic Regression	| 91.011236	| 91.326531 | 79.220779 | 91.304348 | 78.0 |
|  1 | Decision Tree | 98.501873 | 96.428571 | 92.207792 | 97.391304 | 98.0 |
| 2  | Random Forest | 98.876404 | 98.979592 | 96.103896 | 97.391304 | 98.0 |
| 3  | Gaussian Naive Bayes	| 76.029963 | 75.000000 | 77.922078 | 72.173913 | 66.0 | 
| 4 | KNN | 98.127341 | 95.918367 | 92.207792 | 85.217391 | 72.0 |

## Discussion -
On comparison, we can see that when we apply Random Forest Algorithm on Stratified sampling, we get the highest accuracy i.e. 98.97%.

## Submitted By -
Name : Paavan Singh Sayal

Roll No. : 102003738

Sub-Group: 3CO26
