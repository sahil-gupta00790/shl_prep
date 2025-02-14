**Time Complexities of Common CS Algorithms**

### **Sorting Algorithms**
| Algorithm            | Best Case | Average Case | Worst Case |
|----------------------|----------|-------------|------------|
| **Bubble Sort**      | 𝑂(n)     | 𝑂(n²)       | 𝑂(n²)      |
| **Selection Sort**   | 𝑂(n²)    | 𝑂(n²)       | 𝑂(n²)      |
| **Insertion Sort**   | 𝑂(n)     | 𝑂(n²)       | 𝑂(n²)      |
| **Merge Sort**       | 𝑂(n log n) | 𝑂(n log n)  | 𝑂(n log n) |
| **Quick Sort**       | 𝑂(n log n) | 𝑂(n log n)  | 𝑂(n²) (worst case occurs when pivot is smallest/largest) |
| **Heap Sort**        | 𝑂(n log n) | 𝑂(n log n)  | 𝑂(n log n) |
| **Counting Sort**    | 𝑂(n + k) | 𝑂(n + k)    | 𝑂(n + k)   |
| **Radix Sort**       | 𝑂(nk)    | 𝑂(nk)       | 𝑂(nk)      |
| **Bucket Sort**      | 𝑂(n + k) | 𝑂(n + k)    | 𝑂(n²)      |

### **Searching Algorithms**
| Algorithm          | Best Case | Average Case | Worst Case |
|--------------------|----------|-------------|------------|
| **Linear Search**  | 𝑂(1)     | 𝑂(n)        | 𝑂(n)       |
| **Binary Search**  | 𝑂(1)     | 𝑂(log n)    | 𝑂(log n)   |
| **Jump Search**    | 𝑂(1)     | 𝑂(√n)       | 𝑂(√n)      |
| **Exponential Search** | 𝑂(1) | 𝑂(log n)    | 𝑂(log n)   |
| **Interpolation Search** | 𝑂(1) | 𝑂(log log n) | 𝑂(n) |

### **Graph Algorithms**
| Algorithm              | Best Case     | Average Case     | Worst Case     |
|------------------------|--------------|-----------------|---------------|
| **BFS (Breadth First Search)**  | 𝑂(1) | 𝑂(V + E) | 𝑂(V + E) |
| **DFS (Depth First Search)**  | 𝑂(1) | 𝑂(V + E) | 𝑂(V + E) |
| **Dijkstra’s Algorithm** | 𝑂(V log V) | 𝑂((V + E) log V) | 𝑂((V + E) log V) |
| **Bellman-Ford Algorithm** | 𝑂(V) | 𝑂(VE) | 𝑂(VE) |
| **Floyd-Warshall Algorithm** | 𝑂(n³) | 𝑂(n³) | 𝑂(n³) |
| **Kruskal’s Algorithm** | 𝑂(E log E) | 𝑂(E log E) | 𝑂(E log E) |
| **Prim’s Algorithm** | 𝑂(V log V) | 𝑂(E log V) | 𝑂(E log V) |

### **Other Important Algorithms**
| Algorithm                | Best Case  | Average Case | Worst Case  |
|--------------------------|-----------|-------------|------------|
| **Kadane’s Algorithm (Max Subarray Sum)** | 𝑂(n) | 𝑂(n) | 𝑂(n) |
| **KMP (Pattern Matching)** | 𝑂(n) | 𝑂(n + m) | 𝑂(n + m) |
| **Rabin-Karp (Pattern Matching)** | 𝑂(n) | 𝑂(n + m) | 𝑂(nm) |
| **Union-Find (Disjoint Set)** | 𝑂(1) | 𝑂(α(n)) | 𝑂(α(n)) |
| **Topological Sorting** | 𝑂(V + E) | 𝑂(V + E) | 𝑂(V + E) |

(*Here, V = Number of vertices, E = Number of edges, α(n) = Inverse Ackermann function, m = pattern length in string matching.*)
