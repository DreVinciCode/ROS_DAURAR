# DAURAR (Dual-Arm-Universal-Robot5-Augmented-Reality)
### This repo is the ROS component for the DAURAR project for the Dual-Arm UR5 manipulators in the MuLIP lab at Tufts University. [Unity_DAURAR](https://github.com/DreVinciCode/Unity_DAURAR) is the Unity component.

![Alt text](demos/daurar.png)

## Requirements
1. Ubuntu 18.04
2. ROS Melodic
3. Gazebo

## Installation 

```
cd ~/catkin_ws/src
git clone https://github.com/DreVinciCode/ROS_DAURAR.git
git clone https://github.com/DreVinciCode/universal_robot.git
git clone https://github.com/DreVinciCode/Universal_Robots_ROS_Driver.git
git clone https://github.com/DreVinciCode/robotiq_85_gripper.git 

cd ..
rosdep install --from-paths src --ignore-src -r -y

```

## How to Run

```
roslaunch daurar_launch daurar_dual_robot_gazebo_moveit.launch
```
