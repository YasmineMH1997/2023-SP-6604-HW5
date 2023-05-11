# 2023-SP-6604-HW5

Implement Dynamic Data Replica allocation method as follows:

1. Consider a graph of arbitrary number of nodes. 

2. Assign replicas based on the space available at each node as an input. 

3. Implement the three methods taught in the class successively; output of first method where replica allocations are done by individual nodes become input to the nest method where replica allocations are done by nbrs only, whose output becomes the input for the replica allocation done in groups of more stable nodes.

4. You can generate read and write probabilities randomly at each node. 

5. Each node can own their own data items and have some number of replicas.

The program should take generic input regarding the number of nodes in a graph, buffer space to hold replica at each node, and different read and write probabilities.
