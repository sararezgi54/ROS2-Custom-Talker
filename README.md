# ros2-custom-talker

## Description
A custom ROS 2 publisher node built with rclpy that publishes personalized messages on the 'chatter' topic — extending the standard demo_nodes_py talker/listener example.

## README.md

# ROS 2 Custom Talker Node

A simple custom ROS 2 publisher (talker) node written in Python using `rclpy`. 
This node publishes a custom message on the `chatter` topic every second, 
and can be paired with the standard ROS 2 `listener` node to demonstrate 
the Publisher/Subscriber communication pattern.

## Features
- Custom Python ROS 2 package (`my_talker`)
- Publishes personalized messages instead of the default "Hello World"
- Compatible with the standard `demo_nodes_py` listener node

## Requirements
- Ubuntu 22.04
- ROS 2 Humble
- Python 3

## Installation & Usage

1. Clone this repository into your ROS 2 workspace:
   cd ~/ros2_ws/src
   git clone <your-repo-url>

2. Build the workspace:
   cd ~/ros2_ws
   colcon build
   source install/setup.bash

3. Run the talker node:
   ros2 run my_talker talker

4. In a new terminal, run the listener node to receive messages:
   ros2 run demo_nodes_py listener

## Author
Sara
