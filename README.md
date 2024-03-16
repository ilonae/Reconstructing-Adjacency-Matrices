Coding Challenge: Reconstructing Adjacency Matrices 



Problem Statement:

Your task is to reconstruct adjacency matrices from the dataset representing the upper triangles of 10x10 adjacency matrices.
These entries encode the adjacency relationships between points inside cities in the given dataset.
Each entry contains information about a city and the adjacency of points A-J in this city to each other in the form of binary connections.



Challenge:

--Read the dataset from a CSV file containing the database entries.
--Reconstruct the adjacency matrices based on the provided data.
--Add labels for the points, let them be called A-J.
--Visualize the reconstructed matrices in a command-line interface (CLI) print format.



Bonus Task:

Propose an alternative encoding of the data that might be suitable for this scenario and justify your choice.
Discuss how your proposed encoding could enhance the overall solution and its implementation.



Dataset Information:

--Index: The index of the entry.
--City Name: The name of each city in the dataset.
--Binary Connections: Binary values indicating the adjacency relationships between cities. A value of 1 represents adjacency, and 0 represents no adjacency. The connections arn non-directional.

