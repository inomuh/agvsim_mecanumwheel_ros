# agvsim_mecanumwheel_ros

First download agvsim_v2_ros metapackage

sudo apt-get install ros-kinetic-navigation

sudo apt-get install ros-kinetic-gmapping

sudo apt-get install ros-kinetic-timed-roslaunch

sudo apt-get install ros-kinetic-dynamic-reconfigure

sudo apt-get install ros-kinetic-smach-viewer



gedit ~/.bashrc

export GAZEBO_MODEL_PATH=~/<WORKSPACE_NAME>/src/agvsim_v2_ros/building_editor_models:~/<WORKSPACE_NAME>/src/agvsim_v2_ros/model_editor_models:$GAZEBO_MODEL_PATH



cd <WORKSPACE_NAME>

catkin_make

catkin_make install

$ roslaunch agvsim_mecanumwheel_start start_agv.launch
