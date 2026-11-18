cmake_minimum_required(VERSION 3.10)
project(pal_gripper_simulation)

# find dependencies
find_package(ament_cmake_auto REQUIRED)

ament_auto_find_build_dependencies()

if(BUILD_TESTING)
  find_package(ament_lint_auto REQUIRED)
  ament_lint_auto_find_test_dependencies()
endif()


ament_auto_package(INSTALL_TO_SHARE launch)
