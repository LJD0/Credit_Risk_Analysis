# Credit_Risk_Analysis

##### Tools Used

* VSCode 1.78
* Python
  * pandas
  * scikitlearn
  * numpy
  * imblearn

### Overview

To predict the risk of loan defaults using machine learning techniques. The data provided includes results from five different sampling techniques,  The performance of the models is measured using balanced accuracy score, precision, and recall.

The purpose of this analysis is to assess different machine learning models for credit risk prediction. By evaluating the performance of various models, we can determine their effectiveness in identifying high-risk loans and low-risk loans. This analysis will provide insights into the strengths and weaknesses of the four different sampling models; Random Oversampling, Cluster Centroid Undersampling, SMOTE Oversampling, SMOTEENN Combination Sampling, and two classifier models; Balanced Random Forest Classifier, and Easy Ensemble Classifier.

We will look at metrics including, the balanced accuracy score, precision, and recall. These metrics will allow us to make an informed decision on which model will best perform a credit risk analysis.

### Results

|                                    | Random Over Sampler                                          | SMOTE Oversampling                                           | Cluster Centroids                                            | SMOTEENN Sampling                                            | Balanced Random Forest                                       | Easy Ensemble Classifier                                     |
| ---------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Accuracy Score                     | 0.6640                                                       | 0.6556                                                       | 0.5455                                                       | 0.6424                                                       | 0.7885                                                       | 0.9317                                                       |
| Confusion Matrix<br />(True/False) | [[72, 29],<br />[6582, 10522]]                               | [[64, 37],<br />[5514, 11590]]                               | [[67, 34],<br />[9791, 7313]]                                | [[71, 30],<br />[7154, 9950]]                                | [[71, 30],<br />[2153, 14951]]                               | [[93, 8],<br />[983, 16121]]                                 |
| Precision                          | [0.99]- average<br />[0.01]- high risk<br />[1.00]- low risk | [0.99]- average<br />[0.01]- high risk<br />[1.00]- low risk | [0.99]-average<br />[0.01]- high risk<br />[1.00]- low risk  | [0.99]- average<br />[0.01]- high risk<br />[1.00]- low risk | [0.99]- average<br />[0.03]- high risk<br />[1.00]- low risk | [0.99]- average<br />[0.09]- high risk<br />[1.00]- low risk |
| Recall                             | [0.62]- average<br />[0.71]- high risk<br />[0.62]- low risk | [0.68]- average<br />[0.63]- high risk<br />[0.68]- low risk | [0.42]- average<br />[0.66]- high risk<br />[0.43]- low risk | [0.58]- average<br />[0.70]- high risk<br />[0.58]- low risk | [0.87]- average<br />[0.70]- high risk<br />[0.87]- low risk | [0.94]- average<br />[0.92]- high risk<br />[0.94]- low risk |
| F1 Score                           | [0.76]- average<br />[0.02]- high risk<br />[0.76]- low risk | [0.80]- average<br />[0.02]- high risk<br />[0.81]- low risk | [0.59]- average<br />[0.01]- high risk<br />[0.60]- low risk | [0.73]- average<br />[0.02]- high risk<br />[0.73]- low risk | [0.93]- average<br />[0.06]- high risk<br />[0.93]- low risk | [0.97]- average<br />[0.16]- high risk<br />[0.97]- low risk |

### Summary

There is a wide variety of performance between each model. The Easy Ensemble Classifier and the Balanced Random Forest Classifier are the best-performing models, with the balanced accuracy scores, .9317 and .7885 respectively. Both have F1 scores above .9 indicating that the models are able to predict both positive and negative outcomes more accurately.

 The other models, such as Random Oversampling, Cluster Centroid Undersampling, SMOTE Oversampling, and SMOTEENN Combination Sampling, have lower balanced accuracy, precision, and recall scores.

Overall the Easy Ensemble Classifier is best able to predict credit risk. Its ability to combine multple weak learners together allowed it to consistently outperform the other models in terms of accuracy, precision, recall, and F1 score. Its robust performance, balanced predictions, and established effectiveness make it the best recommendation for our credit risk assessment tasks.
