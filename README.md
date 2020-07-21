# Differential Robot with ROS
This repo is to demo the building of a differential robot drive, with ROS and Gazebo as a simulation environment.

The following main tasks are included:
- Building and spawning the Robot+Sensors model in Gazebo + RViz + keyboard teleop.
- Demo move_base control in simulation.
- Replace LiDAR (Hukoyo) with some ULS.
- ROS on Rasperry Pi or Arduino.
- Building the HW robot: Mobile platform (2 DC motors + 2-channels H-bridge driver) + Controller (Pi or Arduino) + ULS sensor + Servo for sensor scanning.
- Integration of HW sensors and actuators drivers in ROS (publisher-subscriber).
