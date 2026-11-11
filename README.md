# 🕸️ Interactive Eulerian Graph Explorer & Simulator

An interactive, web-based educational platform designed to visualize, trace, and analyze **Eulerian Graphs**, **Eulerian Paths**, and **Eulerian Circuits**. Featuring an interactive graph sandbox, step-by-step traversal playback controls, real-time degree calculation, and a historical case study on the **Seven Bridges of Königsberg**.

🚀 **Live Demo:** [https://surajit-sahoo-iitian.github.io/Eulerian-Graph-Interactive-Visualization/](https://surajit-sahoo-iitian.github.io/Eulerian-Graph-Interactive-Visualization/)

---

## ✨ Features

- 📖 **Rigorous Mathematical Foundation**: Clear definitions of Euler's Theorems, degree conditions, paths vs. circuits, and formal graph notation.
- 🌉 **Historical Königsberg Case Study**: Visual breakdown of the famous 1736 Pregel River problem using historical maps and 4-vertex graph formulations.
- 🕹️ **Interactive Traversal Engine**:
  - Select your custom **Start Vertex** ($A, B, C, D\dots$).
  - Controls: **Play**, **Pause**, **Stop**, **Next Step**, **Previous Step**.
  - Attempted traversal playback for non-Eulerian graphs with interactive feedback (*"Oh no, I am stuck!"*).
- 🛠️ **Custom Sandbox**:
  - Add vertices and multigraph edges dynamically.
  - **Single Delete Mode**: Click to remove specific vertices or multi-edges seamlessly.
  - Real-time vertex degree calculator and Eulerian classification badge.
- 🎨 **Responsive UI**: Built with Tailwind CSS and HTML5 Canvas for smooth rendering.

---

## 📂 Repository Structure

```text
.
├── index.html                    # Main interactive web application
├── Bridges_of_Konigsberg.png     # Historical Pregel River map image
├── Konigsberg_formulation.jpg    # 4-Vertex / 7-Edge graph formulation diagram
└── README.md                     # Project documentation
