# 🚗 Automated Parking Path Planning Simulator

This project implements a **simulation-based low-speed automated parking system** using **A* path planning**. The system computes a collision-free path from a start position to a parking target in a constrained environment containing obstacles, and validates the solution through visualization.

The project focuses on **autonomous driving fundamentals** such as path planning, safety-aware navigation, and system-level validation.

---

## 🎯 Project Objective

- Design a low-speed automated parking planner
- Compute safe, collision-free trajectories in a parking environment
- Validate parking maneuvers using simulation and visualization

---

## 🧠 Key Concepts Used

- **A\* Path Planning** for global route computation  
- **Obstacle Handling** to avoid parked vehicles and boundaries  
- **Simulation-Based Validation** to visually verify planned paths  
- **Low-Speed Autonomous Driving Logic**

---

## 🛠️ Technologies Used

- Python  
- A\* Path Planning Algorithm  
- NumPy  
- Matplotlib  

---

## 📐 How It Works

1. The parking environment is modeled with obstacles representing parked vehicles.
2. A* computes a collision-free path from the start position to the parking target.
3. The planned path is validated through simulation and visualized on a 2D grid.
4. The resulting trajectory demonstrates safe low-speed parking behavior.

---

## 🎥 Demo Video

Below is a short demo of the **Automated Parking Path Planning Simulator**, showing collision-free parking trajectory generation using **A\*** path planning.

<video src="./DEMO.mp4" controls muted playsinline width="100%"></video>

---

## ▶️ How to Run

```bash
python main_autopark.py
