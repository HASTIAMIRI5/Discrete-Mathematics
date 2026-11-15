# Topic 5: Graph Theory

## 1. Introduction to Graphs

A graph is a mathematical structure used to represent relationships between objects.

A graph G consists of:
- a set of vertices V
- a set of edges E

A graph may be directed or undirected.

### Undirected graph
If two vertices are connected by an edge, the relationship is symmetric.

### Directed graph
The edge has a direction, meaning the relationship goes one way.

## 2. Types of Graphs

### Simple graph
No loops and no multiple edges.

### Multigraph
Allows multiple edges between the same pair of vertices.

### Weighted graph
Each edge has a weight or cost.

### Complete graph K_n
Every pair of distinct vertices is connected by an edge.

A complete graph with n vertices has n(n-1)/2 edges.

## 3. Degree of a Vertex

The degree of a vertex is the number of edges incident to it.

In an undirected graph:
- sum of all degrees = 2|E|

This is the Handshaking Lemma.

## 4. Paths and Cycles

A path is a sequence of vertices connected by edges.

A cycle is a path that starts and ends at the same vertex without repeating edges.

### Connectivity
A graph is connected if there is a path between every pair of vertices.

## 5. Eulerian and Hamiltonian Paths

### Eulerian path
A path that uses every edge exactly once.

A graph has an Eulerian circuit if and only if every vertex has even degree.

### Hamiltonian path
A path that visits every vertex exactly once.

Finding Hamiltonian paths is computationally difficult.

## 6. Bipartite Graphs

A graph is bipartite if its vertices can be split into two sets such that every edge connects one vertex in each set.

Example:
Students and courses form a bipartite graph because a student can be connected to courses they take.

## 7. Planar Graphs

A planar graph can be drawn in the plane without crossing edges.

Euler's formula for connected planar graphs:
V - E + F = 2

where F is the number of faces.

## 8. Graph Representations

Graphs can be represented as:
- adjacency lists
- adjacency matrices
- edge lists

Each representation is useful depending on the problem.

## 9. Applications

Graph theory is used in:
- social networks
- transportation maps
- computer networks
- scheduling
- web crawlers
- operation research

## 10. Summary

Graph theory models relationships between objects using vertices and edges. By studying degrees, connectivity, paths, cycles, and special graph classes, we can analyze and solve many real-world problems.
