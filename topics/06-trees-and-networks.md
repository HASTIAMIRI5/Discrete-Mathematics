# Topic 6: Trees and Networks

## 1. What Is a Tree?

A tree is a connected graph with no cycles.

Equivalent definitions:
- a connected acyclic graph
- a graph where there is exactly one simple path between any two vertices

## 2. Basic Tree Properties

For a tree with n vertices:
- it has exactly n - 1 edges
- it is connected
- it has no cycles

These properties are extremely useful in proofs and graph algorithms.

## 3. Rooted Trees

A rooted tree has one designated vertex called the root.

Terms:
- parent
- child
- leaf
- internal node
- depth
- height

## 4. Binary Trees

A binary tree is a rooted tree in which each node has at most two children.

A full binary tree has every internal node with exactly two children.

A binary tree is the basic structure for many algorithms and data structures.

## 5. Spanning Trees

A spanning tree of a connected graph is a subgraph that:
- includes all vertices
- is connected
- has no cycles

A connected graph with n vertices has a spanning tree with n - 1 edges.

## 6. Minimum Spanning Tree (MST)

A minimum spanning tree connects all vertices with the minimum possible total edge weight.

Common algorithms:
- Kruskal's algorithm
- Prim's algorithm

These algorithms are important in networking and optimization.

## 7. Tree Traversals

### Preorder
Visit root, then left subtree, then right subtree.

### Inorder
Visit left subtree, then root, then right subtree.

### Postorder
Visit left subtree, then right subtree, then root.

These traversals are used in parsing, expression evaluation, and data processing.

## 8. Applications of Trees

Trees appear in:
- file systems
- decision trees
- search algorithms
- syntax trees
- network design
- hierarchy modeling

## 9. Why Trees Matter

Trees are useful because they simplify complex structures. They maintain organization without cycles, making them efficient and easy to traverse.

## 10. Summary

Trees are special connected acyclic graphs. They are efficient for representing hierarchical relationships and are central to both theoretical and applied computer science.
