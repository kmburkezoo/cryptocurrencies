# cryptocurrencies

## Purpose
The purpose of this project is to use unsupervised machine learning to analyze, group, and visualize various cryptocurrencies.

## Process

1. Preprocessing
    * Currencies that are not currently traded, have not been mined, or have null values are removed
    * Columns that will not be used for clustering are removed
    * Columns containing string values are encoded
2. Dimensionality is reduced using Principle Component Analysis
3. Clustering
    * An elbow curve is used to find the ideal K value
    * The data is clustered using the KMeans algorithm
    * Source data, principle components, and predicted classes are combined into a dataframe for easy viewing
4. Visualization
    * The classes are plotted in 3D, with the principle components as the axes
    * Coin information and class predictions are combined into a sortable table
    * Coin mined and coin supply are scaled and plotted in 2D

## Resources
* Languages: Python, in Jupyter Notebook
* Libraries
    ** Pandas
    ** HVPlot
    ** Plotly
    ** SciKit Learn