## 🧩 Problem 1: Social Network Friend Suggestion (BFS)

### ⚙ Time Complexity
- The time graph shows a linear growth pattern as input size increases, confirming a *O(V + E)* behavior.  
- BFS traverses each vertex and edge once, making it efficient for sparse graphs.  
- For dense graphs, time rises proportionally with the number of edges.  
- Performance is steady and predictable, suitable for large social networks.

### 💾 Space Complexity
- Memory usage increases linearly with V due to adjacency lists and queue storage.  
- Requires *O(V)* space for visited and queue structures.  
- Efficient for moderate graph sizes, as it stores minimal additional data.

### 🧠 Conclusion
BFS is ideal for friend-suggestion systems where traversal depth is limited (friends-of-friends).  
It balances speed and memory well, making it scalable for large social networks like LinkedIn or Facebook.  
Efficient, simple, and practical for real-world social graph traversal.
