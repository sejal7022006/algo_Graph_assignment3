## 🗺 Problem 2: Route Finding (Google Maps) – Bellman-Ford

### ⚙ Time Complexity
- The plot shows a quadratic to cubic growth as vertices and edges increase, matching *O(V × E)*.  
- Each edge is relaxed (V–1) times, causing high computational cost.  
- Suitable for smaller graphs or where negative weights exist, but slower for dense networks.

### 💾 Space Complexity
- Uses *O(V)* space for the distance array and edge list.  
- Memory usage grows linearly with the number of vertices, remaining moderate overall.  
- Efficient in memory but limited by its time cost.

### 🧠 Conclusion
Bellman-Ford ensures accurate shortest paths even with negative weights, unlike Dijkstra.  
It’s reliable and robust for routing or cost-based problems where edges may have penalties, but less efficient for real-time navigation.  
Best suited for smaller networks or systems requiring correctness over speed.
