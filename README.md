# EDA


1. Loading and understanding the data set
2. Removing irrelevant column
3. Create a label column about loan status
4. Exploratory data analysis
5. Preprocessing of data for another category column
6. Clustering
7. Predicting risk using KNN model
8. Risk prediction using Random Forest
9. Risk prediction using GradientBoost


Results 

1. Various models were experimented to predict if the user would pay the debt on time or not. We used binary classification
2. Models used were the KNN model, RandomForest, and GradientBoost. Couldnt get tensorflow to work but will continue further
3. Random Forest Classifier provided the results in less than half the time (around 6 minutes) compared to KNN model
4. Accuracy of random forest and KNN with 10 neighbours were very similar for test data at around 91%
5. Also tried with increaing number of trees and the accuracy output for test data was not much different 
6. GradientBoost was also comparable to randomforest classifier but the time for training for prediction was one-third of the random forest at just over 2 minutes
. 

Summary:
KNN, random forest and gradient boost were very comnparable in their results. Need to work on tensorflow next. 

References:

1. https://www.kaggle.com/datasets/ranadeep/credit-risk-dataset?resource=download    
2. https://www.kaggle.com/code/ardhikamalhaq/credit-risk-analysis-using-knn-model 

