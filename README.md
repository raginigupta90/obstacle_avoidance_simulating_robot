# obstacle_avoidance_simulating_robotTitle:
Simulated Autonomous Robot with Real-Time Obstacle Avoidance

Description:
This project explores the development of a simulated autonomous robot capable of real-time obstacle avoidance using ultrasonic sensors. Implemented in Python with the Pygame library for graphics and NumPy for computations, this project demonstrates essential techniques in autonomous robotics.

Features:
Real-Time Obstacle Detection: Utilizes ultrasonic sensors to detect obstacles and create a point cloud representing the environment.
Obstacle Avoidance Algorithms: Implements algorithms for the robot to adjust its path and avoid collisions based on sensor data.

Kinematic Model: Simulates the robot's movement using differential drive dynamics for precise maneuvers.


Visual Representation: Graphical interface to visualize the robot's movements, sensor data, and obstacles in real-time using Pygame.
Project Structure:
Robot.py:

Robot Class: Handles initialization, obstacle avoidance, and kinematics.
Graphics Class: Manages drawing the robot and visualizing sensor data.
Ultrasonic Class: Simulates obstacle sensing using ultrasonic sensors.


main.py:

Initializes the simulation environment.
Contains the main loop for handling events, updating kinematics, sensing obstacles, and updating graphics.
