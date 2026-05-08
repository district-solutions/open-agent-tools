# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/remote/modules/abstract.py

Prompts

```
['create a subclass of AbstractControlModule to implement a custom robot control module with enable and disable hooks', 'use the enforce_enabled decorator to restrict a method so it only runs when the control module is enabled', 'register a wait function with _register_wait to run an action in a background thread without blocking', 'check if any background action threads are still running by calling the is_busy method', 'wait for all registered background action threads to complete using the wait method with an optional timeout', 'get the camera pose matrix with optional rotation applied for the robot head', 'get the camera pose in base coordinates using tf for grasp computation', 'set the head pan and tilt joint angles with optional blocking behavior', 'get RGB and depth images from the robot camera with optional XYZ point cloud', 'convert a depth image array to XYZ 3D coordinates using camera intrinsics', 'get the end-effector pose as position and quaternion in base or world frame', 'command the stretch robot arm to move to specified joint positions with optional relative mode', 'command the robot gripper to move to a target end-effector pose using inverse kinematics', 'open or close the robot gripper to its full range with optional blocking behavior', 'rotate the robot end-effector by a specified angle around one of the X, Y, or Z axes', 'navigate the robot to a specified xyt goal pose in world coordinates', 'execute a multi-step trajectory by navigating the robot through a list of waypoints', 'get the latest base pose of the robot from sensors as xyt or matrix', 'wait until the robot has reached a target waypoint within position and rotation thresholds', 'set the linear and angular velocity of the robot base directly']
```

Usage

```
{'create_control_module': 'create a subclass of AbstractControlModule to implement a custom robot control module with enable and disable hooks', 'use_enforce_enabled_decorator': 'use the enforce_enabled decorator to restrict a method so it only runs when the control module is enabled', 'register_wait_thread': 'register a wait function with _register_wait to run an action in a background thread without blocking', 'check_is_busy': 'check if any background action threads are still running by calling the is_busy method', 'wait_for_threads': 'wait for all registered background action threads to complete using the wait method with an optional timeout'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/remote/modules/head.py

Prompts

```
['create a subclass of AbstractControlModule to implement a custom robot control module with enable and disable hooks', 'use the enforce_enabled decorator to restrict a method so it only runs when the control module is enabled', 'register a wait function with _register_wait to run an action in a background thread without blocking', 'check if any background action threads are still running by calling the is_busy method', 'wait for all registered background action threads to complete using the wait method with an optional timeout', 'get the camera pose matrix with optional rotation applied for the robot head', 'get the camera pose in base coordinates using tf for grasp computation', 'set the head pan and tilt joint angles with optional blocking behavior', 'get RGB and depth images from the robot camera with optional XYZ point cloud', 'convert a depth image array to XYZ 3D coordinates using camera intrinsics', 'get the end-effector pose as position and quaternion in base or world frame', 'command the stretch robot arm to move to specified joint positions with optional relative mode', 'command the robot gripper to move to a target end-effector pose using inverse kinematics', 'open or close the robot gripper to its full range with optional blocking behavior', 'rotate the robot end-effector by a specified angle around one of the X, Y, or Z axes', 'navigate the robot to a specified xyt goal pose in world coordinates', 'execute a multi-step trajectory by navigating the robot through a list of waypoints', 'get the latest base pose of the robot from sensors as xyt or matrix', 'wait until the robot has reached a target waypoint within position and rotation thresholds', 'set the linear and angular velocity of the robot base directly']
```

Usage

```
{'get_camera_pose': 'get the camera pose matrix with optional rotation applied for the robot head', 'get_pose_in_base_coords': 'get the camera pose in base coordinates using tf for grasp computation', 'set_pan_tilt': 'set the head pan and tilt joint angles with optional blocking behavior', 'get_images': 'get RGB and depth images from the robot camera with optional XYZ point cloud', 'depth_to_xyz': 'convert a depth image array to XYZ 3D coordinates using camera intrinsics'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/remote/modules/manip.py

Prompts

```
['create a subclass of AbstractControlModule to implement a custom robot control module with enable and disable hooks', 'use the enforce_enabled decorator to restrict a method so it only runs when the control module is enabled', 'register a wait function with _register_wait to run an action in a background thread without blocking', 'check if any background action threads are still running by calling the is_busy method', 'wait for all registered background action threads to complete using the wait method with an optional timeout', 'get the camera pose matrix with optional rotation applied for the robot head', 'get the camera pose in base coordinates using tf for grasp computation', 'set the head pan and tilt joint angles with optional blocking behavior', 'get RGB and depth images from the robot camera with optional XYZ point cloud', 'convert a depth image array to XYZ 3D coordinates using camera intrinsics', 'get the end-effector pose as position and quaternion in base or world frame', 'command the stretch robot arm to move to specified joint positions with optional relative mode', 'command the robot gripper to move to a target end-effector pose using inverse kinematics', 'open or close the robot gripper to its full range with optional blocking behavior', 'rotate the robot end-effector by a specified angle around one of the X, Y, or Z axes', 'navigate the robot to a specified xyt goal pose in world coordinates', 'execute a multi-step trajectory by navigating the robot through a list of waypoints', 'get the latest base pose of the robot from sensors as xyt or matrix', 'wait until the robot has reached a target waypoint within position and rotation thresholds', 'set the linear and angular velocity of the robot base directly']
```

Usage

```
{'get_ee_pose': 'get the end-effector pose as position and quaternion in base or world frame', 'goto_joint_positions': 'command the stretch robot arm to move to specified joint positions with optional relative mode', 'goto_ee_pose': 'command the robot gripper to move to a target end-effector pose using inverse kinematics', 'open_gripper_close_gripper': 'open or close the robot gripper to its full range with optional blocking behavior', 'rotate_ee': 'rotate the robot end-effector by a specified angle around one of the X, Y, or Z axes'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/remote/modules/nav.py

Prompts

```
['create a subclass of AbstractControlModule to implement a custom robot control module with enable and disable hooks', 'use the enforce_enabled decorator to restrict a method so it only runs when the control module is enabled', 'register a wait function with _register_wait to run an action in a background thread without blocking', 'check if any background action threads are still running by calling the is_busy method', 'wait for all registered background action threads to complete using the wait method with an optional timeout', 'get the camera pose matrix with optional rotation applied for the robot head', 'get the camera pose in base coordinates using tf for grasp computation', 'set the head pan and tilt joint angles with optional blocking behavior', 'get RGB and depth images from the robot camera with optional XYZ point cloud', 'convert a depth image array to XYZ 3D coordinates using camera intrinsics', 'get the end-effector pose as position and quaternion in base or world frame', 'command the stretch robot arm to move to specified joint positions with optional relative mode', 'command the robot gripper to move to a target end-effector pose using inverse kinematics', 'open or close the robot gripper to its full range with optional blocking behavior', 'rotate the robot end-effector by a specified angle around one of the X, Y, or Z axes', 'navigate the robot to a specified xyt goal pose in world coordinates', 'execute a multi-step trajectory by navigating the robot through a list of waypoints', 'get the latest base pose of the robot from sensors as xyt or matrix', 'wait until the robot has reached a target waypoint within position and rotation thresholds', 'set the linear and angular velocity of the robot base directly']
```

Usage

```
{'navigate_to_goal': 'navigate the robot to a specified xyt goal pose in world coordinates', 'execute_trajectory': 'execute a multi-step trajectory by navigating the robot through a list of waypoints', 'get_base_pose': 'get the latest base pose of the robot from sensors as xyt or matrix', 'wait_for_waypoint': 'wait until the robot has reached a target waypoint within position and rotation thresholds', 'set_velocity': 'set the linear and angular velocity of the robot base directly'}
```

