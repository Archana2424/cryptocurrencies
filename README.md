#CRYPTOCURRENCIES# -

*ANALYSIS OVERVIEW-

The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies 
and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.


Using the following methods for the analysis:

-preprocessing the database,
-reducing the data dimension using Principal Component Analysis,
-clustering cryptocurrencies using K-Means,
-visualizing classification results with 2D and 3D scatter plots

*RESOURCES-

Data Source: crypto_data.csv, CryptoCompare
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3


*RESULTS-

Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.


1.Clustering Cryptocurrencies using K-Means - Elbow Curve-Results(elbow curve fig	1)


 We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
 We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

  The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

2.Visualizing Cryptocurrencies Results-(3D SCATTER PLOT)

  3D-Scatter plot with clusters.

  This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.


3. Tradable Cryptocurrencies Table-Results(Tradable table)

   Most of the cryptocurrencies are part of class #0 and #1.

4.2D-Scatter plot with TotalCoinMined vs TotalCoinSupply-results-((2D SCATTER PLOT))
  
  Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. 
Then using the PCA algorithm is the right method for better visualizations.


*SUMMARY-

The following analysis was done on various crypto currency such as BITCOIN, ETHEREUM, LITECOIN etc.
 and following trends and pattern were analysed (as in the jupyter notebook).
the Analysis identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.