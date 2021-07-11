# 

 **install the package**

`$ cd catkin_ws/src`

`$ git clone https://github.com/devanshdhrafani/diff_drive_bot.git`

`$ cd ..`

`$ catkin_make`

# 

**install the dependencies :**

`$ sudo apt-get install ros-melodic-dwa-local-planner`

`$ sudo apt-get install ros-melodic-joy`

# 


**Load the robot in the Gazebo :**

`$ roslaunch diff_drive_bot gazebo.launch`


![](https://b.top4top.io/p_2018ua4ye1.png)
# 

**start rviz :**

`$ roslaunch diff_drive_bot gmapping.launch`

![](https://d.top4top.io/p_201820tvd1.png)

# 

**create the map :**

`$ rosrun diff_drive_bot keyboard_teleop.py`

![](https://k.top4top.io/p_2018l9q901.png)

# 

**save the map by :**

`$ rosrun map_server map_saver -f ~/test_map1`

![](https://d.top4top.io/p_2018eva2m1.png)
