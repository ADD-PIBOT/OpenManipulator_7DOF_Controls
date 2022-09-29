# OpenMANIPULATOR-7DOF Controls 
<!-- [![Build Status](https://travis-ci.org/ROBOTIS-GIT/open_manipulator_p_controls.svg?branch=master)](https://travis-ci.org/ROBOTIS-GIT/open_manipulator_p_controls) -->

## Dependencies
sudo apt-get install ros-<YOUR_ROS_DISTRO>-dynamixel-workbench-toolbox*

## How to Run
```bash
(MoveGroup + JointTrajectoryController)
(w/o gripper)
# Gazebo Simulation
$ roslaunch open_manipulator_7dof_controllers joint_trajectory_controller.launch

# Real Robot
$ roslaunch open_manipulator_7dof_controllers joint_trajectory_controller.launch sim:=false


# Haven't been tested yet.
# (GravityCompensationController)
# Gazebo Simulation
# Set trasmission to effort and motor mode to current first
# $ roslaunch open_manipulator_p_controllers gravity_compensation_controller.launch

# Real Robot
# $ roslaunch open_manipulator_p_controllers gravity_compensation_controller.launch sim:=false
```
