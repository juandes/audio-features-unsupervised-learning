# Clustering and Visualizing my Spotify music

## Overview

In this project I clustered my Spotify music using its audio features with the goal of finding similar music in each of the clusters.

This work is mostly divided into four parts, which also represents the main topics I want to study.
- What is the most appropriate number of clusters I should use?
- The clustering of the data and looking at the values of several clustering statistics such as the silhouette coefficient, and the dissimilarities between clusters.
- How good is the clustering? How similar are the songs within each cluster? Does the clustering make any sense?
- How does the clustered data look like?

This work was done using both R, and Python. The clustering part was done using R and the packages caret, and cluster. Python was used to acquire the data using the library Spotipy, and to visualize the data using Hypertools. All the code used for the analysis is available in this repo. The file `notebook.Rmd` is the R code (as a notebook), and `data_visualization.ipynb` is the code used for the visualizations.

## The data
All the data needed (and generated) for the project is also available. The file `audiofeatures.csv` contain the feature vectors used for the clustering, `tracksinfo.csv` has some information regarding the music such as album, artists, and Spotify's uri. The files `main_cluster.csv` and `cluster_3.csv` are the clustering results.

## The report
A complete report of this project is available at: ...
