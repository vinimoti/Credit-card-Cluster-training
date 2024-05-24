# Credit-card-Cluster-training
Learning about Clustering data with Alura.\
*Are there types os customers?*
For my first contact with clustering data and unsupervised learning, I have a challenge to divide the customer without having any previous classification.\
The main idea was to make a segmentation of the clients

## Step-by-step
* Load the data and clean it;
* Treat missing values -> in this section I just played a little with the data (may compromise results?);
* Make the cluster by using the method K-means clustering;
* Find a decent number for the quantity of clusters;
* Validate the model -> methods: Silhouette, Davies-Bouldin, Calinski–Harabasz;
* Filter the most distinct feature between clusters using centroids;
* Analyze and have some insights (labelling) about how each cluster of customer behave based on the averages.

## Kaggle Dataset
Data comes from Kaggle. Source: https://www.kaggle.com/datasets/arjunbhasin2013/ccdata/data

## PT-BR: 
Clustering: extraindo padrões de dados - Alura\
Estou aprendendo e seguindo o curso. Alguns incrementos e mudanças são liberdades tomadas por mim.\
OBS: O notebook está em inglês estão em inglês.

## Some insights
![image](https://github.com/vinimoti/Credit-card-Cluster-training/assets/126615931/8418d325-f1c3-4114-ab9d-e0b450d56e3f)

### Analysing Averages\
* Cluster 0: Have the highest balance. Even with a high credit limit, doesnt use the credit card with frequency. Preference in cash advance payment
* Cluster 1: Lowest balance, Rather use the credit card than cash in advance, looks like the high credit limit is due to its constant use of credit card tendency for paying in time and not using the minimum payment
* Cluster 2: High balance, uses the card constantly making high amount of purchases, low credit limit maybe beacuse of its tendency for using the minimum payment
* Cluster 3: High Balance, have a low usage of credit, using almost only cash in advance. Have a tendecy to make expensive purchases rather than buy more times
* Cluster 4: Low balance, makes a lot of purchases using mainly the credit card. Even not using minimum payment a lot doesnt have a high limit like Cluster 1
