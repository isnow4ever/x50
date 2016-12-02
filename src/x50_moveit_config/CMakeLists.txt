cmake_minimum_required(VERSION 2.8.3)
project(x50_moveit_config)

#############
## packages #
#############
find_package(catkin REQUIRED)

#############
##  catkin  #
#############
catkin_package()

#############
## Install ##
#############
install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY config DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
