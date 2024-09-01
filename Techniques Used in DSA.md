### Techniques Used in DSA Problems

#### **Linear Techniques**
1. **Sliding Window Technique**
   - Used for problems involving subarrays or substrings where a fixed or variable size window slides over the data structure (e.g., finding the maximum sum subarray of size `k`).
  
2. **Two-Pointer Technique**
   - Involves using two pointers that move at different speeds or directions to solve problems efficiently (e.g., finding pairs in a sorted array that sum to a target value).
  
3. **Greedy Technique**
   - Makes the locally optimal choice at each stage with the hope of finding a global optimum (e.g., activity selection problem, fractional knapsack).
  
4. **Prefix Sum**
   - Involves creating an auxiliary array that stores the sum of elements up to a certain index, allowing for quick range sum queries (e.g., finding subarrays with a given sum).
  
5. **Kadane’s Algorithm**
   - A dynamic programming technique to find the maximum sum subarray in a linear array.

#### **Non-Linear Techniques**
1. **Divide and Conquer**
   - Breaks a problem into smaller subproblems, solves each subproblem independently, and then combines the results (e.g., merge sort, quick sort, binary search).
  
2. **Dynamic Programming**
   - Solves problems by breaking them down into simpler subproblems and storing the results to avoid redundant calculations (e.g., Fibonacci sequence, longest common subsequence).
  
3. **Backtracking**
   - Systematically searches for a solution by trying partial solutions and then abandoning them if they are not suitable (e.g., N-Queens problem, Sudoku solver).
  
4. **Branch and Bound**
   - Similar to backtracking but includes bounds to eliminate large sections of the search space (e.g., solving the traveling salesman problem).
  
5. **Memoization**
   - A technique of storing the results of expensive function calls and returning the cached result when the same inputs occur again (e.g., recursive dynamic programming problems).
  
6. **Graph Traversal Techniques**
   - **DFS (Depth-First Search)**: Explores as far as possible along each branch before backtracking.
   - **BFS (Breadth-First Search)**: Explores all neighbors at the present depth level before moving on to nodes at the next depth level.

7. **Tree-based Techniques**
   - **Recursion in Trees**: Leveraging the hierarchical structure of trees for solving problems like tree traversal, finding the height, and solving binary tree problems.
   - **Segment Trees**: Used for answering range queries and updating elements in an array efficiently.
   - **Fenwick Tree (Binary Indexed Tree)**: Provides an efficient way to compute prefix sums and update elements in an array.

8. **Graph-based Techniques**
   - **Union-Find**: A technique to keep track of disjoint sets and efficiently manage the merging of these sets (e.g., in Kruskal’s algorithm for MST).
   - **Topological Sorting**: Used to order nodes in a directed acyclic graph (DAG) such that for every directed edge `u -> v`, node `u` comes before `v`.

9. **Heuristics**
   - Techniques used to find a good enough solution where an optimal solution is not feasible (e.g., A* search algorithm in pathfinding).

10. **Reduction**
    - Simplifying a complex problem by reducing it to a previously solved problem (e.g., reducing 3-SAT to 2-SAT, or reducing graph coloring to clique detection).

These techniques form the foundation of many DSA problems, and understanding when and how to apply them is crucial for solving complex problems efficiently.
