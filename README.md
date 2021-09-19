# -Cryptocurrencies Project


## Overview of Project
  
  
 **On this project, the purpose was to analyze a dataset from many alternative cryptocurrencies chosen through an algorithmic process to spot trends that make private business corporations or individuals that want to invest in them. The issue with cryptos is that the most popular ones, like bitcoin or ethereum, are becoming unaffordable for the common public. This exciting analysis on the polular trend among the generation will be studied by machine learning to see if we can spot any trends that result in opportunities for these altcoins.**



##Resources


•	Technologies used:
-	Python
-	Jupyter notebook
-	Sklearn, pandas, and hvplot libraries
-	Unsupervised Machine Learning






## Results and conclusion



   **The first step in our process was to extract, clean, and transform the data to work with unsupervised machine learning. We used pandas.get_dummies method, and scaling the data using the StandardScaler(). Also, we proceeded with the Principal Component Analysis (PCA) to reduce the 98 mounted columns to only three principal components.**
 



<img width="286" alt="Cryy" src="https://user-images.githubusercontent.com/81654454/133944610-e46ced86-f083-47f8-a6ea-22d92466f65a.PNG">





**As for our following process, I created an elbow curve to see how many clusters (k) I could divide the cryptos. We used these coding techniques for our operation.**



<img width="631" alt="Crypto 2" src="https://user-images.githubusercontent.com/81654454/133944614-844c6251-811b-4455-915e-a5dfc1f9527a.PNG">





<img width="564" alt="Crypto 3" src="https://user-images.githubusercontent.com/81654454/133944644-abf930b7-2142-42fa-b05a-0457e026ead9.PNG">


As a result, we can get four clusters' for our optimal effect from the graph displayed in our analysis. Therefore, I  proceeded with the KMeans analysis to fit the PCA data frame and predict the clustering. 

Foto 4


**3D Visualization optic view**.

Foto 5

** As shown in our interactive representation from the 3D scatter plot, each clustered crypto related to the three principal components created on the PCA.**
