# ROS2 SLAM Mapping using TurtleBot3

<p align="center">

![ROS2](https://img.shields.io/badge/ROS2-Humble-blue)

![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-orange)

![RViz2](https://img.shields.io/badge/RViz2-Visualization-green)

![SLAM](https://img.shields.io/badge/SLAM-SLAMToolbox-success)

</p>

---

# Overview

This project demonstrates the implementation of Simultaneous Localization and Mapping (SLAM) using ROS2 Humble, TurtleBot3 Burger, RViz2 and SLAM Toolbox.

The objective is to enable autonomous robots to build occupancy grid maps while estimating their own pose within an unknown environment.

This project explores robotics middleware concepts, sensor integration, coordinate transformations and map visualization.

---

# System Architecture

LiDAR

↓

/scan

↓

SLAM Toolbox

↓

Occupancy Grid Generation

↓

/map

↓

RViz2

↓

Map Visualization

---

# Features

✔ ROS2 Humble Environment

✔ TurtleBot3 Burger Integration

✔ SLAM Toolbox

✔ Occupancy Grid Mapping

✔ RViz2 Visualization

✔ TF Tree Management

✔ Navigation2 Support

✔ LiDAR Data Processing

✔ Ubuntu 22.04 Support

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| ROS2 Humble | Robotics Middleware |
| Ubuntu 22.04 | Operating System |
| TurtleBot3 | Mobile Robot Platform |
| RViz2 | Visualization |
| SLAM Toolbox | Mapping |
| Navigation2 | Navigation |
| Gazebo | Simulation |
| WSL2 | Development Environment |

---

# ROS Topics

```bash
/scan

/map

/tf

/tf_static

/odom

/cmd_vel
```

---

# TF Tree

```text
map

↓

odom

↓

base_link

↓

base_scan
```

---

# Installation

### Update Ubuntu

```bash
sudo apt update

sudo apt upgrade -y
```

### Install ROS2

```bash
sudo apt install ros-humble-desktop -y
```

### Install SLAM Packages

```bash
sudo apt install ros-humble-slam-toolbox -y

sudo apt install ros-humble-navigation2 -y

sudo apt install ros-humble-nav2-bringup -y
```

### Install TurtleBot3

```bash
sudo apt install ros-humble-turtlebot3* -y
```

### Configure Robot

```bash
echo "export TURTLEBOT3_MODEL=burger" >> ~/.bashrc

source ~/.bashrc
```

---

# RViz2

```bash
rviz2
```

---

# SLAM Toolbox

```bash
ros2 launch slam_toolbox online_async_launch.py
```

---

# Skills Learned

- ROS2 Fundamentals
- Robotics Middleware
- Topics and Nodes
- Publisher Subscriber Architecture
- SLAM Concepts
- Occupancy Grid Mapping
- TF Tree Transformations
- RViz2 Visualization
- TurtleBot3 Integration
- Navigation2 Basics
- Ubuntu Environment Setup
- WSL2 Robotics Development

---

# Future Improvements

- Gazebo Integration
- Real Robot Deployment
- Autonomous Navigation
- Path Planning
- Sensor Fusion
- Camera Based SLAM
- Drone SLAM

---

# Screenshots

### RViz2

(Add Screenshot Here)

---

### System Architecture

(Add Architecture Image Here)

---

### Occupancy Grid Map

(Add Map Image Here)

---

# Resume Description

Developed a ROS2-based SLAM environment using TurtleBot3, SLAM Toolbox, Navigation2 and RViz2 for occupancy grid generation, robot localization and real-time visualization.

---

# Author

### Jeet Chalthanwala

MSc IT

Robotics Enthusiast

ROS2 Developer
