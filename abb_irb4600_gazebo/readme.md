# ABB IRB 4600 Gazebo

##Overview

This package contains the files required to simulate the ABB IRB 4600  manipulator (and variants) in Gazebo. 

Current version supports ROS Melodic.

It was modified from the gazebo package for the ABB IRB 120 found in the [abb experimental](https://wiki.ros.org/abb_experimental) package.


## Using Moveit! with Gazebo Simulator

1. Bring the robot model into gazebo and load the ros_control controllers:
   ```roslaunch abb_irb4600_gazebo irb4600_3_58_gazebo.launch``` 

2. Launch moveit! and ensure that it is configured to run alongside Gazebo:
```roslaunch abb_irb4600_moveit_config moveit_planning_execution_gazebo.launch``` 
