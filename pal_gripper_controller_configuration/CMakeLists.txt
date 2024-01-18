cmake_minimum_required(VERSION 3.8)
project(pal_gripper_controller_configuration)

find_package(ament_cmake_auto REQUIRED)

# better way to do this?
# install(PROGRAMS scripts/home_gripper.py
#   DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})

if(BUILD_TESTING)
  find_package(ament_lint_auto REQUIRED)
  ament_lint_auto_find_test_dependencies()
endif()

ament_auto_package(INSTALL_TO_SHARE config launch)

