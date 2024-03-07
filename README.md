### Udacity Robotics Software Engineering Course
Using RTAB-Map (Real-Time Appearance-Based Mapping) to perform SLAM
```
cd src
git clone https://github.com/ros-teleop/teleop_twist_keyboard.git
```
```
roslaunch my_robot world.launch
roslaunch my_robot amcl.launch
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```
