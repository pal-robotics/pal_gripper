^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pal_gripper_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.5.0 (2024-12-16)
------------------
* Fix inertia + update interface link to match the real interface of the gripper
* Contributors: thomas.peyrucain

3.4.0 (2024-11-05)
------------------

3.3.0 (2024-08-07)
------------------

3.2.0 (2024-06-18)
------------------
* follow gripper ros2 structure
* add fixed link
* add ros2_control
* port to ros2 gazebo.urdf
* Contributors: Aina Irisarri

3.1.0 (2024-01-18)
------------------
* Merge branch 'tiago-dual' into 'humble-devel'
  Adapted pal_gripper_controller_configuration to ros2
  See merge request robots/pal_gripper!32
* CMake version to 3.8
* Contributors: David ter Kuile, davidterkuile

3.0.7 (2023-12-12)
------------------

3.0.6 (2023-12-11)
------------------
* Use pal_urdf_utils for common files
* Contributors: David ter Kuile

3.0.5 (2023-11-14)
------------------
* Add website tag
* Contributors: Noel Jimenez

3.0.4 (2023-04-17)
------------------
* rename motors to actuators
* Contributors: Noel Jimenez

3.0.3 (2023-03-01)
------------------

3.0.2 (2023-02-08)
------------------
* Merge branch 'update_transmissions' into 'humble-devel'
  ros2 update transmissions for pal-gripper
  See merge request robots/pal_gripper!22
* ros2 update transmissions for pal-gripper
* Contributors: Jordan Palacios, Noel Jimenez

3.0.1 (2022-12-15)
------------------

3.0.0 (2022-10-26)
------------------
* Merge branch 'cleanup' into 'humble-devel'
  Remove ros deps
  See merge request robots/pal_gripper!18
* rm ros deps
* Merge branch 'linters' into 'humble-devel'
  Linters
  See merge request robots/pal_gripper!17
* add linters
* Merge branch 'add_friction' into 'humble-devel'
  Add friction to gripper fingers
  See merge request robots/pal_gripper!16
* add friction to gripper fingers
* Merge branch 'update_copyright' into 'humble-devel'
  Update copyright and add LICENSE
  See merge request robots/pal_gripper!15
* update copyright and add license
* Merge branch 'update_maintainers' into 'humble-devel'
  update maintainers
  See merge request robots/pal_gripper!14
* update maintainers
* Adapted pal_gripper_controller_configuration to ros2
  Added ros2_control xacro file
* ros2 format. Disabled some packages
* Contributors: Jordan Palacios, Noel Jimenez

1.0.3 (2020-04-30)
------------------

1.0.2 (2019-06-11)
------------------

1.0.1 (2019-03-26)
------------------
* Merge branch 'add-sides' into 'erbium-devel'
  Add option to specify side of gripper
  See merge request robots/pal_gripper!7
* Fix missing dependency
* Merge branch 'fix_xacro_warning' into 'erbium-devel'
  fix xacro warning
  See merge request robots/pal_gripper!5
* rm usuless xacro property
* Added Sanity check
* deprecate upload_gripper.launch
* fix xacro.py deprecation warning
* fix xacro warning
  deprecated: xacro tags should be prepended with 'xacro' xml namespace.
  Use the following script to fix incorrect usage:
  find . -iname "*.xacro" | xargs sed -i 's#<\([/]\?\)\(if\|unless\|include\|arg\|property\|macro\|insert_block\)#<\1xacro:\2#g'
* Contributors: Jeremie Deray, Jordi Pages, Victor Lopez, davidfernandez

1.0.0 (2018-07-30)
------------------
* Merge branch 'fix-simulation-warnings' into 'erbium-devel'
  Fix simulation warnings
  See merge request robots/pal_gripper!6
* prepend missing 'xacro' tag
* remove link color discrepancy
* Contributors: Jordi Pages, Victor Lopez

0.0.13 (2018-04-13)
-------------------
* Merge branch 'add-tool-link' into 'dubnium-devel'
  Add tool link
  See merge request robots/pal_gripper!4
* Add tool link
* Contributors: Hilario Tome, Victor Lopez

0.0.12 (2018-02-20)
-------------------

0.0.11 (2018-01-24)
-------------------

0.0.10 (2018-01-24)
-------------------
* move scripts and config files from tiago_robot
* Contributors: Jordi Pages

0.0.9 (2016-10-14)
------------------
* Fixed problem with gripper_grasping_frame in wrong position
* fix maintainer
* 0.0.8
* Update changelog
* use box for fingers' collision model
* 0.0.7
* Update changelogs
* 0.0.6
* Update cahngelog
* remove grasping hack macro and tune friction
* update meshes and inertia matrices
* 0.0.5
* Update changelog
* Change gripper limit to 0.045
* 0.0.4
* Update changelgo
* Fix safety joint limit
* 0.0.3
* Update changelogs
* Added safety controller values
* 0.0.2
* Updated the changelog
* Added install rules
* Contributors: Adria Roig, Hilario Tome, Jordi Pages, Sam Pfeiffer, Victor Lopez

0.0.1 (2016-06-01)
------------------
* Initial version
* Contributors: Sam Pfeiffer
