# Credit_Risk_Analysis
## Overview of the analysis: 
The purpose of the our analysis is to to predict credit risk for LendingClub, a peer-to-peer lending services company techniques to train and evaluate models with unbalanced classes  using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.

## Results: 
Below is the lists of the balanced accuracy scores and the precision and recall scores of all six machine learning models with screenshots.

- RandomOverSampler:

![image](https://user-images.githubusercontent.com/104603037/189161078-cb91c349-6fca-439e-a717-bf488e4a192d.png)

- SMOTE:

![image](https://user-images.githubusercontent.com/104603037/189161177-a7839b9f-a4cb-49f4-8d36-c1a0973852c2.png)

- ClusterCentroids:

![image](https://user-images.githubusercontent.com/104603037/189161268-82a8c3ee-7a84-4ae8-a827-0d38529a6666.png)

- SMOTEENN:

![image](https://user-images.githubusercontent.com/104603037/189161336-c108f4fb-c37f-46ae-afac-be26b3c36b85.png)

- BalancedRandomForestClassifier:

![image](https://user-images.githubusercontent.com/104603037/189161467-b55e93cc-4d1b-4a27-be49-54d4e2c9c68d.png)

- EasyEnsembleClassifier:

![image](https://user-images.githubusercontent.com/104603037/189161548-9dd7cbed-2d2f-46e7-86c1-be2ac1abbde4.png)


## Summary:
Comparing the two machine learning models that reduce bias BalancedRandomForestClassifier and EasyEnsembleClassifier.
Based on the above outputs my recommendation will adopt the EasyEnsembleClassifier and this is because we want our machine learning to detect high credit risk as high  possible so the company does not avail credit to these set of borrowers.

Also in our metrics, I will go for value of specificity (0.94) because when specificity is high then it means our model is good at predicting the true negatives.
