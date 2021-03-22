# Credit_Risk_Analysis
Creating models analyzing credit risk


## Background
Loans are an essential part of modern society

On one hand loans create revenue not the other hand there is a risk involved if loan owners do not meet their financial obligations
Creating models can help us analyze the risk involved before granting a loan. 
Machine Learning helps us analyze accuray, sensitivy, oversampling, and underspamling, among other useful algorithms. 
Machine learning teaches us how to deal withthe personal aspect a well.


## Objectives

* Explain how a machine learning algorithm is used in data analytics.
* Create training and test groups from a given data set.
* Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
* Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
* Compare the advantages and disadvantages of each supervised learning algorithm.
* Determine which supervised learning algorithm is best used for a given data set or scenario.
* Use ensemble and resampling techniques to improve model performance.
 


## Method
The purpose of this analysis was to create a supervised machine learning model that could accurately predict credit risk. In order to complete this task, I used 6 different methods, which are:
1. Naive Random Oversampling
2. SMOTE Oversampling
3. Cluster Centroid Undersampling
4. SMOTEENN Sampling
5. Balanced Random Forest Classifying
6. Easy Ensemble Classifying
Through each of these methods, I split my data into training and testing datasets, and compiled accuracy scores, confusion matries, and classification reports as my results.

## Results

### Naive Random Oversampling
![naive](https://github.com/Solrys/Credit_Risk_Analysis/blob/main/visuals/Screen%20Shot%202021-03-21%20at%2011.24.13%20PM.png)
* Accuracy Score: 67.4%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 72%
* Recall Low Risk: 63%

### SMOTE Oversampling
![oversampling](https://github.com/Solrys/Credit_Risk_Analysis/blob/main/visuals/Screen%20Shot%202021-03-22%20at%2012.03.43%20AM.png)
* Accuracy Score: 66.2%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 66%
* Recall Low Risk: 66%

### Cluster Centroid Undersampling
![under](https://github.com/Solrys/Credit_Risk_Analysis/blob/main/visuals/Screen%20Shot%202021-03-22%20at%2012.05.56%20AM.png)
* Accuracy Score: 51.3%
* Precision High Risk: 0%
* Precision Low Risk: 100%
* Recall High Risk: 61%
* Recall Low Risk: 42%

### SMOTEENN Sampling
![smoteen](https://github.com/Solrys/Credit_Risk_Analysis/blob/main/visuals/Screen%20Shot%202021-03-22%20at%2012.07.46%20AM.png)
* Accuracy Score: 68.1%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 76%
* Recall Low Risk: 60%

### Balanced Random Forest Classifying
![balance](https://github.com/Solrys/Credit_Risk_Analysis/blob/main/visuals/Screen%20Shot%202021-03-22%20at%201.00.28%20AM.png)
* Accuracy Score: 64.8%
* Precision High Risk: 56%
* Precision Low Risk: 100%
* Recall High Risk: 30%
* Recall Low Risk: 100%

### Easy Ensemble Classifying
![ensemble](https://github.com/Solrys/Credit_Risk_Analysis/blob/main/visuals/Screen%20Shot%202021-03-22%20at%201.17.20%20AM.png)
* Accuracy Score: 92.3%
* Precision High Risk: 6%
* Precision Low Risk: 100%
* Recall High Risk: 91%
* Recall Low Risk: 94%

rewrite.. 
Summary
This analysis is trying to find the best model that can detect if a loan is high risk or not. Becasue of that, we need to find a model that lets the least amount of high risk loans pass through undetected. That correlating statistic for this is the recall rate for high risk. Looking through the different models, the ones that scored the highest were:

Easy Ensemble Classifying (91%)
SMOTEENN Sampling (76%)
Naive Random Oversampling (72%)
While this is the most important statistic that is pulled from this analysis, another important statistic is recall rate for low risk as it shows how many low risk loans are flagged as high risk. Looking through the different models, the ones that scored the highest were:

Balanced Random Forest Classifying (100%)
Easy Ensemble Classifying (94%)
After taking these two statistics over the others, we can look at the accurary score to get a picture of how well the model performs in general. The models with the highest accuracy scores were:

Easy Ensemble Classify (92.3%)
SMOTEENN Sampling (68.1%)
Balanced Random Forest Classifying (64.8%)
After factoring in these three main statistics, the model that I would recommend to use for predicting high risk loans is the Easy Ensemble Classifying model.




