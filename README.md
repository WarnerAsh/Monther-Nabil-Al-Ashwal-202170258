Name : Monther Nabil Al-Ashwal
Ac.No : 202170258

Project : Classification of World Countries Using K-Means and Hierarchical Clustering

IMPORTANT NOTES :
1/ the project is built with orange meaning it has a ows file
2/ the dfs search homework is also uploaded to the same repository in a py file
3/ the dataset file is also uploaded here (Note that the orange file requires it so make sure its uploaded or 
upload it manually 


Overview :
The goal of this project is to categorize the world's countries based on a set of socio-economic and health indicators. The key metrics include:

Health Statistics
Child Mortality
Life Expectancy
Inflation
Imports and Exports
GDP
Total Fertility Rate
The purpose is to divide countries into three categories to assess whether a country requires help or assistance based on these factors.

Algorithms Used:
The project employs two unsupervised clustering algorithms:

1/K-Means Clustering: A popular partitioning method that divides the dataset into k clusters based on similarity. 
In this case, it groups countries into three clusters, with each cluster representing a different level of need (e.g., high, moderate, low).

2/Hierarchical Clustering: This algorithm builds a hierarchy of clusters either through an agglomerative approach (starting with individual countries and merging them) or a divisive approach (starting with one large cluster and splitting). 
This method is also used to divide countries into three categories based on the same socio-economic indicators.

Process:
Data Preprocessing: Data representing each country's indicators (health, economy, etc.) is cleaned and normalized to ensure consistency across the variables.

Clustering: Both K-Means and Hierarchical Clustering are applied to the dataset. The number of clusters (k) is set to three, representing:

Category 1: Countries in urgent need of help.
Category 2: Countries that need moderate assistance.
Category 3: Countries that are relatively stable or do not require external assistance.
Comparison of Algorithms: The results of the K-Means and Hierarchical Clustering algorithms are compared. 
Silhouette plots are used to evaluate the cohesion and separation of clusters, 
which helps in determining how well the countries are grouped. Scatter plots are also generated to visualize the clusters and their distribution based on the chosen indicators.

Final Decision: Based on the clustering results and visual analysis, each country is classified into one of the three categories. 
Countries that fall into the first category are identified as those requiring urgent help.

