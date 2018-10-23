cmake_minimum_required(VERSION 2.8.3)
project(ropod_teleop)

find_package(catkin REQUIRED COMPONENTS
  roslint
  rospy
  geometry_msgs
  sensor_msgs
)

roslint_python()
catkin_python_setup()

catkin_package()

include_directories(
  ${catkin_INCLUDE_DIRS}
)

install(PROGRAMS
  ros/scripts/joy
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}/scripts
)

install(DIRECTORY ros/launch/
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
)
