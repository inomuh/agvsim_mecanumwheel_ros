cmake_minimum_required(VERSION 2.8.3)
project(agvmecanumwheel_navigation)


find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  std_msgs
  sensor_msgs
)


catkin_package(
)


include_directories(
  ${catkin_INCLUDE_DIRS}
)


add_executable(agvmecanumwheel_initial_pose src/agvmecanumwheel_initial_pose.cpp)
target_link_libraries(agvmecanumwheel_initial_pose ${catkin_LIBRARIES})
