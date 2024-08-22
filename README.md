# Floyd Warshall Algorithm
# Features:
Input: The graph is represented as a 2D vector (adjacency matrix), where graph[i][j] holds the weight of the edge from vertex i to vertex j. If no edge exists between two vertices, the value is set to INF (infinity).

Output: The program prints the shortest distance between every pair of vertices in a matrix format. If no path exists between two vertices, it outputs "INF".

# How It Works:
The algorithm considers each vertex in the graph as an intermediate vertex and updates the shortest paths between every pair of vertices.
If a shorter path is found through an intermediate vertex, the algorithm updates the distance matrix.

# Usage:
Compile the code using any C++ compiler.
Run the executable to see the output for the provided graph.

