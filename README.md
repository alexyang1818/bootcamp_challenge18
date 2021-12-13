# Unsupervised Machine Learning and Cryptocurrencies

## Purpose

A collection of over 1,000 cryptocurrencies have been analyzed using unsupervised machine learning to determine how to group them based on their features. The results can be used to identify opportunities for startups in the same area.

## Results

The features of cryptocurrencies were pre-processed to study only those that are being traded and without null values. Features such as Algorithm and ProofType were extended to cover multiple cases. 

Preprocessing resulted in 532 cryptocurrencies with 98 features. These features were first scaled and then simplified using principal component analysis. Three principal components were used to identify clusters of these 532 cryptocurrencies. 

Using the elbow curve, it was determined that there are 4 clusters in total. K-means analysis was carried out to classify each cryptocurrency. The result of classification was displayed using table and both 3-d and 2-d plots.