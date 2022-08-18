# Module 17

## Overview
The purpose of this analysis is to experiment with different sampling algorithms for a credit risk classification problem.

## Results
* Naive Random Oversampling:
  * Balanced accuracy: 62.5%
  * Precision: 99%
  * Recall: 66%
* SMOTE Oversampling:
  * Balanced accuracy: 63.6%
  * Precision: 100%
  * Recall: 66%
* Cluster Centroids Undersampling:
  * Balanced accuracy: 52.7%
  * Precision: 100%
  * Recall: 46%
* SMOTEENN Over- and Under- Sampling:
  * Balanced accuracy: 63.7%
  * Precision: 99%
  * Recall: 57%
* Balanced Random Forest Classifier:
  * Balanced accuracy: 78.8%
  * Precision: 99%
  * Recall: 91%
* Easy Ensemble AdaBoost Classifier:
  * Balanced accuracy: 92.5%
  * Precision: 99%
  * Recall: 94%

See the notebooks in this repository for outputs and code supporting the above results.

## Summary
Overall, undersampling seemed to actually reduce performance, while the remaining sampling methods did not affect the performance of the models significantly.
Moreover, the two imbalanced models performed significantly better than the sampling methods, with the Easy Ensemble AdaBoost Classifier significantly outperforming everything else.
Overall, I recommend using the Easy Ensemble AdaBoost Classifier, because it has the highest recall and balanced accuracy over the other models by far.
All models had high precision.
