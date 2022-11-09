# GoChaseIt

## Introduction

Project made in the robotics engineering nano degree of Udacity
.This project is a robot chasing a white ball in a simulated environment.

## Build

```
cd /catkin_ws/
catkin_make
```

## Launch

### Terminal 1
```
cd /catkin_ws/
. devel/setup.bash
roslaunch my_robot world.launch
```

### Terminal 2
```
cd /catkin_ws/
. devel/setup.bash
roslaunch ball_chaser ball_chaser.launch
```

### Terminal 3

This one is optional and offer a dedicated window of the mounted camera of the robot
```
cd /catkin_ws/
. devel/setup.bash
rosrun rqt_image_view rqt_image_view
```

## RViz config

In case you're looking for a default setup for this project you will find the configuration inside the "rviz" folder. 