+**Previously:**

* Read the three thesis. 

* First one focused on use of classification, regression network to control the robot. 

* Second one focused on use of deep learning to control the robot in real time. 

* Third one used reinforcement learning for visual control in robot car in simulation. 

* Installed the DL libraries, ROS2 on fresh PC

**Meeting outcomes:**

* reproduce the setup (follow line) to ROS2 + (gazebo/ignition) for collecting the dataset for work ahead in ros2bags

* ROS2bag - mainly images+ speed(translational + rotational) required 


Reading references:

1. Gazebo vs Ignition [Gazebo vs Ignition](https://allisonthackston.com/articles/ignition-vs-gazebo.html#:~:text=Both%20Ignition%20and%20Gazebo%20calculate,like%20they%20are%20in%20Ignition.)


**Progress:**

1. Migration to ROS2 in progress, currently launcing robot with gazebo part left. Instead of using  robot models from jderobot package, this time they have to be loaded directly from custom robots. Launch.py file has to be modified accordingly. 


