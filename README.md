# Customer-segmentation-using-k-means

## Overview

Customer Segmentation is the process of division of customer base into several
groups of individuals that share a similarity in different ways that are relevant to
marketing such as gender, age, interests, and miscellaneous spending habits. In the first
step of this data science project, we will perform data exploration. We will import the
essential packages required for this role and then read our data. Finally, we will go
through the input data to gain necessary insights about it.

#### K-Means Clustering:

K-Means algorithm is an iterative algorithm that tries to partition the dataset into K
pre-defined distinct non-overlapping subgroups (clusters) where each data point belongs
to only one group. It tries to make the intra-cluster data points as similar as possible
while also keeping the clusters as different (far) as possible. It assigns data points to a
cluster such that the sum of the squared distance between the data points and the
cluster’s centroid is at the minimum. The less variation we have within clusters, the
more homogeneous the data points are within the same cluster.
We then proceeded to perform K-means Clustering which will create different
clusters to group similar spending activity based on their age and annual income. KMeans Clustering selects random values from the data and forms clusters assigned. The
closest values from the centre of each cluster were taken to update the cluster and
reshape the plot (just like k-NN). The closest values are based on Euclidean Distance.

#### Context:
This data set is created only for the learning purpose of the customer segmentation concepts , also known as market basket analysis . I will demonstrate this by using unsupervised ML technique (KMeans Clustering Algorithm) in the simplest form.

#### Content:
You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score.
Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data.

#### Problem Statement:
You own the mall and want to understand the customers like who can be easily converge [Target Customers] so that the sense can be given to marketing team and plan the strategy accordingly.

By the end of this case study , you would be able to answer below questions.
1- How to achieve customer segmentation using machine learning algorithm (KMeans Clustering) in Python in simplest way.
2- Who are your target customers with whom you can start marketing strategy [easy to converse]
3- How the marketing strategy works in real world
