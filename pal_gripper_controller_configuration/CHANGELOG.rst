^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pal_gripper_controller_configuration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.1.0 (2024-01-18)
------------------
* Merge branch 'tiago-dual' into 'humble-devel'
  Adapted pal_gripper_controller_configuration to ros2
  See merge request robots/pal_gripper!32
* CMake version to 3.8
* Update variable name of gripper_prefix
* Change to ee_suffix
* Default side argument set to empty
* combine gripper controller params in single file with parametrization
* Contributors: David ter Kuile, davidterkuile

3.0.7 (2023-12-12)
------------------
* adding the pal_gripper_controller launcher
* Contributors: Aina Irisarri

3.0.6 (2023-12-11)
------------------
* Add left and right controller
* Contributors: David ter Kuile

3.0.5 (2023-11-14)
------------------
* Add website tag
* Contributors: Noel Jimenez

3.0.4 (2023-04-17)
------------------

3.0.3 (2023-03-01)
------------------
* Merge branch 'rm_use_sim_time' into 'humble-devel'
  Remove unecessary use_sim_time
  See merge request robots/pal_gripper!23
* rm unnecessary use_sim_time
* Merge branch 'fix_controllers_config' into 'humble-devel'
  Remove initial / from controllers config
  See merge request robots/pal_gripper!25
* remove initial / from controllers config
* Contributors: Jordan Palacios, Noel Jimenez

3.0.2 (2023-02-08)
------------------

3.0.1 (2022-12-15)
------------------
* Merge branch 'sim_time' into 'humble-devel'
  set sim time param
  See merge request robots/pal_gripper!20
* set sim time param
* Contributors: Jordan Palacios, Noel Jimenez

3.0.0 (2022-10-26)
------------------
* Merge branch 'linters' into 'humble-devel'
  Linters
  See merge request robots/pal_gripper!17
* linters
* add linters
* Merge branch 'update_copyright' into 'humble-devel'
  Update copyright and add LICENSE
  See merge request robots/pal_gripper!15
* update copyright and add license
* Merge branch 'update_maintainers' into 'humble-devel'
  update maintainers
  See merge request robots/pal_gripper!14
* update maintainers
* Merge branch 'move_gripper_controller_launch' into 'foxy-devel'
  move controller launch to tiago_controller_configuration
  See merge request robots/pal_gripper!12
* move controller launch to tiago_controller_configuration
* Added new parameters required for joint trajectory controllers
* Use correct namespacing for parameters
* Using controller_manager launch_utils
* Adapted pal_gripper_controller_configuration to ros2
  Added ros2_control xacro file
* ros2 format. Disabled some packages
* Contributors: Jordan Palacios, Noel Jimenez, cescfolch, victor

1.0.3 (2020-04-30)
------------------
* Merge branch 'removed_open_gripper' into 'erbium-devel'
  Removed open gripper node in launch
  See merge request robots/pal_gripper!9
* Removed open gripper node in launch
* Contributors: saikishor, victor

1.0.2 (2019-06-11)
------------------
* Merge branch 'more-side-fixes' into 'erbium-devel'
  More side fixes
  See merge request robots/pal_gripper!8
* More side fixes
* Contributors: Victor Lopez

1.0.1 (2019-03-26)
------------------
* Merge branch 'add-sides' into 'erbium-devel'
  Add option to specify side of gripper
  See merge request robots/pal_gripper!7
* Fix suffix usage
* Fix action server name
* Add option to specify side of gripper
* Contributors: Victor Lopez

1.0.0 (2018-07-30)
------------------

0.0.13 (2018-04-13)
-------------------

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
* fix maintainer
* 0.0.8
* Update changelog
* Launch current limit controller
* 0.0.7
* Update changelogs
* 0.0.6
* Update cahngelog
* 0.0.5
* Update changelog
* 0.0.4
* Update changelgo
* 0.0.3
* Update changelogs
* 0.0.2
* Updated the changelog
* Added install rules pal gripper configuration
* Contributors: Hilario Tome, Jordi Pages, Sam Pfeiffer, Victor Lopez

0.0.1 (2016-06-01)
------------------
* Initial version
* Contributors: Sam Pfeiffer
