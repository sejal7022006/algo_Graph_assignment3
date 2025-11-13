##  Problem 3: Emergency Response System – Dijkstra’s Algorithm

### Time Complexity
- Execution time increases almost linearly with E log V, aligning with *O(E log V)* complexity.  
- The priority queue (min-heap) significantly improves efficiency over simple BFS.  
- Performs exceptionally well for large, positive-weighted graphs.

### Space Complexity
- Memory grows linearly with V and E, due to adjacency list and distance map.  
- Space requirement is *O(V)* for distance tracking and *O(E)* for graph structure.  
- Reasonably efficient, with predictable scaling as graph size grows.

### Conclusion
Dijkstra’s algorithm is optimal for positive-weighted shortest path problems, such as emergency vehicle routing.  
It achieves the best trade-off between time and space among all tested algorithms.  
Highly practical for navigation, logistics, and disaster management applications.

---
