# Cryptocurrencies

The purpose of the analysis was to use unsupervised learning to evaluate cryptocurrencies. Data for the analysis was retrieved from CryptoCompare. The analysis included:
- Cleaning the data to remove null value and include only cryptocurrencies currently traded and mined.
- Scaling the data and using PCA to reduce to three principal components.
- Using an elbow curve to choose the best K-value (4) and using the K-Means model to predict the class for each cryptocurrency.
- Creating a 3D-Scatter based on results to visualize the relationship between cryptocurrencies.
- Scaling the total coin supply and total coins mined and plotting the results on a 2D-Scatter.
