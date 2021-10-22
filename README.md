# moveit_ros_occupancy_map_monitor

参考：

http://docs.ros.org/en/melodic/api/moveit_tutorials/html/doc/perception_pipeline/perception_pipeline_tutorial.html

https://github.com/ros-planning/moveit/tree/melodic-devel/moveit_ros/occupancy_map_monitor

说明：move it 的Octomap插件

**安装：**

$ cd catkin_ws/src/

$ git clone https://github.com/AIRS-TJ/moveit_ros_occupancy_map_monitor.git

$ cd ..

$ catkin_make

**运行：**

$ roslaunch moveit_ros_occupancy_map_monitor test.launch

(当前无法使用)

**直接调用octomap_server的方法：**

$ sudo apt-get install ros-melodic-octomap-ros 

$ sudo apt-get install ros-melodic-octomap-msgs 

$ sudo apt-get install ros-melodic-octomap-server

$ sudo apt-get install ros-melodic-octomap-rviz-plugins

$ roslaunch moveit_ros_occupancy_map_monitor octomap_server.launch
