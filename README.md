[![](https://github.com/LKSeng/ros_noetic_2d_planning_demo/workflows/noetic_build/badge.svg?branch=main)](https://github.com/LKSeng/ros_noetic_2d_planning_demo/actions)

Author:
Menglong Zhu, menglong AT cis upenn edu

Updated by:
LKSeng

DESCRIPTION:
Path planning package. Two approaches are implemented in this package
1. uniform grid over map
2. quadtree decomposition over the map
Planning algorithm is A* search

video of quadtree decomposition:
http://www.youtube.com/watch?v=jqjlsIAQDT0

visualization use ROS markers in rviz

COMPILATION:
```shell
catkin build ros_noetic_2d_planning_demo
```

HOW TO RUN:
```shell
rosrun ros_noetic_2d_planning_demo run_planner ~/catkin_ws/src/ros_noetic_2d_planning_demo/maps/map0.txt
```
which generate intermediate text file for output.

NOTE:
This implementaion assume obstacles are all circles

