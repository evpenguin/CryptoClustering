# Challenge 19 - Crypto Clustering
Analyses CruptoCurrency market prices using K-Means models with and without Principal Component Analysis to determine if the prices are affected by 24-hour or 7-day price changes. 

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Installing](#installing)
- [Usage](#usage)
- [Contributing](#contributing)

## About
This analysis first determines the optimal number of clusters for K-Means modelling when using all 7 features, then predicts a 4-cluster model. We then apply Principal Component Analysis to reduce the data two 3 features, which represent 90% of the variablility of the original data. We then determine the new optimal number of clusters for the PCA data, and finally compare the elbow and cluster visualisations to compare the methods. 

## Getting Started
This repository contains the intitial data in Resources, the Jupyter Notebook with the analysis, and Plot Images, containing screenshots of all the plots created within the Jupyter Notebook. The plot screenshots are included due to a known bug in hvplot which occasionally prevents the plots from rendering. 

## Installing
Clone this repository and run in Jupyter Notebook.

## Usage
Does cluster analysis on Crypto Currency market data. 

## Contributing
Evangeline Allan
