cmake_minimum_required(VERSION 3.5)
project(pal_gripper_controller_configuration)

find_package(ament_cmake_auto REQUIRED)

# better way to do this?
# install(PROGRAMS scripts/home_gripper.py
#   DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})

ament_auto_package(INSTALL_TO_SHARE config launch)

