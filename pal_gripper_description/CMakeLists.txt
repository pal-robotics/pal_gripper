cmake_minimum_required(VERSION 3.8)
project(pal_gripper_description)

find_package(ament_cmake_auto REQUIRED)
find_package(xacro REQUIRED)

# PAL Robotics stricter build flags, other developers should not worry about this
find_package(ament_cmake_pal QUIET)

ament_auto_find_build_dependencies()


#############
## Testing ##
#############

if(BUILD_TESTING)
  find_package(ament_lint_auto REQUIRED)
  ament_lint_auto_find_test_dependencies()
#  find_package(rostest REQUIRED)
#  add_rostest(test/test_gripper_test.test)
endif()



ament_auto_package(INSTALL_TO_SHARE gazebo meshes robots urdf)
