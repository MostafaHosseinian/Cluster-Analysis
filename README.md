# Cluster Analysis for Customer’s Segmentation

## Introduction
Unsupervised learning is an increasingly important branch of data science, the goal of which is to train models that can learn the structure of a dataset and provide the user with helpful pieces of information about new samples. In many different business sectors (such as marketing, business intelligence, strategy, and so forth), unsupervised learning has always had a primary role in helping the manager to make the best decisions, based both on qualitative and, above all, quantitative approaches.

Malls or shopping complexes are often indulged in the race to increase their customers and make huge profits. Hence, it is essential to know more about their customers and cluster those who have the same characteristics or features in the same cluster and separate customers who have no common in a different cluster. It would help businesses to focus more on the specific sub-group of customers for further planning.

The main methods we use in this study are **Dissimilarity-based methods** and **model-based methods**. The dissimilarity-based method includes **KMeans**, **Hierarchical Clustering**, and **KPrototypes**. The model-based method also involves **Gaussian Mixture Model (GMM) with Expectation-Maximization (EM) algorithm**.
Furthermore, one primary constraint in most dissimilarity-based methods is the fact that they are based on distance/similarity metrics. So, dealing with mixed-type (continuous and categorical) data is a challenge. Most distance/similarity metrics like Euclidean, Manhattan, Minkowski, and etc., handle continuous data, whereas some metrics like the simple matching introduced to deal with categorical data. In many applications, each instance in a data set is described by more than one type of attribute. In this case, the dissimilarity measures discussed before cannot be applied directly. This study examines Gower's metric to calculate the dissimilarity metric when we have mixed-type data. Moreover, we consider the KPrototypes algorithm that works well on mixed-type data. KPrototypes is a dissimilarity-based method that uses the KMeans and K-Mode clustering algorithm to handle mixed-type data.

Besides, one of the most common disadvantages of cluster analysis is related to choosing the optimal number of clusters (*k*). Often, we don't know the number of clusters. An excessively small value for *k* will determine large groupings and heterogeneous elements, while a large number leads to identify the clusters difficult. In these cases, we will want to select *k* based on using some criteria. Therefore, we're going to discuss some methods that can be employed to determine the appropriate number of splits and to evaluate the corresponding performance. These methods includes elbow plot (or inertia plot), Silhouette, Calinski-Harabasz, Davies-Bouldin index.

## Procedure
This study is conducted in 4 main parts.
- First, we use descriptive analysis to get an idea of our data and find duplications or missing values in advance.
- Second, we use exploratory data analysis (EDA) to summarize the main characteristics of our data, using statistical graphics and other data visualization methods.
- Third, we use dissimilarity-based methods to cluster our data. Three algorithms (KMeans, Hierarchical CLustering, and KPrototypes) are employed for this purpose.
- Fourth, we use a model-based method using GMM with EM algorithm to analyze different clusters.

The summary findings are discussed after each part. For more detail, please contact the author (me).
