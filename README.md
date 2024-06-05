## Reconstructing Adjacency Matrices 



### Problem Statement:

The task is to reconstruct adjacency matrices from the dataset representing the upper triangles of 10x10 adjacency matrices.
These entries encode the adjacency relationships between points inside cities in the given dataset.
Each entry contains information about a city and the adjacency of points A-J in this city to each other in the form of binary connections.



### Info:

- The dataset (CSV file) contains the database entries.
- The adjacency matrices will be based on the provided data.
- Labels for the adjacency points are called A-J.
- The reconstructed matrices are visualized in a print format.
- Check out the Jupyter Notebook to execute all cells and then accordingly!



### Bonus:

- Proposing an alternative encoding of the data that might be suitable for this scenario (TBC).
- Discussing how the encoding could enhance the overall solution and its implementation (TBC).



### Dataset Information:

- Index: The index of the entry.
- City Name: The name of each city in the dataset.
- Binary Connections: Binary values indicating the adjacency relationships between cities. A value of 1 represents adjacency, and 0 represents no adjacency. The connections arn non-directional.

