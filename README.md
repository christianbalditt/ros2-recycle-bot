# ROS 2 Recycle Bot

Autonomous recycling robot simulation using ROS 2 and Gazebo.

## Goal

Develop a mobile robot that can detect recyclable objects such as cans and water bottles, navigate toward them, pick them up with a gripper, and transport them to a recycling location.

## Features

- Differential-drive mobile robot
- LiDAR navigation
- Nav2 autonomous navigation
- Bottle and can detection
- Camera-based perception
- Mechanical gripper
- Bin-full detection
- Gazebo simulation

## Software

- Ubuntu 24.04
- ROS 2
- Gazebo
- Nav2
- RViz
- Python
- YOLO / OpenCV

## Team

- Person 1: Robot platform, LiDAR, and navigation
- Person 2: Cameras, object detection, and gripper
- Both: Integration and testing

## Project Structure

```text
src/
  recycle_bot_description/
  recycle_bot_navigation/
  recycle_bot_perception/
  recycle_bot_gripper/
  recycle_bot_bringup/
worlds/
models/
```

## Target Completion

November 20, 2026
