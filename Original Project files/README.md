# Credit_Risk_Analysis

### Overview

    To predict the risk of loan defaults using machine learning techniques. The data provided includes results from five different sampling techniques, including Random Oversampling, Cluster Centroid Undersampling, SMOTE Oversampling, SMOTEENN Combination Sampling, and a Balanced Random Forest Classifier and Easy Ensemble Classifier. The performance of the models is measured using balanced accuracy score, precision, and recall.

### Results

- Random Oversampling:
  - Balanced Accuracy Score: 0.65
  - Precision (high risk): 0.01
  - Recall (high risk): 0.72
  - Precision (low risk): 1.00
  - Recall (low risk): 0.59
- Cluster Centroid Undersampling:
  - Balanced Accuracy Score: 0.54
  - Precision (high risk): 0.01
  - Recall (high risk): 0.69
  - Precision (low risk): 1.00
  - Recall (low risk): 0.40
- SMOTE Oversampling:
  - Balanced Accuracy Score: 0.66
  - Precision (high risk): 0.01
  - Recall (high risk): 0.63
  - Precision (low risk): 1.00
  - Recall (low risk): 0.69
- SMOTEENN Combination Sampling:
  - Balanced Accuracy Score: 0.64
  - Precision (high risk): 0.01
  - Recall (high risk): 0.71
  - Precision (low risk): 1.00
  - Recall (low risk): 0.57
- Balanced Random Forest Classifier:
  - Balanced Accuracy Score: 0.79
  - Precision (high risk): 0.03
  - Recall (high risk): 0.70
  - Precision (low risk): 1.00
  - Recall (low risk): 0.87
- Easy Ensemble Classifier:
  - Balanced Accuracy Score: 0.93
  - Precision (high risk): 0.09
  - Recall (high risk): 0.92
  - Precision (low risk): 1.00
  - Recall (low risk): 0.94

### Summary

    It appears that the Easy Ensemble Classifier and the Balanced Random Forest Classifier are the best-performing models, with the highest balanced accuracy scores and the highest precision and recall scores for both the high-risk and low-risk classes. The other models, such as Random Oversampling, Cluster Centroid Undersampling, SMOTE Oversampling, and SMOTEENN Combination Sampling, have lower balanced accuracy scores and lower precision and recall scores. Therefore, it would be advisable to use the Easy Ensemble Classifier or the Balanced Random Forest Classifier for this classification task.
