# -Cryptocurrencies Project


## Overview of Project
  
  
 **On this project, the purpose was to analyze a dataset from many alternative cryptocurrencies chosen through an algorithmic process to spot trends that make private business corporations or individuals that want to invest in them. The issue with cryptos is that the most popular ones, like bitcoin or ethereum, are becoming unaffordable for the common public. This exciting analysis on the polular trend among the generation will be studied by machine learning to see if we can spot any trends that result in opportunities for these altcoins.**



## Resources


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




**As a result, we can get four clusters' for our optimal effect from the graph displayed in our analysis. Therefore, I  proceeded with the KMeans analysis to fit the PCA data frame and predict the clustering.** 



<img width="615" alt="Crypto 7" src="https://user-images.githubusercontent.com/81654454/133945113-bda4483c-d859-40d8-9f34-4840fbad4432.PNG">



#### **3D Visualization optic view**.




**As shown in our interactive representation from the 3D scatter plot, each clustered crypto related to the three principal components created on the PCA.**



<img width="575" alt="Crypto 5" src="https://user-images.githubusercontent.com/81654454/133944693-8f2f2961-bedf-42a3-ae99-69197d79ed86.PNG">





<img width="566" alt="Crypto 6" src="https://user-images.githubusercontent.com/81654454/133944702-09c6281a-ee0a-45a7-9d93-2eb0974f95ca.PNG">




## Conclusion



**The unsupervised machine learning process aims to discover patterns or groups of data when there is no known output. This analysis successfully grouped cryptocurrencies into four groups.**




**If we were to create a crypto investment portfolio, we would need to analyze the clusters further. We must have a good starting point where we can see that the most profitable cryptos in the two groups have less supply and mined coins than others. These cryptos are Bitcoin and Ethereum. Finally, we advised keeping up with technology innovations where new altcoins are discovered and are proposed as an exciting business opportunity.**

