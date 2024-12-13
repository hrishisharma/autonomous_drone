# Drone Project

Welcome to the Drone Project repository! This project includes the necessary setup and files to work with a drone using ROS2, including URDF modeling.

---

## Features
- URDF model of the drone
- ROS2 package setup
- Basic functionality for simulation and navigation

---

## Prerequisites

Before getting started, make sure you have:

- A system with ROS2 installed (recommended version: Humble or higher).
- Python 3.8 or later.
- Necessary dependencies for building and running URDF models.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/drone_project.git
   cd drone_project
   ```

2. Install required dependencies:
   ```bash
   sudo apt update
   sudo apt install -y python3-colcon-common-extensions ros-humble-desktop
   ```

3. Set up the URDF files:

   Run the included shell script to configure the URDF model:
   ```bash
   chmod +x urdf.sh
   ./urdf.sh
   ```
https://github.com/hrishisharma/autonomous_drone/blob/main/image1.jpeg

