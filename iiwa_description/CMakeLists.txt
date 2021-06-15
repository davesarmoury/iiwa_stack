cmake_minimum_required(VERSION 3.5)
project(iiwa_description)

find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY meshes urdf launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
