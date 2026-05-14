# ENMT484-Perception-Subsystem
ROS2 Perception subsystem for TurtleBot4 with OAK-D camera, April-Tag Detection, RViz, and Gazebo simulation

This repository contains perception subsystem development for the ENMT484 capstone project using a TurtleBot4 and ROS2 Jazzy.

#features implemented
-OAK-D camera integration
-ROS2 topic communication
-RViz visualization
-AprilTag detection using apriltag_ros
-Gazebo simulation testing
-intel RealSense camera testing for future regolith detection and depth sensing

#Sensors Roles
#OakD Camera
-detects AprilTags
-ROS2 Topic communication
-Localization testing
#Intel RealSense Camera
-Regolith detection testing
-depth sensing
-Camera verification
#Software used
-ROS2 Jazzy
-Turtlebot4 packages
-RViz2
-Gazebo
-apriltag_ros

#Important topics
-/oakd/rgb/preview/image_raw
-/oakd/rgb/preview/camera_info
-/detections

#Current status
AprilTag detection and ROS2 camera communication were successfully tested using the OAK-D camera and simulated turtlebot4 gazebo environment
Intel RealSense camera tested for future regolith perception
