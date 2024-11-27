ROS2 Humble test for a 6 wheels robot

Personal Comments: This repository was created to enhance and update my knowledge of the latest features and structures in ROS2 and Gazebo. It also serves as a platform to apply what I’ve learned over the past few years.

# Robot code Compilation
Compile the code via ros2 command before anything. 
```
colcon build --symlink-install
source install/setup.bash
```

# RVIZ Visualization
To visualize the robot in Rviz
```
ros2 launch robot_description display.launch.py
```

# Running Gazebo and RVIZ
```
ros2 launch robot_bringup gazebo.launch.xml
```