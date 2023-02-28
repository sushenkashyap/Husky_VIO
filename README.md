# Husky_VIO
Husky Gazebo Simulator for Visual Inertial Odometry

Based on Husky robot by Clearpath Robotics: https://github.com/husky/husky

To spawn Husky simulation:
```
#!command

roslaunch husky_vio arena_husky_gazebo.launch
```

To move Husky:
```
#!command

rosrun key_teleop key_teleop.py key_vel:=cmd_vel
```