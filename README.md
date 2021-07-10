# Cryptocurrencies

![Cryptocurrency](https://github.com/RyanWhited/Cryptocurrencies/blob/main/images/cryptocurrency-mining-equipment-isometric-ethereum-digital-currency-extract_39422-401.jpg)

## Overview of Analysis

Accountability Accounting, an investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. They asked me to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. I have chosen unsupervised learning to group these and created visualizations to present.

## Results

### Deliverable 1: Preprocessing the Data for PCA

The first step was the transform and standardized the data using the StandardScaler() method to prep it for Principal Component Analysis. 

![Deliverable 1](https://github.com/RyanWhited/Cryptocurrencies/blob/main/images/Deliverable1.jpg)

### Deliverable 2: Reducing Data Dimensions Using PCA

Using the Principal Component Analysis (PCA) algorithm I reduced the dimensions of the X DataFrame to three principal components and place those dimensions in a new DataFrame.

![Deliverable 2](https://github.com/RyanWhited/Cryptocurrencies/blob/main/images/Deliverable2.jpg)


### Deliverable 3: Clustering Cryptocurrencies Using K-means

Using the K-means algorithm I created an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then I ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data which I determined was 4. 

![Deliverable 3](https://github.com/RyanWhited/Cryptocurrencies/blob/main/images/Deliverable3.jpg)

### Deliverable 4: Visualizing Cryptocurrencies Results

Using scatter plots with Plotly Express and hvplot I visualized the distinct groups that correspond to the three principal components I created in Deliverable 2. Then I created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

3D SCATTER PLOT

![Deliverable 4(1)](https://github.com/RyanWhited/Cryptocurrencies/blob/main/images/Deliverable4(1).jpg)

SCATTER PLOT

![Deliverable 4(3)](https://github.com/RyanWhited/Cryptocurrencies/blob/main/images/Deliverable4(3).jpg)

TABLE

![Deliverable 4(2)](https://github.com/RyanWhited/Cryptocurrencies/blob/main/images/Deliverable4(2).jpg)



