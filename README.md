# Cluster-analysis
A big mall that conatins the infromation of their clients. Clients have to give some infromation to get the membership card through this they collect those data of theri clients. 
Applied the clustering algorithms in the dataset to segment the customers into different Groups.
Applied both K-means clustering and Hierarchical Clustering in the same dataset
Features in the dataset:
* CusomerID
* Genre 
* Age
* Annual Income (used this one as first key features)
* Spending Score (used this one as final key features to train the model)

# K-Means Clustering 
using the Annual income and Spending score features, 
divided the customers into 5 different Groups/Clusters based on their common characteristic:
  1. Blue Cluster (Careless  Group (Low Income but High Spending Score))
  2. Green Cluster (Target  Group (High Income and High spending score)) 
  3. Red Cluster (Average  Group (Average Income and Average Spending Score))
  4. Cyan Cluster (Sensible Group (Low Income and Low Spending Score))
  5. Magenta Cluster (Careful  Group (High Income but low spending score))

So, depending on that information mall company can target their main customers.

# Hierarchical clustering
Same process applied again but in differnt Algorithm 
  1. Blue One (Average Group (Average Income and Average Spending Score))      
  2. Green One (Target Group (High Income and High spending score)) 
  3. Red One (Careful Group (High Income but low spending score)) 
  4. Cyan One (Careless Group (Low Income but High Spending Score))
  5. Magenta One (Sensible Group (Low Income and Low Spending Score))


