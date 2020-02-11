# breastcancer
An analysis of Wisconsin Breast Cancer dataset

This project analyses the Wisconsin Breast Cancer dataset, where breast tissue cytological features were digitally scanned and analysed. Ten features from each one of the cells in the sample. Then, the mean, standard error (SE) and largest 'worst' (mean of the three largest values) of these features were computed for each image, resulting in 30 features.

In the first analysis, I reduced the features of my dataset down to 20 and then used 4 supervised learning machine techniques (kNN, DecisionTree, Gaussian Naive Bayes, Neural Network).I found that Decision Tree was my most effective model, overall, after a bit of pruning.

In the second round of analysis, I used an unsupervised technique called Principal Component Analysis, PCA, in order to reduce my features down to 2 principal components. From there, I used this reduced dataset on 4 supervised techniques: kNN, SVM, Decision Tree, and Gaussian Naive Bayes. I then used an unsupervised technique called k-means clustering to test clustering against 2 features. 
