# Clustering-Techniques-for-the-any-customer-dataset-using-machine-Learning
In this code, we first load the customer dataset and select the features for clustering ('Age', 'Income', and 'Spending Score'). Then, we standardize the features to ensure they have the same scale. We use the Elbow Method to find the optimal number of clusters (k) based on the inertia (sum of squared distances within each cluster). We plot the Elbow Method graph to visually identify the best k value.

![image](https://github.com/NituY/Clustering-Techniques-for-the-any-customer-dataset-using-machine-Learning/assets/108191093/00659507-5fb0-45d8-9666-88c1e8cdbc0d)

Next, we apply K-Means clustering with the chosen k value and assign cluster labels to each customer. Finally, we visualize the clusters in a 2D scatter plot using 'Income' and 'Spending Score' as the x and y-axis, respectively.

![image](https://github.com/NituY/Clustering-Techniques-for-the-any-customer-dataset-using-machine-Learning/assets/108191093/ce0ef801-d473-4558-808c-d46ab6a1b2c4)
