# truck_emergency_gazebo
This is gazebo simulation environment and turtlebot to test [truck emergency system](https://github.com/qwes98/truck_emergency)

# Before started
We have to export our package models' path
```
vim ~/.bashrc
export GAZEBO_MODEL_PATH=$HOME/catkin_ws/src/truck_emergency_gazebo/models:$GAZEBO_MODEL_PATH
source ~/.bashrc
```

# Dependency
- [turtlebot3_description](https://github.com/ROBOTIS-GIT/turtlebot3/tree/master/turtlebot3_description)

# Acknowledgement
Package's some codes come from turtlebot_gazebo package
