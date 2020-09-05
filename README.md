# Cryptocurrencies

## A. Background

Use unsupersied learning techniques to model crypto currency market,
for advising investment /accounting firms.

## B. Method

1. Clean the data , including dropping unnecessary columns and rows
(like null, not active, etc)

2. For Algorithm, needed to drop 'Multiple' as it was vague and there 
is no such algorithm

3. Assigned new dataframes to fields with the intent of merging at a later stage.

4. Used elbow method to determing possible optimal cluster number.

5. Converted text based column to numeric and made all necessay columns
numeric

6. Used KMeans(n=5) to custer the data and plotted with plotly (3d), hove scatter (2d) , 
and created hover.table for visualization

## C. Results

![images]crypto_elbow_plot.png

![images]Crypto_pca.PNG

![images]k_5_cluster.PNG

![images]plotlyforcrypto.png

![images]hvplottable.PNG

![images]hvplot.png

## D. Summary

There are many crypto coins and modelling with unsupervised learning , 
specifically with KMEANS/elbow gives us some indication of cluster size
to make /fit a KMEANS model.  Our analysis predicted possible cluster size of 5, 
as after 5 the -ve slope does not change as much. We were able to see visually 
that some outliers are clustered with one member, thus providing evidence of 
unique clusters.These clusters may be the desired outcome as it could be popular
etc.In our model, we had 4 more custers and all were tied to supply/mined  data
and that is seen with hover scatter plots.
