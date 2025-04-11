## Post Midterm Time Complexities (Pre Midterm Coming soon)
| **Algorithm**                          | **Time Complexity**  | Extra Details/Notes                                                                             |
| -------------------------------------- | -------------------- | ----------------------------------------------------------------------------------------------- |
| Brute Force Longest Common Subsequence | O(n2<sup>m</sup>)            | Brute force method                                                                              |
| Bottom-Up Pascals Identity             | O(nk)                |                                                                                                 |
| Top-Down Pascals Identity              | O(nk)                |                                                                                                 |
| Longest Common Subsequence             | O(nm)                | Implements dynamic programming                                                                  |
| Matrix-Product Brute Force             | Exponential Time<sup>*</sup> | <sup>*</sup>Considers all Ω(4$^n$/n$^3$$^/$$^2$) possible parenthesizations (the Catalan  <br>numbers)  |
| Matrix Chain Multiplication            | O(n<sup>3</sup>)             | Implements dynamic programming                                                                  |
| Breadth First Search (BFS)             | O(m + n)             |                                                                                                 |
| Depth First Search (DFS)               | O(m + n)             |                                                                                                 |
| Strongly Connected Components (SCC)    | O(m + n)             | Only requires two passes of DFS                                                                 |
| Dijkstra’s Algorithm                   | O((n + m) log n)     | Single source, all destinations                                                                 |
| Dijkstra’s Algorithm<sup>*</sup>               | O(m log n)           | <sup>*</sup>If the graph is connected                                                                   |
| Dijkstra’s Algorithm<sup>**</sup>           | O(m + n log n)       | <sup>**</sup>Fibonacci heap implementation                                                           |
| Bellman-Ford Algorithm                 | O(mn)                | Single source, all destinations                                                                 |
| Direct Acyclic Graphs (DAG)            | O(n + m)             | Single source, all destinations                                                                 |
| Floyd-Warshall Algorithm               | O(n<sup>3</sup>)             |                                                                                                 |
| Dijkstra’s Algorithm<sup>***</sup>       | O(n<sup>3</sup>)             | <sup>***</sup>All sources, all destinations, dense graph                                          |
| Dijkstra’s Algorithm<sup>****</sup>   | O(n<sup>2</sup> log n )      | <sup>****</sup>All sources, all destinations, sparse graph                                     |
| Transitive Closure Algorithm           | O(n<sup>3</sup>)             | Floyd-Warshall implementation                                                                   |
| Transitive Closure Algorithm<sup>*</sup>       | O(n(n + m))          | <sup>*</sup>DFS Implementation                                                                          |
| Kruskal's Algorithm                    | O(m log n)           |                                                                                                 |
| Prim-Jarnik’s Algorithm                | O(m log n)           |                                                                                                 |
| Ford-Fulkerson Algorithm               | O(m*f*<sup>*</sup>)          | f<sup>*</sup> is the value of the maximum flow                                                          |
| Edmonds-Karp Algorithm                 | O(nm<sup>2</sup>)            |                                                                                                 |
| Push-relabel algorithms                | O(n<sup>2</sup>m)            |                                                                                                 |
| Brute Force Pattern Matching           | O(nm)                |                                                                                                 |
| Boyer-Moore Algorithm                  | O(mn + \|Σ\|)        | Requires \|Σ\| time to calculate the *last* function                                            |
| Booyer-Moore Algorithm$^*$             | O(m + n + \|Σ\|)     | Considers a more sophisticated heuristic to skip characters based on the longest matched suffix |
| Knuth-Morris-Pratt (KMP)               | O(n + m)             |                                                                                                 |

## Pioneer Section Coming Soon
