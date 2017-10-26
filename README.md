# PhantomX Pincher arm under ROS indigo 
<p align="center">
<img src="https://github.com/NathanCrombez/PhantomXPincherArmROS/blob/master/images/pincher.jpg" align ="middle" width="60%" height="60%" title="header">
</p>

## Packages installation 

__Arbotix__:
ArbotiX ROS drivers to interface with the ArbotiX board.
Installation from source:

	cd ~/ros/indigo/catkin_ws/src
	git clone https://github.com/NathanCrombez/arbotix_ros
	cd .. && catkin_make


__Turtlebot Arm__:
The turtlebot_arm package provides bringup, description, and utilities for using the turtlebot arm. 
The Kinetic version provides code for the PhantomX Pincher. The Kinectic version works with ROS Indigo except "turtlebot_arm_object_manipulation" and "turtlebot_arm_block_manipulation".
Installation from source:

	cd ~/ros/indigo/catkin_ws/src
	git clone  https://github.com/NathanCrombez/turtlebot_arm
	cd .. && catkin_make

	

	
