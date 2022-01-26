# TFluna
TFluna working in ROS


**quick start commands create folder 'catkin_ws' **


$cd catkin_ws create folder 'src'，put the tfluna ROS package in back to folder /catkin_ws

$ catkin_make 
$ source devel/setup.bash 
$ sudo chmod 666 /dev/ttyUSB1 /*Notes: need to keep the same as the 'tfluna.launch'/ 
$ roslaunch tfluna_ros tfluna.launch

$ rostopic list 
$ rostopic echo /tfluna_ros_node/TFluna


**also can use 'rviz' to view**

$ rostopic list $rviz

Notes: Fixed frame Range Topic choose the 'TFluna'
