# Dijkstra’s Algorithm – Shortest Path Finder

A comprehensive implementation of **Dijkstra’s Algorithm** for finding the **shortest paths from a source node to all other nodes** in a weighted graph.  
This project focuses on **algorithmic correctness, performance, scalability, and real-world use cases**, making it suitable for **academic study, competitive programming, and production systems**.

---

## 📌 Table of Contents

1. Introduction  
2. Problem Statement  
3. Algorithm Overview  
4. Why Dijkstra’s Algorithm  
5. Applications  
6. Graph Representation  
7. Data Structures Used  
8. Time & Space Complexity  
9. Project Features  
10. Input & Output Format  
11. Implementation Details  
12. Example Walkthrough  
13. Edge Cases Handled  
14. Limitations  
15. Optimization Techniques  
16. Comparison with Other Algorithms  
17. Real-World Use Cases  
18. Project Structure  
19. How to Run  
20. Testing Strategy  
21. Future Enhancements  
22. Academic Relevance  
23. Interview Relevance  
24. License  
25. Author  

---

## 🧠 Introduction

Dijkstra’s Algorithm is one of the most fundamental and widely used **graph algorithms** in computer science.  
It computes the **shortest path** from a given **source vertex** to all other vertices in a graph with **non-negative edge weights**.

This project demonstrates:
- Correct implementation of Dijkstra’s Algorithm
- Efficient use of data structures
- Clean, modular, and readable code
- Practical considerations for real-world systems

---

## ❓ Problem Statement

Given:
- A weighted graph `G(V, E)`
- A source vertex `S`

Find:
- The **shortest distance** from `S` to every other vertex in the graph
- Optionally, the **actual shortest path**

Constraints:
- Edge weights must be **non-negative**
- Graph may be directed or undirected

---

## ⚙️ Algorithm Overview

Dijkstra’s Algorithm works by:
1. Initializing distances from the source to all vertices as infinity
2. Setting the source distance to 0
3. Using a **priority queue (min-heap)** to always expand the closest unvisited node
4. Relaxing edges and updating distances
5. Repeating until all nodes are visited or the queue is empty

---

## 💡 Why Dijkstra’s Algorithm?

✔ Guarantees optimal shortest paths  
✔ Efficient for sparse graphs  
✔ Widely used in real-world systems  
✔ Simple yet powerful  
✔ Foundation for advanced routing algorithms  

---

## 🌍 Applications

- GPS Navigation Systems
- Google Maps routing
- Network routing protocols
- Traffic management systems
- Game AI pathfinding
- Robotics navigation
- Logistics and supply chain optimization
- Social network analysis

---

## 🗺️ Graph Representation

The graph is represented using:

- **Adjacency List**
- Each node maintains a list of `(neighbor, weight)` pairs

Advantages:
- Space efficient
- Faster iteration over neighbors
- Suitable for sparse graphs

---

## 🧱 Data Structures Used

| Data Structure | Purpose |
|---------------|--------|
| Priority Queue (Min Heap) | Select next closest node |
| HashMap / Array | Store distances |
| Visited Set | Prevent reprocessing |
| Parent Map | Path reconstruction |

---

## ⏱️ Time Complexity

| Implementation | Time Complexity |
|---------------|----------------|
| Array-based | O(V²) |
| Priority Queue | O((V + E) log V) |

---

## 💾 Space Complexity

- O(V + E)
- Stores graph, distance array, and priority queue

---

## ✨ Project Features

- Supports directed & undirected graphs
- Supports weighted graphs
- Efficient priority queue implementation
- Path reconstruction
- Handles disconnected graphs
- Clean modular code
- Easy to extend

---

## 📥 Input Format

