# ROS2 Differential Drive Robot

## 📌 Project Overview
This project demonstrates the development and simulation of a Differential Drive Robot using ROS2 and Gazebo.
The project focuses on robot modeling, simulation, motion control, sensor integration, SLAM-based mapping, and autonomous navigation using the Nav2 stack.

## 🎯 Project Objectives
- Create a robot model using URDF/SDF
- Simulate the robot in Gazebo environments
- Implement basic movement control using `cmd_vel`
- Design and modify custom Gazebo worlds
- Integrate sensors (e.g., LIDAR, camera)
- Generate a map using SLAM
- Implement autonomous navigation from Point A to Point B using Nav2

## 📂 Repository Structure
The repository contains the following ROS2 packages:
- **my_robot_description** – Robot model files (URDF) and RViz configurations
- **my_robot_controller** – ROS2 nodes responsible for robot movement control
- **my_robot_bringup** – Launch files to start simulation and required nodes

## ⚠ Important Note
The ROS2 packages are uploaded as ZIP files:
- `my_robot_description.zip`
- `my_robot_controller.zip`
- `my_robot_bringup.zip`

To use the project:
1. Download the ZIP files
2. Extract them inside a ROS2 workspace under the `src/` directory (inside your workspace folder)
3. Build the workspace
4. Launch the simulation using the appropriate launch file

## 🧠 Technologies Used
- ROS2
- Gazebo
- RViz
- URDF 
- SLAM
- Nav2 Stack

## 📊 Project Outcomes
- Developed a complete Differential Drive Robot model using URDF
- Simulated the robot in custom Gazebo environments with obstacles
- Implemented a movement control node using ROS2 and `cmd_vel`
- Integrated sensors for environment perception
- Generated a map using SLAM
- Achieved autonomous navigation using the Nav2 stack
- 
## Robot Overview
![Differential Drive Robot](images/Differential_Drive_Robot.jpeg)  

## Sensors
![LIDAR Sensor](images/LIidar.png)  

## MIT License
