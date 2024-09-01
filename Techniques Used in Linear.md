### Techniques Used in Linear Data Structures

#### **1. Sliding Window Technique**
   - **Description:** Involves creating a window of a fixed or variable size that slides over the data structure (usually an array or string) to solve problems related to subarrays or substrings.
   - **Use Cases:** Maximum sum subarray of size `k`, longest substring without repeating characters.

#### **2. Two-Pointer Technique**
   - **Description:** Uses two pointers that traverse the data structure in different directions or at different speeds to efficiently solve problems.
   - **Use Cases:** Finding pairs in a sorted array that sum to a target value, merging two sorted arrays, or finding the middle element of a linked list.

#### **3. Prefix Sum Technique**
   - **Description:** Involves creating an auxiliary array that stores the sum of elements up to a certain index, allowing quick calculation of range sums or other cumulative properties.
   - **Use Cases:** Finding subarrays with a given sum, range sum queries in arrays.

#### **4. Kadane’s Algorithm (for Maximum Subarray Sum)**
   - **Description:** A dynamic programming-based technique to find the maximum sum subarray in a linear array. Although Kadane's algorithm is often presented as an algorithm, it is also a technique because it helps simplify other problems that require maximizing a sum in a sequence.
   - **Use Cases:** Maximum sum subarray problem.

#### **5. Fast and Slow Pointer Technique (Tortoise and Hare)**
   - **Description:** Involves using two pointers moving at different speeds to detect cycles in linked lists or to find the middle of a linked list.
   - **Use Cases:** Detecting cycles in linked lists, finding the middle of a linked list.

#### **6. Hashing for Efficient Lookup**
   - **Description:** Using a hash map (or hash set) to store and quickly look up data to solve problems involving frequent lookups or to check for the existence of elements.
   - **Use Cases:** Two-sum problem, checking for duplicates in arrays, finding subarrays with a given sum.

#### **7. Stack-Based Techniques**
   - **Monotonic Stack:** 
     - **Description:** A stack that remains either strictly increasing or decreasing, used to solve problems related to finding the next greater or smaller element.
     - **Use Cases:** Next greater element, largest rectangle in histogram.
   - **Balanced Parentheses:**
     - **Description:** Using a stack to check for balanced parentheses or to evaluate expressions.
     - **Use Cases:** Valid parentheses checking, evaluating postfix or prefix expressions.

#### **8. Queue-Based Techniques**
   - **Sliding Window Maximum:**
     - **Description:** Using a deque (double-ended queue) to maintain a sliding window of maximum values in an array.
     - **Use Cases:** Finding maximum values in a sliding window of an array.
   - **BFS-like Level Order Traversal:**
     - **Description:** Using a queue to traverse a linear structure in a breadth-first manner.
     - **Use Cases:** Level-order traversal in tree-like structures (though more often applied to non-linear structures).

#### **9. In-place Modification Techniques**
   - **Description:** Modifying the data structure in place to save space and avoid using extra memory.
   - **Use Cases:** Reversing an array or linked list, rotating an array, rearranging elements in an array.

#### **10. Merge and Conquer**
   - **Description:** Similar to the merge step in merge sort, this technique involves merging two sorted arrays or lists into a single sorted structure.
   - **Use Cases:** Merging two sorted arrays, merging k sorted lists.

#### **11. XOR Technique**
   - **Description:** Using the properties of the XOR bitwise operation to solve problems, particularly those involving pairs or uniqueness.
   - **Use Cases:** Finding the single number in an array where every other number appears twice, swapping two numbers without using a temporary variable.

#### **12. Difference Array Technique**
   - **Description:** Involves using a difference array to efficiently perform range update queries.
   - **Use Cases:** Range increment operations, manipulating a range of elements in an array efficiently.

#### **13. Counting Frequency**
   - **Description:** Using a frequency array or hash map to count the occurrences of elements in a linear data structure.
   - **Use Cases:** Checking for anagram strings, finding the majority element, counting sort.

#### **14. Two-Sum/Multiple Sum Techniques**
   - **Description:** Techniques that involve finding pairs or groups of elements in an array that sum to a specific value using a combination of hashing and two-pointer techniques.
   - **Use Cases:** Two-sum problem, three-sum problem.

These techniques are foundational in solving various problems efficiently in linear data structures such as arrays, linked lists, stacks, and queues. Understanding when and how to apply these techniques can significantly reduce the time complexity of algorithms and improve overall problem-solving efficiency.
