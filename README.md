# CryptoClustering
## Module 19 Challenge

### Objective
To understand how primary component analysis affects K Means clustering of a cryptocurrency dataset.

### Analysis
The [cryptocurrency dataset](Resources/crypto_market_data.csv) is available in this repository's Resources folder.  
Analysis is provided in the jupyter notebook file [Crypto_Clustering.ipynb](Crypto_Clustering.ipynb).
The analysis file contains the following:
1. Utilizing StandardScaler from sklearn
2. Utilizing an elbow curve to determine optimal K-means cluster number
3. Clustering of cryptocurrencies with K-means
4. Optimizing clusters with Principal Component Analysis (PCA)
5. Utilizing an elbow curve to determine optimal K-means cluster number with PCA data
6. Clustering of cryptocurrency PCA data with K-means
7. Comparison of K-means clustering with and without PCA

### Conclusion
Although optimal K-means cluster number did not change after using Principal Component Analysis, PCA allowed for better visualization of cluster differences within the cryptocurrency dataset.
