# Task-3-
Here are all the commands needed to complete this task: 

$ sudo apt-get install ros-melodic-hector-trajectory-server ros-melodic-slam-gmapping ros-melodic-navigation

then bulit the map and robot using this command >> $ cd ~/catkin_ws/src 

 $ git clone https://github.com/wh200720041/warehouse_navigation.git
 
 $ cd .. 
 
 $ catkin_make 
 
 $ source ~/catkin_ws/devel/setup.bash 
 
 $ roslaunch warehouse_simulation warehouse_simulation.launch 
 
 $ rosrun map_server map_saver -f ~/map
 
last command to save it.
