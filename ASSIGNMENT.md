# Robotics Intern Assignment

## Task Details

### Task 1: 3D Grid Path Planning
1. **Grid Setup**:
   - Create a 3D grid of points ranging from `(0,0,0)` to `(100,100,100)` with unit increments along all axes.
   - Randomly assign higher weights to some points, leaving others with zero weights.

2. **User Input**:
   - Accept two or more sets of `{start, end}` points from the user.

3. **Objective**:
   - Compute the shortest path for each set such that no two paths share a common point at the same time.
   - Visualize the paths in a 3D plot.

---

### Task 2: Drone Mission Planning
1. **Waypoints**:
   - Create a dictionary of 15 waypoints with keys `'lat'`, `'lon'`, and `'alt'`.

2. **Mission Planning**:
   - Use **DroneKit** or **Pymavlink** to plan a quadcopter mission in auto mode.
   - Include a dynamic waypoint after the 10th waypoint at 100m perpendicular to the current direction.

3. **Real-Time Feedback**:
   - Print the estimated time and distance to complete the mission at every instance.

4. **Visualization**:
   - Plot the drone's path in 2D.

---

## Submission Requirements

1. **Documentation**:
   - Provide detailed documentation of your algorithms and their implementation.
   - Include a clear explanation of your approach.

2. **Results**:
   - Add results with visualizations of feature matches or graphs.
   - Ensure paths and missions are correctly plotted.

3. **GitHub Repository**:
   - Write a detailed README file.
   - Make the repository private and share it with:
     - rajeshree@vecros.com
     - prime@vecros.com

---

## Deliverables
- Source code for both tasks.
- Visualizations of 3D paths and 2D drone paths.
- Documentation and results in the `/docs` and `/results` directories.
- Private GitHub repository link shared via email.

---

## Tools and Libraries
- **Python Libraries**:
  - `numpy`, `matplotlib`, `networkx`, `dronekit`, `pymavlink`
- **Visualization Tools**:
  - Matplotlib or Plotly for 3D and 2D plots.

---

### Notes:
1. Ensure all scripts are well-documented with comments.
2. Follow best practices for code readability and modularity.
3. Test your implementation thoroughly before submission.

---

Let me know if you need further edits or a different format!
