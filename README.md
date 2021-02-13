# Cryptocurrencies

## Project Overview:
Create a report that includes cryptocurrencies that are on the trading market and show how they could be grouped to create a classification system for the new investment of Accountability Accounting.

## Results:

### What cryptocurrencies are on the trading market?

The dataset was preprocessed and two data frames were obtained, one containing only the “Coin Names” and the other containing data for “Algorithm”, “Proof Type”, “Coins Mined”, and “Coin Supply.”

The cryptocurrencies that are on the trading market are as follow:

Coin Name data frame:

![](https://github.com/KatiuscaQ/Cryptocurrencies/blob/main/Resources/CoinName.PNG)

Cryptocurrencies data frame:

![](https://github.com/KatiuscaQ/Cryptocurrencies/blob/main/Resources/crypto_df.PNG)


### How the cryptocurrencies can be grouped?

After preprocessing the dataset, PCA (Principal Component Analysis) was used to extract information from the high-dimensional dataset and projecting it into a lower-dimensional sub-set.  The next image shows the resulting dataframe:

![](https://github.com/KatiuscaQ/Cryptocurrencies/blob/main/Resources/pcs_df.PNG)

With the help of K-means the clustering of cryptocurrencies was able to be done.

First an elbow curve was produce:

![](https://github.com/KatiuscaQ/Cryptocurrencies/blob/main/Resources/elbow_curve.PNG)

The image above shows an “elbow” formation on number 4, reason for selecting the number of clusters equal to 4 for the K-means model.

A 3D scatter plot was produced to show the clustering of the cryptocurrencies:

![](https://github.com/KatiuscaQ/Cryptocurrencies/blob/main/Resources/3d_scatter.png)

A table with the tradable cryptocurrencies is shown below:

![](https://github.com/KatiuscaQ/Cryptocurrencies/blob/main/Resources/crypto_table.PNG)


Also, a two-dimensional scatter plot was created showing the Coins Mined vs the Coin Supply:

![](https://github.com/KatiuscaQ/Cryptocurrencies/blob/main/Resources/2d_scatter.PNG)


## Summary:

### What cryptocurrencies are on the trading market?

•	There are 532 tradable cryptocurrencies.

### How the cryptocurrencies can be grouped?

Since 4 clusters were selected for this study, the cryptocurrencies were grouped into those clusters by the unsupervised machine learning algorithm as follow:

•	There are 238 cryptocurrencies in class 0.

•	There are 289 cryptocurrencies in class 1.

•	There are 1 cryptocurrencies in class 2.

•	There are 4 cryptocurrencies in class 3.

