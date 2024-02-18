# RFM client segmentation
The goal of this project is to perform a client segmentation based on RFM analysis for an e-commerce site and to simulate the cluster stability in time.

## Data
Data comes from the Olist company https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce, contains csv extracts of 8 tables of a relational database.

## Notebooks
- [00_EDA](00_EDA.ipynb): exploratory analysis
- [01_Clustering](01_Clustering.ipynb): clustering and determining clients' profiles
- [02_Cluster_Evolution_Simulation](02_Cluster_Evolution_Simulation.ipynb): cluster stability simulation

## Clustering
The following algorithms were used and evaluated:
- K-Means
- Hierarchical Clustering
- DBSCAN

