# Cryptocurrencies

## Overview

Analysis of the available Cryptocurrency information to help prepare clients getting into cryptocurrency market by using unsupervised learning to process data, cluster data, reduce data dimensions, and reduce the principal components using PCA.

Tasks are divided as shown below:
 - 1: Preprocessing the Data for PCA
 - 2: Reducing Data Dimensions Using PCA
 - 3: Clustering Cryptocurrencies Using K-means
 - 4: Visualizing Cryptocurrencies Results


## Resources
  - Data Source: crypto_data.csv
  - Software: anaconda3, python 3.7.7, jupyter notebook
  - Librarys: pandas, hvplot, path, plotly.express, sklearn.preprocessing (StandardScaler, MinMaxScaler), sklearn.decomposition (PCA), sklearn.cluster (KMeans)


## Results
### Preprocessing the Data for PCA
 - Starting Data
 
   ![""](./Images/Starting_data.png "")

 - List with Algorithms
 
   ![""](./Images/List_of_Coins_algorithms.png "")
   
 - List with currently Traded
 
   ![""](./Images/List_of_Coins_Traded.png "")
   
 - List with no null rows
 
   ![""](./Images/List_of_Coins_nonulls.png "")
   
 - List with coins that are mined
 
   ![""](./Images/List_of_Coins_Mined.png "")
   
 - Dropping CoinName column
 
   ![""](./Images/no_coinname_column.png "")
   
 - Converting all string data to numeric suing dummies function
 
   ![""](./Images/Conversion_string_to_numeric.png "")
   

### Reducing Data Dimensions Using PCA
 - Reduction PCS table
 
   ![""](./Images/Reduction_PCA_table.png "")
   
 - Elbow Curve
 
   ![""](./Images/elbow_curve.png "")
   


### Clustering Cryptocurrencies Using K-means
 - Clustering PCA table
 
   ![""](./Images/Clustering_PCA_table.png "")
   
 - Coins Table
 
   ![""](./Images/coins_table.png "")
   
 - 3D Scatter plot
 
   ![""](./Images/3d_scatter_plot.png "")
   


### Visualizing Cryptocurrencies Results
 - Coins mined vs supply table
 
   ![""](./Images/Coins_Mined_vs_Supply_table.png "")
   
 - Coins mined vs supply scaled chart
 
   ![""](./Images/Coins_Mined_vs_Supply.png "")
   


## Summary

Based on the analysis we can show that there are 532 coins that are being currently actively traded in cryptocurrency market. Further analysis can be done on these coins to see what are the better contenders for mining and suggesting them for our clients.
