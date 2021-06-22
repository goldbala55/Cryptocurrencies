# Cryptocurrencies
Analyze the cryptocurrencies on the trading market and how they can be grouped to create a classification system for new investment portfolios.

## Overview
 The goal is to categorize the currencies into groups based on the reference data provided.  The data needed to be preprocessed with unneeded features removed, text features converted to booleans (via get_dummies), and reducing dimensionality using PCA.  An 'elbow curve' was created and used to pick the optimal clustering for a K-means analysis. The resulting clusters were merged into the tradable currencies for visualization and reporting.

## Resources
 Data: Cryptocurrency data from  CryptoCompare

 Software: Python 3.7.10, Jupyter Notebook 6.3, pandas 1.2.4, numpy 1.19.5,scikit-learn 0.24.1, Git Bash 4.4.23, 
 
 Graphics: plotly 4.14.3, hvplot 0.7.2