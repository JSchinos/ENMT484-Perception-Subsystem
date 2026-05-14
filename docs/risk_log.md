#Perception Subsystem Risk log

RISKS:
OAK-D camera not publishing ROS2 topics
Turtlebot4 battery depletion during testing
AprilTag detection instability
ROS2 communication issues

IMPACTS:
Prevents AprilTag detection and perception testing
Camera and ROS2 nodes stop functioning during testing
Inconsistent localization and perception outputs
Delays subsystem integration and testing

MITIGATIONS:
Troubleshot ROS2 bringup, verified camera connections, and tested topic publication through RViz
Kept Turtlebot4 Docked between testing and monitored battery
Tuned apriltag configuration
