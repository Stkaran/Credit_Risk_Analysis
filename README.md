# Credit_Risk_Analysis

## Purpose 
For the assignment we were tasked with analyzing a dataset that dealt with credit risk in potential clients and the mutiple factors that can contribute to a high or low credit risk. In order to do this, we leveraged the power of machine learning to sample the dataset mutiple times. Each time we used a different sampling technique(oversampling, undersampling, smote, and smoteen) in the hopes we could find the most accurate type of model.

## Results 
![](https://github.com/Stkaran/Credit_Risk_Analysis/blob/main/Resources/OverSample.png)
The first model was the oversample model.
  * The balanced accuracy score was 63%.
  * The precision for high risk was 1% and low risk was 100%.
  * The recalls were 68% for low risk and 57% for high risk.

![](https://github.com/Stkaran/Credit_Risk_Analysis/blob/main/Resources/Smote.png)
The second model used the SMOTE method and as seen below there is very little differnce in results between the first model.
  * The balanced accuracy score was also 63%.
  * The precision for high risk was 1% and low risk was 100%.
  * The recalls were 63% for low risk and 62% for high risk.

![](https://github.com/Stkaran/Credit_Risk_Analysis/blob/main/Resources/Cluster.png)
The model departed from the first to models and used undersampling with the ClusterCentroids method.
  * The balanced accuracy score was also 51%.
  * The precision for high risk was 1% and low risk was 100%.
  * The recalls were 44% for low risk and 59% for high risk.

![]()



