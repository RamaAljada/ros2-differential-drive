# ROS2 Differential Drive Robot

## 📌 Project Overview
This project demonstrates the development and simulation of a Differential Drive Robot using ROS2 and Gazebo.
The project focuses on robot modeling, simulation, motion control, sensor integration, SLAM-based mapping, and autonomous navigation using the Nav2 stack.

## 🎯 Project Objectives
- Create a robot model using URDF
- Simulate the robot in Gazebo environments
- Implement basic movement control using `cmd_vel`
- Design and modify custom Gazebo worlds
- Integrate sensors LIDAR
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
1. Create a ROS 2 workspace (if you don't have one yet)
   ```bash
   mkdir -p ~/ros2_ws/src
   cd ~/ros2_ws/src
2. Download the following files from the repository:
   - `my_robot_description.zip`
   - `my_robot_controller.zip`
   - `my_robot_bringup.zip`
   Then extract them into the src/ folder:
   unzip my_robot_description.zip -d my_robot_description
   unzip my_robot_controller.zip   -d my_robot_controller
   unzip my_robot_bringup.zip      -d my_robot_bringup
3. Build the workspace
   cd ~/ros2_ws
   colcon build --symlink-install
4. Source the workspace
   source install/setup.bash
5. Launch the simulation:
   ros2 launch my_robot_bringup robot_simulation.launch.py

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
## Robot in Gazebo Environment
![Differential Drive Robot](images/Differential_Drive_Robot.jpeg)  

## LIDAR Scanning the Surroundings
![LIDAR Sensor](images/LIidar.png)  

## MIT License
