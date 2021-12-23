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

![](https://github.com/Stkaran/Credit_Risk_Analysis/blob/main/Resources/Smoteen.png)
The fourth model combines both over and undersampling methods with SMOTEEN.
  * The balanced accuracy score was also 62%.
  * The precision for high risk was 1% and low risk was 100%.
  * The recalls were 54% for low risk and 70% for high risk.

![](https://github.com/Stkaran/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForest.png)
The fifth model used BalancedRandomForest classifier which undersamples the majority class in order to balance the dataset.
  * The balanced accuracy score was also 79%.
  * The precision for high risk was 4% and low risk was 100%.
  * The recalls were 91% for low risk and 67% for high risk.

![](https://github.com/Stkaran/Credit_Risk_Analysis/blob/main/Resources/EasyEnsemble.png)
Lastly, the sixth model used EasyEnsemble(a form adaptive boosting) and random undersampling on the dataset.
  * The balanced accuracy score was also 93%.
  * The precision for high risk was 7% and low risk was 100%.
  * The recalls were 94% for low risk and 91% for high risk.

## Results
Overall, the accuracy trend in our models moved in a positive direction. Specifically, both the balanced accuracy scores and recall values improved with each successive model. The EasyEnsemble was the best of the bunch and by the end the model was able to accurately identify over 90% of both low-risk and high-risk cases. However, there was one issue that was never truly solved and it lay with the fact that the high-risk precison score at its highest was only 7%. In this context though, low precision and high sensitivty is acceptable. With this combination there will be a significant amount of false positives flagged as high risk, but as a business, it can be better to be on the safe side and lose a few potential customers rather than expose yourself to a lot of high risk cases. Due to this, I would argue that the EasyEnsemble model meets the requirements and can be used effectively in certain scenarios.  






