# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/real_world_ovmm/tests/test_action_interface.py

Prompts

```
['run the stretch robot action interface test with optional --reset-nav flag to reset navigation', 'test continuous arm control by creating HybridAction with lift, arm, and pan parameters', 'test discrete navigation actions like TURN_RIGHT, TURN_LEFT, MANIPULATION_MODE, and NAVIGATION_MODE', 'run the print_action helper to inspect a HybridAction manipulation or navigation details', 'test updating the end-effector look-at pose using update_look_at_ee with STRETCH_PREGRASP_Q', 'run a click CLI command to test robot base motion navigating back and forth between two positions', 'load a Stretch robot pick-and-place environment configuration with optional visualization settings', 'create a Stretch robot pick-and-place environment instance with a config and ros_grasping flag', 'reset the Stretch pick-and-place environment with specified object names like table, cup, and chair', 'navigate the robot base to a specified x, y, theta coordinate position', 'test inverse kinematics by solving IK for the current end-effector pose and verifying forward kinematics', 'send a predicted grasp pose matrix to ROS TF for RViz visualization on the stretch robot', 'execute a grasp plan pose using the grasp planner with wait for input on the stretch robot', 'apply discrete navigation actions like turn left or turn right to the stretch robot environment', 'run robot manipulator motion to a target pose with specified velocity and acceleration profiles', 'get joint velocity values from a motion profiles dictionary for a given speed setting', 'get joint acceleration values from a motion profiles dictionary for a given speed setting', 'read and parse a YAML file into a Python dictionary using yaml.safe_load']
```

Usage

```
{'run_test_action_interface': 'run the stretch robot action interface test with optional --reset-nav flag to reset navigation', 'test_continuous_arm_control': 'test continuous arm control by creating HybridAction with lift, arm, and pan parameters', 'test_discrete_navigation_actions': 'test discrete navigation actions like TURN_RIGHT, TURN_LEFT, MANIPULATION_MODE, and NAVIGATION_MODE', 'run_print_action_helper': 'run the print_action helper to inspect a HybridAction manipulation or navigation details', 'test_pregrasp_ee_update': 'test updating the end-effector look-at pose using update_look_at_ee with STRETCH_PREGRASP_Q'}
```

## File: facebookresearch_home-robot/projects/real_world_ovmm/tests/test_motion.py

Prompts

```
['run the stretch robot action interface test with optional --reset-nav flag to reset navigation', 'test continuous arm control by creating HybridAction with lift, arm, and pan parameters', 'test discrete navigation actions like TURN_RIGHT, TURN_LEFT, MANIPULATION_MODE, and NAVIGATION_MODE', 'run the print_action helper to inspect a HybridAction manipulation or navigation details', 'test updating the end-effector look-at pose using update_look_at_ee with STRETCH_PREGRASP_Q', 'run a click CLI command to test robot base motion navigating back and forth between two positions', 'load a Stretch robot pick-and-place environment configuration with optional visualization settings', 'create a Stretch robot pick-and-place environment instance with a config and ros_grasping flag', 'reset the Stretch pick-and-place environment with specified object names like table, cup, and chair', 'navigate the robot base to a specified x, y, theta coordinate position', 'test inverse kinematics by solving IK for the current end-effector pose and verifying forward kinematics', 'send a predicted grasp pose matrix to ROS TF for RViz visualization on the stretch robot', 'execute a grasp plan pose using the grasp planner with wait for input on the stretch robot', 'apply discrete navigation actions like turn left or turn right to the stretch robot environment', 'run robot manipulator motion to a target pose with specified velocity and acceleration profiles', 'get joint velocity values from a motion profiles dictionary for a given speed setting', 'get joint acceleration values from a motion profiles dictionary for a given speed setting', 'read and parse a YAML file into a Python dictionary using yaml.safe_load']
```

Usage

```
{'run_experiment': 'run a click CLI command to test robot base motion navigating back and forth between two positions', 'load_config': 'load a Stretch robot pick-and-place environment configuration with optional visualization settings', 'StretchPickandPlaceEnv': 'create a Stretch robot pick-and-place environment instance with a config and ros_grasping flag', 'env_reset': 'reset the Stretch pick-and-place environment with specified object names like table, cup, and chair', 'navigate_to': 'navigate the robot base to a specified x, y, theta coordinate position'}
```

## File: facebookresearch_home-robot/projects/real_world_ovmm/tests/test_pick.py

Prompts

```
['run the stretch robot action interface test with optional --reset-nav flag to reset navigation', 'test continuous arm control by creating HybridAction with lift, arm, and pan parameters', 'test discrete navigation actions like TURN_RIGHT, TURN_LEFT, MANIPULATION_MODE, and NAVIGATION_MODE', 'run the print_action helper to inspect a HybridAction manipulation or navigation details', 'test updating the end-effector look-at pose using update_look_at_ee with STRETCH_PREGRASP_Q', 'run a click CLI command to test robot base motion navigating back and forth between two positions', 'load a Stretch robot pick-and-place environment configuration with optional visualization settings', 'create a Stretch robot pick-and-place environment instance with a config and ros_grasping flag', 'reset the Stretch pick-and-place environment with specified object names like table, cup, and chair', 'navigate the robot base to a specified x, y, theta coordinate position', 'test inverse kinematics by solving IK for the current end-effector pose and verifying forward kinematics', 'send a predicted grasp pose matrix to ROS TF for RViz visualization on the stretch robot', 'execute a grasp plan pose using the grasp planner with wait for input on the stretch robot', 'apply discrete navigation actions like turn left or turn right to the stretch robot environment', 'run robot manipulator motion to a target pose with specified velocity and acceleration profiles', 'get joint velocity values from a motion profiles dictionary for a given speed setting', 'get joint acceleration values from a motion profiles dictionary for a given speed setting', 'read and parse a YAML file into a Python dictionary using yaml.safe_load']
```

Usage

```
{'run_experiment': 'run the stretch robot pick and place experiment with click CLI options for test ID and navigation reset', 'test_current_cfg': 'test inverse kinematics by solving IK for the current end-effector pose and verifying forward kinematics', 'send_predicted_grasp_to_tf': 'send a predicted grasp pose matrix to ROS TF for RViz visualization on the stretch robot', 'execute_grasp_plan': 'execute a grasp plan pose using the grasp planner with wait for input on the stretch robot', 'apply_discrete_navigation_action': 'apply discrete navigation actions like turn left or turn right to the stretch robot environment'}
```

## File: facebookresearch_home-robot/projects/real_world_ovmm/tests/test_vel_and_accel.py

Prompts

```
['run the stretch robot action interface test with optional --reset-nav flag to reset navigation', 'test continuous arm control by creating HybridAction with lift, arm, and pan parameters', 'test discrete navigation actions like TURN_RIGHT, TURN_LEFT, MANIPULATION_MODE, and NAVIGATION_MODE', 'run the print_action helper to inspect a HybridAction manipulation or navigation details', 'test updating the end-effector look-at pose using update_look_at_ee with STRETCH_PREGRASP_Q', 'run a click CLI command to test robot base motion navigating back and forth between two positions', 'load a Stretch robot pick-and-place environment configuration with optional visualization settings', 'create a Stretch robot pick-and-place environment instance with a config and ros_grasping flag', 'reset the Stretch pick-and-place environment with specified object names like table, cup, and chair', 'navigate the robot base to a specified x, y, theta coordinate position', 'test inverse kinematics by solving IK for the current end-effector pose and verifying forward kinematics', 'send a predicted grasp pose matrix to ROS TF for RViz visualization on the stretch robot', 'execute a grasp plan pose using the grasp planner with wait for input on the stretch robot', 'apply discrete navigation actions like turn left or turn right to the stretch robot environment', 'run robot manipulator motion to a target pose with specified velocity and acceleration profiles', 'get joint velocity values from a motion profiles dictionary for a given speed setting', 'get joint acceleration values from a motion profiles dictionary for a given speed setting', 'read and parse a YAML file into a Python dictionary using yaml.safe_load']
```

Usage

```
{'run_experiment': 'run a Stretch robot velocity and acceleration experiment with different motion profiles via CLI', 'run_robot_motion': 'run robot manipulator motion to a target pose with specified velocity and acceleration profiles', 'get_velocities': 'get joint velocity values from a motion profiles dictionary for a given speed setting', 'get_accelerations': 'get joint acceleration values from a motion profiles dictionary for a given speed setting', 'read_yaml': 'read and parse a YAML file into a Python dictionary using yaml.safe_load'}
```

