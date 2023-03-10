# Intent Detection of User Retail Shopping using Stacked Autoencoders

Semi-supervised learning (SSL) is a machine learning approach that is implemented in cases where the class labels are not known. The goal of this approach is to leverage the unlabelled data during training along with small set of labelled data. Previous research has proven that semi-supervised techniques provide results as good as a completely supervised learning approach.

In this project, three different semi-supervised approaches namely Self Training, Semi-supervised ensemble and Unsupervised Pretraining are implemented to identify the best performing model to perform intent detection of online shopping to determine whether a given user will complete their shopping or not.

Further, a comparitive analysis was also conducted to study the performance of different SSL models on different degrees of imbalance data and the following results were observed. 

-  SSL algorithms is a promising option when the dataset consists of large number of unlabelled data
-  The performance of SSL algorithms decreases in most cases as the level of unlabelled data increases
-  The performance of SSL algorithms increases in the case of oversampled data
-  The performance of SSL algorithms is as good as a fully supervised algorithm even when the level of unlabelled data is greater than 10%
-  Semi Boost suffers in case of large datasets because it uses KNN for similarity calculated between nearest data points
