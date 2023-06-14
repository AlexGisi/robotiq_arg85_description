cmake_minimum_required(VERSION 3.16)
project(robotiq_arg85_description)

## Find catkin macros and libraries
find_package(ament_cmake REQUIRED)

#############
## Install ##
#############

install(
  DIRECTORY launch meshes robots
  DESTINATION share/${PROJECT_NAME}/
)

install(FILES urdf.rviz
  DESTINATION share/${PROJECT_NAME}/
)

ament_package()
