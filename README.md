# Robotics Intern Assignment

## Overview

This repository contains the solutions for the Robotics Intern Assignment. The tasks involve creating algorithms for 3D grid navigation, waypoint management using drones, and generating visualizations for the results. The project demonstrates expertise in path planning, real-time drone mission updates, and data visualization.

---

## Assignment Breakdown

### Task 1: 3D Grid Path Planning
1. **Description**:
   - Consider a 3D grid of points (0,0,0) to (100,100,100) with unit increments.
   - Assign random weights to some points, leaving others with zero weights.
   - The user inputs two or more sets of `{start, end}` points.

2. **Goals**:
   - Calculate the shortest path for each set such that no two paths share a common point at the same time.
   - Visualize the paths in 3D.

3. **Implementation**:
   - Used [Algorithm Name] (e.g., Dijkstra's or A*) for path planning.
   - Ensured non-overlapping paths using a time-based scheduling approach.
   - Visualized results using libraries such as Matplotlib/Plotly.

---

### Task 2: Drone Mission Planning
1. **Description**:
   - Created a dictionary of 15 waypoints with latitude, longitude, and altitude.
   - Planned a drone mission in auto mode using **DroneKit** or **Pymavlink**.

2. **Goals**:
   - Execute the mission with dynamic waypoint insertion after the 10th waypoint.
   - Print real-time estimates of time and distance to mission completion.
   - Visualize the drone’s path in 2D.

3. **Implementation**:
   - Managed waypoints dynamically to adapt the mission trajectory.
   - Calculated real-time telemetry data for mission status.
   - Used libraries like Matplotlib for 2D path visualization.

---

## Installation

### Prerequisites
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `dronekit`, `pymavlink`, `networkx`
- Other requirements can be installed using the provided `requirements.txt` file.

```bash
pip install -r requirements.txt
