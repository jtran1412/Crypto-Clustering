# Crypto-Clustering

## Overview

In this project, I will clusters cryptocurrencies by their performance (price change %) for various time periods.
I will use the elbow method to find the ideal value of k. 
I will use K-Means algorithm to cluster the cryptocurrencies. 
I will use PCA to cluster the cryptocurrencies. 
I will visualise and compaire both models with hvplot.

## Results
The ideal value of k was 4.
About 90% of the total variance is condensed into the 3 PCA variables.
The result of using fewer features (PCA) instead of K-means was that there is less overlap of objects within each cluster when using fewer features (PCA1 + PCA2). Thus, using PCA data seems to result in groups that are obviously different from each other (you don't see an object of one cluster inside another cluster) 

## Summary
Using K-Means algorithm, the best performing cryptocurrencies, shown as blue dots, include chainlink, bitcoin, cosmos, monero, cardano, binancecoin, zcash, etherium, tzos, maker, litecoin and wrapped-bitcoin.
Using PCA, the best performing cryptocurrency, shown as a yellow dot, is celcius.  
*Past performance is no guarantee of future results*
