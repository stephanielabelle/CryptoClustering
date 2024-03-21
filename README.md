# CryptoClustering
## Module 19 Challenge

### Objective
To understand how Primary Component Analysis (PCA) affects K-means clustering of a cryptocurrency dataset.

### Analysis
The [cryptocurrency dataset](Resources/crypto_market_data.csv) is available in this repository's Resources folder.  
Analysis is provided in the jupyter notebook file [Crypto_Clustering.ipynb](Crypto_Clustering.ipynb).
The analysis file contains the following:
1. Utilizing StandardScaler from sklearn to normalize the data
2. Utilizing an elbow curve to determine optimal K-means cluster number
3. Clustering of cryptocurrencies with K-means
4. Conducting PCA on the cryptocurrency dataset
5. Utilizing an elbow curve to determine optimal K-means cluster number with cryptocurrency Primary Component (PC) data
6. Clustering of cryptocurrency PC data with K-means
7. Comparison of K-means clustering with and without PCA

### Conclusion
Although optimal K-means cluster number did not change after using Principal Component Analysis, PCA allowed for better visualization of cluster differences within the cryptocurrency dataset.
