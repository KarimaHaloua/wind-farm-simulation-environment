# wind-farm-simulation-environment
A wind farm simulation environment built with Blender, Gazebo Sim, PX4, and ROS2 Jazzy for UAV infrastructure inspection and robotics research.

![image alt](https://github.com/KarimaHaloua/wind-farm-simulation-environment/blob/main/images/Wind%20Farm.png?raw=true)

## Overview

This repository presents the development of a realistic wind farm simulation environment designed to support research on autonomous aerial inspection of wind turbines.

The environment integrates modern robotics and simulation tools to provide a configurable platform for testing UAV missions, evaluating perception systems, and generating multimodal sensor data under controlled conditions.

The project has been developed as part of an ongoing PhD research project focused on autonomous infrastructure inspection using aerial robots.


## Objectives

The main objectives of this simulation environment are:

Develop a realistic virtual wind farm for UAV inspection research.
Integrate a UAV simulation platform using PX4 and Gazebo Sim.
Support multimodal sensing through RGB, thermal, and LiDAR sensors.
Provide a reproducible environment for robotics experimentation.
Facilitate future research on autonomous infrastructure inspection.


## Simulation Environment

The virtual environment has been developed using Blender for 3D scene creation and Gazebo Sim for physics-based simulation.

The environment includes:

9 Wind turbines
Terrain
x500-fpv drone operating space
Physics simulation
Sensor simulation
Environmental visualization

The simulation is intended to reproduce realistic inspection scenarios while maintaining flexibility for future extensions.

## Software Stack

| Component | Technology |
|-----------|------------|
| 3D Modeling | Blender |
| Simulation Engine | Gazebo Sim |
| Robotics Middleware | ROS 2 Jazzy |
| Flight Controller | PX4 SITL |
| Visualization | RViz2 |
| Programming Languages | Python, C++ |

---

# UAV Platform

The simulated aerial platform is integrated with:

![image alt](https://github.com/KarimaHaloua/wind-farm-simulation-environment/blob/main/images/x500_vision%20drone.png?raw=true)

- x500_vision
- PX4 Software-In-The-Loop (SITL)
- ROS 2 Jazzy
- Gazebo Sim


---

# Simulation Gallery

The following screenshots illustrate different components of the simulation environment.

In Gazebo Sim :

![image alt](https://github.com/KarimaHaloua/wind-farm-simulation-environment/blob/main/images/Wind%20farm_x500-fpv_gazebo%20sim%20.png?raw=true)

In Rviz2 :

![image alt](https://github.com/KarimaHaloua/wind-farm-simulation-environment/blob/main/images/wind%20farm_lidar%20sensor_rviz2.png?raw=true)

## Research Context

This repository presents the simulation environment developed as part of an ongoing PhD research project on autonomous UAV inspection of wind energy infrastructure.

The simulation platform provides a flexible and reproducible environment for robotics experimentation and serves as the foundation for subsequent research activities.

# Copyright

© 2026 Karima Haloua. All rights reserved.

This repository documents research developed as part of an ongoing PhD project.

The documentation, figures, diagrams, and other materials contained in this repository are provided for academic and informational purposes only. They may not be copied, modified, redistributed, or used in other projects or publications without the prior written permission of the author.

For academic collaborations or further information, please contact the author.
