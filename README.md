This project implements **Dijkstra's Algorithm** in C to find the **shortest distance from a source vertex to all other vertices** in a weighted graph.

The graph is represented using an **Adjacency Matrix**.

---

 Concept Overview

 Dijkstra's Algorithm

Dijkstra’s Algorithm is a greedy algorithm used to find the **shortest path** from a single source vertex to all other vertices in a graph with **non-negative edge weights**.

It is widely used in:

- GPS Navigation Systems
- Network Routing Protocols
- Map Applications
- Shortest path problems

---

 How the Algorithm Works

1. Initialize distance of all vertices as **infinity (INF)**.
2. Set distance of source vertex to **0**.
3. Pick the vertex with minimum distance that is not visited.
4. Update distances of its adjacent vertices.
5. Repeat until all vertices are visited.

---

 Program Features

- Uses adjacency matrix representation
- User input for number of vertices
- User input for adjacency matrix
- User input for starting vertex
- Displays shortest distance from source to all vertices
- Uses greedy approach

 Input Format

1. Enter number of vertices  
2. Enter adjacency matrix  
   - Enter `0` if there is no edge  
3. Enter starting vertex  
