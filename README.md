# Unsupervised-Machine-Learning-and-Cryptocurrencies

### Background

Report what cryptocurrencies are in the trading market and how cryptocurrencies can be grouped toward creating a classification for developing a new investment product.

Since there is no known output, unsupervised learning will be used. The clustering algorithm will be used to group the cryptocurrencies and data visualizations to share the findings.

### Objectives

•	Prepare the data for dimensions reduction with PCA and clustering using K-means. <br/>
•	Reduce data dimensions using PCA algorithms from sklearn. <br/>
•	Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn. <br/>
•	Create some plots and data tables to present your results. <br/>

### Examples of Data Preprocessing

•	Removed cryptocurrencies with null values <br/>
•	Removed “IsTrading” column <br/>
•	Removed cryptocurrencies that don’t have an algorithm defined <br/>
•	Removed “CoinName” column <br/>

### Principal Component Analysis (PCA)

•	Principal component analysis is an adaptive data analysis technique that helps to reduce the dimensions in the data sets while minimizing the loss of information. <br/>
•	PCA was used to obtain 3 columns as principal components in the data frame. <br/>

![1](https://github.com/Samira786/Unsupervised-Machine-Learning-and-Cryptocurrencies/blob/master/images/PCA-18.png)

### Clustering using K-means

•	K-means is a simple clustering method in unsupervised machine learning. <br/>
•	The K-value is 4 based on the elbow curve. <br/>

![2](https://github.com/Samira786/Unsupervised-Machine-Learning-and-Cryptocurrencies/blob/master/images/elbowcurve-18.png)

### Data Visualization

•	The 3D scatter plot demonstrates the results of using PCA <br/>

![3](https://github.com/Samira786/Unsupervised-Machine-Learning-and-Cryptocurrencies/blob/master/images/scatterplot-18.png)

•	HVPlot Table with current tradable cryptocurrencies including the following columns: CoinName, Algorithm, ProofType, TotalCoinSupply, TotalCoinsMined, and Class. <br/>

![4](https://github.com/Samira786/Unsupervised-Machine-Learning-and-Cryptocurrencies/blob/master/images/HVPlot-18.png)

•	Scatterplot of clustered date – x=TotalCoinsMined and y=TotalCoinSupply <br/>

![5](https://github.com/Samira786/Unsupervised-Machine-Learning-and-Cryptocurrencies/blob/master/images/scatterplot2D-18.png)
