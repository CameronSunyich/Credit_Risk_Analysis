# Credit_Risk_Analysis

# Overview:

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Files:

https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_17/Module-17-Challenge-Resources.zip 

Use LoanStats_2019Q1.csv for data and the credit_risk_resampling_starter_code.ipynb and credit_risk_ensemble_starter_code.ipynb as your starter code.

# Results:

-Naive Random Oversampling

    Poor Accuracy and Fair Recall, very low Precision
    
-SMOTE Oversampling

    Poor Accuracy and Poor Recall, very low Precision
    
-Cluster Centroids Undersampling

    Poor Accuracy and Poor Recall, very low Precision
    
-SMOTEENN Undersampling

    Poor Accuracy and Poor Recall, very low Precision
    
-Balanced Random Forest Classifier

    Fair Accuracy and Fair Recall, very low Precision
    
-AdaBoost Classifier

    Good Accuracy and Good Recall, improved but still very low Precision
    
 Naive Random Oversampling Image
 
 <img width="674" alt="Naive_Random_Oversampling" src="https://user-images.githubusercontent.com/90425412/151737649-38b27278-f43c-4fa8-a9c0-8d956a3f148b.png">
 
 
SMOTE Oversampling Image

  <img width="654" alt="SMOTE_Oversampling" src="https://user-images.githubusercontent.com/90425412/151737789-35452e0c-1d85-4ebe-b0b7-a0d1dc43d2a8.png">
  
  
 Cluster Centroids Undersampling Image
 
 <img width="619" alt="Cluster_Centroids_Undersampling" src="https://user-images.githubusercontent.com/90425412/151737925-8f405ca3-09a4-49cc-9e4d-bca0fe968656.png">
 
 
 SMOTEENN Undersampling Image
 
 <img width="577" alt="SMOTEENN_Undersampling" src="https://user-images.githubusercontent.com/90425412/151738057-8fe93083-c9ed-44f8-aa48-8b76584a0d49.png">


Balanced Random Forest Classifier Image

  <img width="621" alt="Balanced_Random_Forest_Classifier" src="https://user-images.githubusercontent.com/90425412/151738465-1b1f76e6-eb97-4e14-8149-5a7498c8ac98.png">


AdaBoost Classifier

  <img width="595" alt="AdaBoost_Imbalanced_Classification" src="https://user-images.githubusercontent.com/90425412/151738492-2a4a8ef8-c40c-49a0-9089-d4b238511bb4.png">


