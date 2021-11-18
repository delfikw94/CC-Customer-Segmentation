# Customer Segmentation in Credit Card Services
Credit card customer segmentation using clustering machine learning model

**Tools Used** : Python, Pandas, Seaborn, Scikit-Learn

**Category** : Machine learning, Unsupervised learning, Clustering

**Year** : September 2021

**Features** : Credit card balance, Purchase ratio, Installment purchase frequency, payments, cash advance frequency, etc.

**Model Algorithms** : K-Means Algorithm, Gaussian Mixture, Elbow Method, PCA

**Result** : Based on the elbow method and silhouette score, the amount of effective cluster is 3. The data was trained with 2 kinds of model, and the model with K-Means Algorithm gives the best result (based on the variance in data visualization). Then the characteristic of these 3 cluster were analyzed further based on their shopping behaviour.

- Cluster A : semi-active user. seem very interested in cash advance feature. always keep their balance is available/filled up
- Cluster B : passive-user. rarely make transaction with their credit card. even when they have, the transaction amount is the lowest among other cluster
- Cluster C : active-user. most frequent in making transaction, especially for the purchase installment. mostly had transaction with high amount.
