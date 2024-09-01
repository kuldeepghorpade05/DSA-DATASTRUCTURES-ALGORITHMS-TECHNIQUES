### Techniques Used in Non-Linear Data Structures

#### **1. Depth-First Search (DFS)**
   - **Description:** A traversal technique used to explore all possible paths in a graph or tree by going as deep as possible along each branch before backtracking.
   - **Use Cases:** Pathfinding in graphs, solving puzzles like mazes, checking for cycles in a graph, topological sorting.

#### **2. Breadth-First Search (BFS)**
   - **Description:** A traversal technique that explores all neighbors at the present depth level before moving on to nodes at the next depth level.
   - **Use Cases:** Shortest path in unweighted graphs, level-order traversal in trees, finding connected components in a graph.

#### **3. Backtracking**
   - **Description:** A technique for solving problems incrementally by building a solution piece by piece and abandoning solutions that fail to satisfy the problem's constraints.
   - **Use Cases:** N-Queens problem, solving Sudoku, generating permutations or combinations, Hamiltonian paths.

#### **4. Dynamic Programming (on Trees and Graphs)**
   - **Description:** A technique that solves complex problems by breaking them down into simpler subproblems and storing the results to avoid redundant calculations.
   - **Use Cases:** Longest path in a Directed Acyclic Graph (DAG), tree-based problems like finding the diameter of a tree, dynamic programming on grids.

#### **5. Divide and Conquer (on Non-Linear Structures)**
   - **Description:** A technique where the problem is divided into smaller subproblems, each of which is solved independently, and then the solutions are combined.
   - **Use Cases:** Quickselect (for finding the k-th smallest element), divide and conquer approaches on trees, graph partitioning problems.

#### **6. Union-Find (Disjoint Set Union - DSU)**
   - **Description:** A technique used to manage a partition of a set into disjoint subsets and efficiently handle operations like union and find.
   - **Use Cases:** Kruskal’s algorithm for Minimum Spanning Tree (MST), detecting cycles in undirected graphs, connected component analysis.

#### **7. Topological Sorting**
   - **Description:** A technique used to order nodes in a Directed Acyclic Graph (DAG) such that for every directed edge `u -> v`, node `u` comes before node `v`.
   - **Use Cases:** Task scheduling, resolving symbol dependencies in compilers, determining the order of courses in a prerequisite system.

#### **8. Tree Traversal Techniques**
   - **Inorder Traversal:**
     - **Description:** Visits the left subtree, the node, and then the right subtree.
     - **Use Cases:** Binary search tree (BST) operations like finding the kth smallest element.
   - **Preorder Traversal:**
     - **Description:** Visits the node, then the left subtree, and then the right subtree.
     - **Use Cases:** Copying a tree, generating prefix expressions.
   - **Postorder Traversal:**
     - **Description:** Visits the left subtree, the right subtree, and then the node.
     - **Use Cases:** Deleting a tree, evaluating postfix expressions.
   - **Level Order Traversal:**
     - **Description:** Traverses each level of the tree from top to bottom.
     - **Use Cases:** Finding the width of a binary tree, printing nodes level by level.

#### **9. Heuristic Search Techniques**
   - **Description:** Techniques that use heuristics or informed guesses to reduce the search space and solve problems more efficiently.
   - **Use Cases:** A* search algorithm for pathfinding, greedy best-first search in AI, solving optimization problems in graphs.

#### **10. Greedy Technique on Graphs**
   - **Description:** A technique that builds up a solution piece by piece, choosing the most immediate, optimal solution at each step.
   - **Use Cases:** Prim's and Kruskal's algorithms for MST, Dijkstra’s algorithm for shortest path in weighted graphs.

#### **11. Graph Coloring**
   - **Description:** A technique used to assign colors to the vertices of a graph so that no two adjacent vertices share the same color.
   - **Use Cases:** Scheduling problems, register allocation in compilers, map coloring.

#### **12. Shortest Path Algorithms**
   - **Description:** Techniques used to find the shortest path between nodes in a graph.
   - **Use Cases:** Dijkstra’s algorithm, Bellman-Ford algorithm, Floyd-Warshall algorithm for all-pairs shortest paths.

#### **13. Minimum Spanning Tree (MST)**
   - **Description:** Techniques used to find a spanning tree of a graph with the minimum possible total edge weight.
   - **Use Cases:** Kruskal’s algorithm, Prim’s algorithm, designing networks (e.g., computer networks, road networks).

#### **14. Flow Networks and Max-Flow Algorithms**
   - **Description:** Techniques used to find the maximum flow in a flow network.
   - **Use Cases:** Ford-Fulkerson algorithm, Edmonds-Karp algorithm, network routing, matching problems in bipartite graphs.

#### **15. LCA (Lowest Common Ancestor) in Trees**
   - **Description:** A technique used to find the lowest common ancestor of two nodes in a tree.
   - **Use Cases:** Binary tree and Binary Search Tree operations, solving queries on trees in constant time after preprocessing.

#### **16. Eulerian Path and Circuit**
   - **Description:** A technique used to find a path or circuit that visits every edge of a graph exactly once.
   - **Use Cases:** Solving problems related to graph traversal, circuit design, DNA sequencing.

#### **17. Strongly Connected Components (SCC)**
   - **Description:** A technique used to identify all the strongly connected components in a directed graph.
   - **Use Cases:** Kosaraju’s algorithm, Tarjan’s algorithm, analyzing the structure of a graph, solving 2-SAT problems.

#### **18. Segment Trees and Fenwick Trees (Binary Indexed Trees)**
   - **Description:** Advanced data structures used for efficient range queries and updates.
   - **Use Cases:** Range minimum queries, range sum queries, point updates in arrays.

These techniques are foundational for solving complex problems that involve non-linear data structures such as trees, graphs, and networks. Understanding these techniques is essential for designing efficient algorithms to handle hierarchical, relational, and networked data.
