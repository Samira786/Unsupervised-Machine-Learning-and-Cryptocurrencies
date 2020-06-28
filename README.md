# Unsupervised-Machine-Learning-and-Cryptocurrencies

### Background

Report what cryptocurrencies are in the trading market and how cryptocurrencies can be grouped toward creating a classification for developing a new investment product.

Since there is no known output, unsupervised learning will be used. The clustering algorithm will be used to group the cryptocurrencies and data visualizations to share the findings.

### Objectives

•	Prepare the data for dimensions reduction with PCA and clustering using K-means.
•	Reduce data dimensions using PCA algorithms from sklearn.
•	Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn.
•	Create some plots and data tables to present your results.

### Examples of Data Preprocessing

•	Removed cryptocurrencies with null values
•	Removed “IsTrading” column
•	Removed cryptocurrencies that don’t have an algorithm defined
•	Removed “CoinName” column

### Principal Component Analysis (PCA)

•	Principal component analysis is an adaptive data analysis technique that helps to reduce the dimensions in the data sets while minimizing the loss of information.
•	PCA was used to obtain 3 columns as principal components in the data frame.

### Clustering using K-means

•	K-means is a simple clustering method in unsupervised machine learning. 
•	The K-value is 4 based on the elbow curve. 

### Data Visualization

•	The 3D scatter plot demonstrates the results of using PCA

•	HVPlot Table with current tradable cryptocurrencies including the following columns: CoinName, Algorithm, ProofType, TotalCoinSupply, TotalCoinsMined, and Class.

•	Scatterplot of clustered date – x=TotalCoinsMined and y=TotalCoinSupply
