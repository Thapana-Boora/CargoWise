# 🚚 CargoWise – Logistics Route & Profit Optimizer

> A browser-based logistics simulation that finds the **shortest delivery route** and **maximizes cargo profit** using two classic algorithms — all in a single HTML file.

---

## 🖥️ Live Demo

Open `cargowise.html` directly in any browser. No installation, no server, no dependencies.

---

## 📌 Features

| Feature | Description |
|---|---|
| **Graph Visualization** | Cities as nodes, roads as weighted edges on HTML5 Canvas |
| **Shortest Path** | Dijkstra's Algorithm highlights the optimal route in green |
| **Truck Animation** | Delivery truck drives along the Dijkstra path on the graph, rotating at each turn |
| **Package Optimizer** | 0/1 Knapsack DP selects the most profitable packages within truck capacity |
| **DP Table** | Full dynamic programming table rendered with highlighted cells |
| **Results Dashboard** | Shows Route · Travel Cost · Max Profit · Net Profit together |
| **3-Panel Layout** | Network Setup · Graph Canvas · Cargo Packages — all visible at once |

---

## 🧠 Algorithms Used

### Dijkstra's Algorithm *(Greedy — Shortest Path)*
- Finds the minimum-cost path between two cities in a weighted undirected graph
- Time: **O(V²)** · Space: **O(V)**

### 0/1 Knapsack *(Dynamic Programming)*
- Selects the most profitable combination of packages within the truck's weight limit
- Time: **O(n·W)** · Space: **O(n·W)**

---

## 🚀 How to Use

1. **Clone or download** this repository
2. Open `cargowise.html` in your browser
3. **Set up the network** — enter city names and roads with costs
4. **Add packages** — enter package ID, weight, and profit
5. **Set truck capacity** and choose source/destination
6. Click **🚀 Optimize Route & Cargo**
7. Watch the truck drive the shortest path and see the results

---

## 📁 Project Structure

```
cargowise/
│
├── cargowise.html      # Complete application (HTML + CSS + JS in one file)
└── README.md           # This file
```

Everything runs in a single self-contained HTML file — no frameworks, no build tools, no backend.

---

## 🛠️ Tech Stack

- **HTML5** — Structure and layout
- **CSS3** — Dark logistics dashboard theme with CSS variables
- **JavaScript (ES6+)** — Algorithm logic, DOM manipulation, Canvas rendering
- **HTML5 Canvas API** — Graph drawing and truck animation

---

## 📚 Course Details

| Field | Details |
|---|---|
| **Project** | CargoWise – Logistics Route & Profit Optimizer |
| **Student** | Thapana Boora |
| **Course** | 23CSE211 – Design and Analysis of Algorithms |
| **Semester** | IV Semester · B.Tech. CSE-A |
| **University** | Amrita Vishwa Vidyapeetham, Nagercoil |

---

## 📖 References

1. Cormen et al. — *Introduction to Algorithms (CLRS)*, MIT Press
2. Kleinberg & Tardos — *Algorithm Design*, Pearson
3. GeeksforGeeks — Dijkstra's & 0/1 Knapsack tutorials
4. MDN Web Docs — HTML5 Canvas API

---

## 📄 License

This project is submitted as an academic mini project. Feel free to reference or learn from it.
