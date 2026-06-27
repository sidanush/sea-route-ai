# 🚢 Sea Route AI — Autonomous Ship Navigation System

An AI-powered maritime navigation system that combines Model Predictive Control (MPC) 
with intelligent pathfinding to simulate autonomous ship navigation in real-world 
coastal environments.

## 🌟 Key Features
- Multiple pathfinding algorithms: Dijkstra, A*, D* and more
- COLREG-compliant collision avoidance (international maritime regulations)
- Real-time dynamic obstacle detection and avoidance
- High-resolution coastal mapping using GSHHG geographic data
- 3-DOF kinematic ship modelling (surge, sway, yaw)
- Interactive MATLAB-based simulation with live visualization

## 🛠️ Tech Stack
- MATLAB (Simulation & Visualization)
- Model Predictive Control (MPC)
- GSHHG Geographic Database
- Kinematic Ship Modelling

## 🧠 How It Works
1. Loads real coastal map data to model shorelines as static obstacles
2. User defines origin & destination waypoints
3. Global path planner generates optimal collision-free route
4. MPC controller tracks trajectory in real-time
5. System detects dynamic vessels and executes COLREG-compliant manoeuvres
6. Fan-shaped candidate trajectories evaluated for safety & feasibility

## 📊 Algorithms Implemented
| Algorithm | Use Case |
|-----------|----------|
| Dijkstra | Shortest path on weighted graph |
| A* | Heuristic-based optimal pathfinding |
| D* | Dynamic replanning for changing environments |
| MPC | Real-time trajectory tracking & control |

## 👥 Contributors
- Siddiqui Mohammed Anush
- Tabish Syed

## 📄 Research Report
Full technical report available in the repository.
