# 🧭 Path Visualizer

An interactive **Pathfinding Algorithm Visualizer** built using **HTML, CSS, and JavaScript**.  
This project helps users **understand how different graph traversal and shortest-path algorithms work step by step** through real-time visual animations on a grid.

---
## 🌐 Live Demo

🔗 **Path Visualizer (GitHub Pages)**  
https://itzrv19.github.io/Path-Visualizer/


---

## 🚀 Features

- 📊 Visualizes popular pathfinding algorithms
- 🟦 Interactive grid with start & end nodes
- ⛔ Wall/obstacle creation
- 🎞️ Step-by-step animation
- ⚡ Real-time comparison of algorithms
- 🌐 Runs fully in the browser (no backend)

---

## 🧠 Algorithms Implemented

| Algorithm | Type | Guarantees Shortest Path | Notes |
|---------|------|--------------------------|------|
| **BFS (Breadth-First Search)** | Unweighted | ✅ Yes | Explores level by level |
| **DFS (Depth-First Search)** | Unweighted | ❌ No | Faster but not optimal |
| **Dijkstra’s Algorithm** | Weighted | ✅ Yes | Classic shortest path |
| **A\* (A-Star)** | Heuristic-based | ✅ Yes | Faster using heuristics |

---

## 🛠️ Tech Stack

- **HTML5** – Structure  
- **CSS3** – Styling & animations  
- **JavaScript (ES6)** – Logic & algorithms  

---

## 📂 Project Structure
```
Path-Visualizer-main/
│
├── index.html
│
├── script/
│ ├── bfs.js
│ ├── dfs.js
│ ├── dijkstra.js
│ ├── astar.js
│ └── dist/
│ ├── bfs.dev.js
│ ├── dfs.dev.js
│ ├── dijkstra.dev.js
│ └── astar.dev.js
│
├── assests/
│ └── images/
│ ├── img1.webp
│ ├── img2.webp
│ ├── img3.webp
│ ├── img4.webp
│ └── img5.webp
│
└── README.md

```
## 🎮 How to Use

1. Select a **pathfinding algorithm**
2. Place:
   - 🟢 **Start node**
   - 🔴 **End node**
   - ⬛ **Walls / obstacles**
3. Click **Visualize**
4. Watch how the algorithm explores the grid step by step
5. Reset the grid and try another algorithm

