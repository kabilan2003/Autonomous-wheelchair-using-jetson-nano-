# Autonomous Wheelchair using NVIDIA Jetson Nano

![autonomous wheelchair for physically disabled](https://github.com/kabilan2003/Autonomous-wheelchair-using-jetson-nano-/assets/109456728/2736da3b-7f93-4251-8bdf-14c2634a4d44)

# Autonomous Wheelchair 


Welcome to the Autonomous Wheelchair project using NVIDIA Jetson Nano! This project aims to develop an intelligent and autonomous wheelchair using the powerful NVIDIA Jetson Nano platform. The goal is to enhance the mobility and independence of users with mobility impairments by enabling the wheelchair to navigate and avoid obstacles autonomously.

# Table of contents 

1. Introduction
2. Features
3. Hardware Requirements
4. Software Requirements
5. Installation
6. Usage
7. Contributing
8. License

# Introduction
The Autonomous Wheelchair project leverages the NVIDIA Jetson Nano, a high-performance, low-power AI platform, to process sensor data, perform real-time object detection, and make intelligent decisions for autonomous navigation. The project integrates a range of sensors, including depth sensors, LiDAR, and cameras, to perceive the environment and provide accurate obstacle detection and avoidance capabilities.

The wheelchair's autonomous navigation system is built upon a combination of perception, path planning, and control algorithms. Deep Learning models are employed for object recognition and localization, allowing the wheelchair to detect obstacles and create a dynamic map of the surrounding environment.

The wheelchair's autonomous navigation system is built upon a combination of perception, path planning, and control algorithms. Deep Learning models are employed for object recognition and localization, allowing the wheelchair to detect obstacles and create a dynamic map of the surrounding environment.

# Features

    1.Real-time obstacle detection and avoidance using deep learning models.
    2.Integration of multiple sensors for robust environmental perception.
    3.Dynamic mapping and path planning algorithms for smooth navigation.
    4.User-friendly interface for manual and autonomous control modes.
    5.Extensible architecture, allowing for easy integration of additional features.

# Hardware Requirements
1. NVIDIA Jetson Nano Developer Kit
2. Depth Sensors (e.g., Intel RealSense Depth Camera)
3. RPLidar sensor
4. Cameras (e.g., USB webcams)
5. Motorized Wheelchair
6. Power Supply for Jetson Nano and other components

# Software Requirements
1. NVIDIA Jetson Nano Developer Kit with ubuntu 20.04
2. ROS (Robot Operating System) noetic
3. Python 3
4. OpenCV
5. yplo object detection

# Installation
1.ubuntu 20.04 - https://github.com/Qengineering/Jetson-Nano-Ubuntu-20-image

2.ros- http://wiki.ros.org/noetic/Installation/Ubuntu

3.ros navigation stack - https://github.com/kabilan2003/navigation_stack.git

4.yolo object detection for ros - https://github.com/leggedrobotics/darknet_ros.git

# working model 

![WhatsApp Image 2023-07-31 at 9 26 19 PM](https://github.com/kabilan2003/navigation_stack/assets/109456728/d93806b2-2dca-43e1-a40d-83de2a9f35fd)

# isaac ros simulation for wheelchair in hospital environment 

![WhatsApp Image 2023-07-31 at 9 28 15 PM](https://github.com/kabilan2003/navigation_stack/assets/109456728/9e29ef4e-07ce-4ec0-bdf9-c6ff70239f03)

Welcome to the ISAAC ROS Omniverse Simulation with Hospital Environment for Wheelchair project! This simulation aims to create a realistic and dynamic hospital environment in NVIDIA Omniverse to test and validate the performance of an autonomous wheelchair. The project integrates the ISAAC ROS stack and NVIDIA Omniverse platform to simulate a virtual hospital setting where the wheelchair can navigate autonomously and safely.

github - https://github.com/kabilan2003/isaac_ros.git


# Ros gazebo simulation 

![Screenshot from 2023-07-31 21-33-56](https://github.com/kabilan2003/navigation_stack/assets/109456728/c008f7f0-fc0a-42ee-8da9-96c7327c00f1)

Welcome to the Gazebo Simulation for Wheelchair project! This simulation aims to create a realistic and dynamic virtual environment using Gazebo to test and develop autonomous wheelchair control algorithms. The project integrates a wheelchair model and various sensors into the Gazebo simulation environment to enable accurate perception and navigation testing.

Gi

# Hardware architecture

![WhatsApp Image 2023-07-31 at 9 42 12 PM](https://github.com/kabilan2003/navigation_stack/assets/109456728/824d9dda-f825-42f0-a677-ab68a82b092a)

This document outlines the hardware architecture for a project that combines the NVIDIA Jetson Nano, Arduino, Webcam, and RPLIDAR sensor. The goal of this architecture is to create an intelligent robotic system capable of real-time perception, navigation, and environment mapping.

# Hardware Components

1. NVIDIA Jetson Nano: The Jetson Nano serves as the main processing unit and runs sophisticated AI algorithms for perception, object detection, and path planning. Its GPU capabilities enable fast and efficient deep learning computations.

2. NVIDIA Jetson Nano: The Jetson Nano serves as the main processing unit and runs sophisticated AI algorithms for perception, object detection, and path planning. Its GPU capabilities enable fast and efficient deep learning computations.

3. Webcam: The webcam is used for visual perception and object detection. It captures real-time video feed, which is then processed by the Jetson Nano to identify and track objects in the environment.

4. RPLIDAR Sensor: The RPLIDAR sensor is a 360-degree laser scanner that provides high-resolution 2D maps of the surrounding environment. It allows the robot to perceive obstacles and plan collision-free paths.

# Hardware Workflow

1. Sensor Data Acquisition: The webcam captures real-time video, and the RPLIDAR scans the environment to collect point cloud data.
2. Object Detection: The Jetson Nano processes the video feed from the webcam using deep learning-based computer vision models to detect and recognize objects of interest in the environment.
3. Obstacle Perception: The Jetson Nano analyzes the point cloud data from the RPLIDAR to identify obstacles and generate a 2D map of the surroundings.
4. Path Planning and Navigation: Based on the object detection and obstacle perception results, the Jetson Nano plans collision-free paths and sends control commands to the Arduino to navigate the robot safely.
5. Motor Control and Actuation: The Arduino receives control commands from the Jetson Nano and actuates the motors to execute the planned navigation and physical actions.
6. Feedback and Localization: The robot's sensors, such as encoders and IMU, provide feedback to the Arduino and Jetson Nano for accurate localization and position updates during navigation.

# Conclusion

The hardware architecture combining NVIDIA Jetson Nano, Arduino, Webcam, and RPLIDAR enables the creation of a versatile and intelligent robotic system capable of real-time perception, navigation, and environment mapping. The powerful AI capabilities of the Jetson Nano, along with the Arduino's control and actuation abilities, form a robust foundation for building advanced robotics applications. This architecture can be expanded and customized for various robotic projects, such as autonomous vehicles, surveillance robots, or mapping drones.


# License 

This project is licensed under the MIT License - see the LICENSE file for details.

Thank you for your interest in our Autonomous Wheelchair project! We hope this project inspires you to contribute to the field of assistive robotics and make a positive impact on the lives of people with mobility challenges. If you have any questions or suggestions, feel free to contact us or open an issue on GitHub. 












 






   












