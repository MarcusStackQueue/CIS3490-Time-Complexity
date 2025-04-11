# Time Complexities and Pioneers!!!
## Pre Midterm Time Complexities

| **Algorithm**                     | **Time Complexity**          | **Extra Details/Notes**                                                                                                                           |
| --------------------------------- | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| MergeSort                         | O(n log n)                   | This algorithm is stable.                                                                                                                         |
| QuickSort                         | O(n<sup>2</sup>)             | Worst case. Ex. if the pivot is the last element and the list is already sorted                                                                   |
| QuickSort<sup>*</sup>             | O(n log n)                   | <sup>*</sup>Expected running time if the pivot is random                                                                                          |
| HeapSort                          | O(n log n)                   |                                                                                                                                                   |
| BubbleSort                        | O(n<sup>2</sup>)             |                                                                                                                                                   |
| SelectionSort                     | O(n<sup>2</sup>)             |                                                                                                                                                   |
| BucketSort                        | O(n + N)                     | This algorithm is stable.                                                                                                                         |
| CountingSort                      | O(n + N)<sup>*</sup>         | <sup>*</sup>If N = O(n) then it runs in O(n) time.                                                                                                |
| RadixSort                         | O(d(n + N))<sup>*</sup>      | <sup>*</sup>If d is a constant, and the number of characters N is a constant, then the algorithm runs in O(n) time. This algorithm is stable.                                |
| RandomizedQuickSelect             | O(n<sup>2</sup>)             | Worst case                                                                                                                                        |
| RandomizedQuickSelect<sup>*</sup> | O(n)                         | <sup>*</sup>Expected case                                                                                                                         |
| DeterministicSelect               | O(n)                         |                                                                                                                                                   |
| PruneMedian                       | O(n)                         |                                                                                                                                                   |
| 01KnapSack Brute Force            | Exponential time<sup>*</sup> | <sup>*</sup>A brute force method is to try all 2<sup>n</sup> subsets of items, then pick the one with largest benefit and total weight at most C. |
| FractionalKnapSack                | O(n log n)                   |                                                                                                                                                   |
| Task Scheduling                   | O(n<sup>2</sup>)             |                                                                                                                                                   |
| Task Scheduling<sup>*</sup>       | O(n log n)                   | <sup>*</sup>Min-Heap implementation                                                                                                               |
| Huffman Coding                    | O(n + dlogd)<sup>*</sup>     | <sup>*</sup>String of length n with d distinct characters                                                                                         |
| Fuel Stop                         | O(n)                         |                                                                                                                                                   |
| Strassens Algorithm               | O(n<sup>log7</sup>)          |                                                                                                                                                   |
| Fastest Matrix Multiplication     | O(n<sup>2.376</sup>)         |                                                                                                                                                   |

## Post Midterm Time Complexities

| **Algorithm**                          | **Time Complexity**          | Extra Details/Notes                                                                                         |
| -------------------------------------- | ---------------------------- | ----------------------------------------------------------------------------------------------------------- |
| Brute Force Longest Common Subsequence | O(n2<sup>m</sup>)            | Brute force method                                                                                          |
| Bottom-Up Pascals Identity             | O(nk)                        |                                                                                                             |
| Top-Down Pascals Identity              | O(nk)                        |                                                                                                             |
| Longest Common Subsequence             | O(nm)                        | Implements dynamic programming                                                                              |
| Matrix-Product Brute Force             | Exponential Time<sup>*</sup> | <sup>*</sup>Considers all Ω(4<sup>n</sup>/n<sup>3/2</sup>) possible parenthesizations (the Catalan  <br>numbers)      |
| Matrix Chain Multiplication            | O(n<sup>3</sup>)             | Implements dynamic programming                                                                              |
| Breadth First Search (BFS)             | O(m + n)                     |                                                                                                             |
| Depth First Search (DFS)               | O(m + n)                     |                                                                                                             |
| Strongly Connected Components (SCC)    | O(m + n)                     | Only requires two passes of DFS                                                                             |
| Dijkstra’s Algorithm                   | O((n + m) log n)             | Single source, all destinations                                                                             |
| Dijkstra’s Algorithm<sup>*</sup>       | O(m log n)                   | <sup>*</sup>If the graph is connected                                                                       |
| Dijkstra’s Algorithm<sup>**</sup>      | O(m + n log n)               | <sup>**</sup>Fibonacci heap implementation                                                                  |
| Bellman-Ford Algorithm                 | O(mn)                        | Single source, all destinations                                                                             |
| Direct Acyclic Graphs (DAG)            | O(n + m)                     | Single source, all destinations                                                                             |
| Floyd-Warshall Algorithm               | O(n<sup>3</sup>)             |                                                                                                             |
| Dijkstra’s Algorithm<sup>***</sup>     | O(n<sup>3</sup>)             | <sup>***</sup>All sources, all destinations, dense graph                                                    |
| Dijkstra’s Algorithm<sup>****</sup>    | O(n<sup>2</sup> log n )      | <sup>****</sup>All sources, all destinations, sparse graph                                                  |
| Transitive Closure Algorithm           | O(n<sup>3</sup>)             | Floyd-Warshall implementation                                                                               |
| Transitive Closure Algorithm$^*$       | O(n(n + m))                  | $^*$DFS Implementation                                                                                      |
| Kruskal's Algorithm                    | O(m log n)                   |                                                                                                             |
| Prim-Jarnik’s Algorithm                | O(m log n)                   |                                                                                                             |
| Ford-Fulkerson Algorithm               | O(m*f*<sup>*</sup>)          | f<sup>*</sup> is the value of the maximum flow                                                              |
| Edmonds-Karp Algorithm                 | O(nm<sup>2</sup>)            |                                                                                                             |
| Push-relabel algorithms                | O(n<sup>2</sup>m)            |                                                                                                             |
| Brute Force Pattern Matching           | O(nm)                        |                                                                                                             |
| Boyer-Moore Algorithm                  | O(mn + \|Σ\|)                | Requires \|Σ\| time to calculate the *last* function                                                        |
| Booyer-Moore Algorithm<sup>*</sup>     | O(m + n + \|Σ\|)             | <sup>*</sup>Considers a more sophisticated heuristic to skip characters based on the longest matched suffix |
| Knuth-Morris-Pratt (KMP)               | O(n + m)                     |                                                                                                             |
## Pioneers!
- **Donald Knuth** - Developed TeX and wrote "The Art of Computer Programming". 
- **Frances Allen** - Known for her optimization, parallelization, and compiler contributions. Recipient of the Turing award winner. 
- **Richard Bellman** - Developed the Bellman-Ford Algorithm and introduced the concept of dynamic programming. 
- **Frank Grey** - Came up with Grey Code. 
- **Vulker Strassen** - Introduced the first matrix multiplication algorithm faster then O(n<sup>3</sup>) in O(n<sup>log7</sup>) time.
- **Julius Peter Christian Petersen** - Key contributions in graph theory, cryptography, and mathematical economics. Best known for the Peterson Graph
- **Edsger Dijkstra** - Solved the shortest paths problem, developed the first compiler for ALGOL 60, received a Turing award.
- **Lester Ford Jr.** - Developed the Ford-Fulkerson and Bellman-Ford algorithms, established the max-flow min-cut theorem.
- **Jack Edmonds** - Published the paper Paths, Trees and Flowers. Developed the blossom algorithm for constructing maximum matchings on graphs. This was the first polynomial-time algorithm for maximum matching in graphs.
- **Stephen Cook** - Formulated the P vs NP problem, came up with the Cook-Levin theorem. Professor at the University of Toronto (lets go Canada!).
