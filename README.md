# Map_My_World

This is a really interesting project.  For the first time, I implemented RTAB-Map and built a map of my simulated world in Gazebo.

You will need to rebuild on your system, so copy the /src folder and run catkin_make.

# Overview

In this project I created a 2D occumpancy grid and 3D octomap from a simulated environment (my house) using my own robot with the RTAB-Map package.

RTAB-Map (Real-Time Appearance-Based Mapping) is a popular solution for SLAM to develop robots that can map environments in 3D.  RTAB-Map has good speed and memory management, and it provides custom developed tools for information analysis.  Most importantly, the quality of the documentation on [ROS Wiki](https://wki.ros.org/rtabmap_ros) is very high.  Being able to leverage RTAB-Map with your own robots will lead to a solid foundation for mapping and localization.
