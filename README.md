# Fintech_Module10_Challenge_Unsupervised-Learning

## Crypto Clustering
![](https://github.com/Karthi-k-a/Fintech_Module10_Challenge_Unsupervised-Learning/blob/main/Images/10-5-challenge-image.png)

### Overview
Crypto Clustering aims at clustering cryptocurrencies by their performance in different time periods and then plotting the results to visually show the performance.<br>
Files: [crypto_investments.ipynb](https://github.com/Karthi-k-a/Fintech_Module10_Challenge_Unsupervised-Learning/blob/main/crypto_investments.ipynb), [crypto_market_data.csv](https://github.com/Karthi-k-a/Fintech_Module10_Challenge_Unsupervised-Learning/blob/main/Resources/crypto_market_data.csv)

### Steps
- Import the Data (provided in the starter code)
- Prepare the Data (provided in the starter code)
- Find the Best Value for k Using the Original Data
- Cluster Cryptocurrencies with K-means Using the Original Data
- Optimize Clusters with Principal Component Analysis
- Find the Best Value for k Using the PCA Data
- Cluster the Cryptocurrencies with K-means Using the PCA Data
- Visualize and Compare the Results

### Results
**Elbow Curve using original data:**<br>
From the below Elbow Curve plotted using the original data, the best value for k is 4.
![](https://github.com/Karthi-k-a/Fintech_Module10_Challenge_Unsupervised-Learning/blob/main/Images/elbow_original.png)

**Elbow Curve using PCA data:**<br>
From the below Elbow Curve plotted using the PCA data, the best value for k is 4. It is same as the k value found using original data; however, the inertia at that point is different with 79.022 in original data and 49.665 in PCA data.
![](https://github.com/Karthi-k-a/Fintech_Module10_Challenge_Unsupervised-Learning/blob/main/Images/elbow_pca.png)

**Clustering of cryptocurrencies using original data:**<br>
![](https://github.com/Karthi-k-a/Fintech_Module10_Challenge_Unsupervised-Learning/blob/main/Images/cluster_original.png)

**Clustering of cryptocurrencies using PCA data:**<br>
![](https://github.com/Karthi-k-a/Fintech_Module10_Challenge_Unsupervised-Learning/blob/main/Images/cluster_pca.png)

### Conclusion
The inertia for the clusters with the PCA features is way lower than that of the original features. The values within each cluster in PCA data are much closer together and easier to distinguish compared to the ones in the original data. The PCA plot also better separated the two outliers celsius-degree-token and ethlend.
