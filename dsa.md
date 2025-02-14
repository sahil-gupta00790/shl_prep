# Theoretical Questions on Data Structures

## Trees

1. The maximum number of nodes at level 'L' of a binary tree is:
**Answer:** 2^L, where L starts from 0

2. The time complexity of searching for a key in a balanced binary search tree is:
**Answer:** O(log n)

3. A complete binary tree with n nodes has a height of:
**Answer:** ⌊log₂(n)⌋

4. The minimum number of nodes in an AVL tree of height h is:
**Answer:** N(h) = N(h-1) + N(h-2) + 1, where N(0) = 1, N(1) = 2

5. In a binary tree with n nodes, the number of NULL links (empty children references) is:
**Answer:** n + 1

6. The maximum number of nodes in a binary tree of height h is:
**Answer:** 2^(h+1) - 1

## Heaps

7. The time complexity of building a heap from an array of n elements is:
**Answer:** O(n)

8. In a min-heap, for any given node at index i, its left child is at index:
**Answer:** 2i + 1

9. The time complexity of extracting the minimum element from a min-heap is:
**Answer:** O(log n)

10. In a binary max-heap of n nodes, the smallest element can be found in time:
**Answer:** O(n)

11. The number of comparisons needed to insert a new element into a heap of size n is at most:
**Answer:** ⌊log₂(n)⌋

## Hash Tables

12. The expected time complexity of insertion in a hash table with chaining is:
**Answer:** O(1 + α), where α is the load factor

13. The load factor of a hash table is defined as:
**Answer:** Number of items stored / Size of hash table

14. When using linear probing, the probability of clustering increases as the load factor:
**Answer:** Increases

15. The space complexity of separate chaining hash table implementation is:
**Answer:** O(n + m), where n is number of keys and m is table size

16. The best load factor range for optimal performance in a hash table is:
**Answer:** Between 0.4 and 0.7

## Graphs

17. The maximum number of edges in a directed graph with n vertices is:
**Answer:** n(n-1)

18. In an undirected connected graph with n vertices, the minimum number of edges is:
**Answer:** n-1

19. The maximum number of edges in a simple planar graph with n vertices (n ≥ 3) is:
**Answer:** 3n - 6

20. The chromatic number of a complete graph with n vertices is:
**Answer:** n

21. In a complete binary tree with n internal nodes, the number of leaf nodes is:
**Answer:** n + 1

22. The number of connected components in a tree is:
**Answer:** 1

23. The maximum number of edges in a bipartite graph with n vertices is:
**Answer:** ⌊n²/4⌋

24. The size of the transitive closure of a graph with n vertices is:
**Answer:** O(n²)

25. The minimum number of spanning trees a connected graph with n vertices can have is:
**Answer:** 1

