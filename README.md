This repository presents a GNN approach for a recommendation system based on pairwise preferences. For this, we have a dataset consisting the prefferences of a group of users regarding books. 
From this dataset, we extract their prefferences as pairwise, giving 1 if the first item is favoured over the second, 0.5 if they are equal and 0 otherwise. 
From there, they are built into a Graph Neural Network, where the prefferences are compared. From there, we use a Top-K Similarity approach
