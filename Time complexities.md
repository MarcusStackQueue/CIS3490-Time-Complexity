
| **Algorithm**                          | **Time Complexity**  | Extra Details/Notes                                                                             |
| -------------------------------------- | -------------------- | ----------------------------------------------------------------------------------------------- |
| Brute Force Longest Common Subsequence | O(n2$^m$)            | Brute force method                                                                              |
| Bottom-Up Pascals Identity             | O(nk)                |                                                                                                 |
| Top-Down Pascals Identity              | O(nk)                |                                                                                                 |
| Longest Common Subsequence             | O(nm)                | Implements dynamic programming                                                                  |
| Matrix-Product Brute Force             | Exponential Time$^*$ | $^*$Considers all Ω(4$^n$/n$^3$$^/$$^2$) possible parenthesizations (the Catalan  <br>numbers)  |
| Matrix Chain Multiplication            | O(n$^3$)             | Implements dynamic programming                                                                  |
| Breadth First Search (BFS)             | O(m + n)             |                                                                                                 |
| Depth First Search (DFS)               | O(m + n)             |                                                                                                 |
| Strongly Connected Components (SCC)    | O(m + n)             | Only requires two passes of DFS                                                                 |
| Dijkstra’s Algorithm                   | O((n + m) log n)     | Single source, all destinations                                                                 |
| Dijkstra’s Algorithm$^*$               | O(m log n)           | $^*$If the graph is connected                                                                   |
| Dijkstra’s Algorithm$^*$$^*$           | O(m + n log n)       | $^*$$^*$Fibonacci heap implementation                                                           |
| Bellman-Ford Algorithm                 | O(mn)                | Single source, all destinations                                                                 |
| Direct Acyclic Graphs (DAG)            | O(n + m)             | Single source, all destinations                                                                 |
| Floyd-Warshall Algorithm               | O(n$^3$)             |                                                                                                 |
| Dijkstra’s Algorithm$^*$$^*$$^*$       | O(n$^3$)             | $^*$$^*$$^*$All sources, all destinations, dense graph                                          |
| Dijkstra’s Algorithm$^*$$^*$$^*$$^*$   | O(n$^2$ log n )      | $^*$$^*$$^*$$^*$All sources, all destinations, sparse graph                                     |
| Transitive Closure Algorithm           | O(n$^3$)             | Floyd-Warshall implementation                                                                   |
| Transitive Closure Algorithm$^*$       | O(n(n + m))          | $^*$DFS Implementation                                                                          |
| Kruskal's Algorithm                    | O(m log n)           |                                                                                                 |
| Prim-Jarnik’s Algorithm                | O(m log n)           |                                                                                                 |
| Ford-Fulkerson Algorithm               | O(m*f*$^*$)          | f$^*$ is the value of the maximum flow                                                          |
| Edmonds-Karp Algorithm                 | O(nm$^2$)            |                                                                                                 |
| Push-relabel algorithms                | O(n$^2$m)            |                                                                                                 |
| Brute Force Pattern Matching           | O(nm)                |                                                                                                 |
| Boyer-Moore Algorithm                  | O(mn + \|Σ\|)        | Requires \|Σ\| time to calculate the *last* function                                            |
| Booyer-Moore Algorithm$^*$             | O(m + n + \|Σ\|)     | Considers a more sophisticated heuristic to skip characters based on the longest matched suffix |
| Knuth-Morris-Pratt (KMP)               | O(n + m)             |                                                                                                 |
