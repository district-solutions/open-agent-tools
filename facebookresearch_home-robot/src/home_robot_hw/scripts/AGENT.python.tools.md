# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot_hw/scripts/interactive_marker.py

Prompts

```
['run the interactive marker ROS node to teleoperate a Stretch robot via 6-DOF marker controls', 'create a 6-DOF interactive marker with rotate and move axis controls for robot teleoperation', 'record a robot demonstration as HDF5 keyframes with RGB and depth images during interactive teleoperation', 'process interactive marker feedback events including pose updates, menu selects, and button clicks', 'command the Stretch robot to move its arm to the current interactive marker pose using inverse kinematics', 'run the ROS node that subscribes to camera color and depth topics and publishes rotated images', 'run the color image callback that rotates incoming color images 270 degrees and publishes them', 'run the depth image callback that rotates incoming depth images 270 degrees and publishes them', 'review the callback_color function that converts ROS Image messages to numpy arrays, rotates them, and republishes', 'review the callback_depth function that converts ROS Image messages to numpy arrays, rotates them, and republishes']
```

Usage

```
{'run_interactive_marker_teleop': 'run the interactive marker ROS node to teleoperate a Stretch robot via 6-DOF marker controls', 'create_6dof_marker': 'create a 6-DOF interactive marker with rotate and move axis controls for robot teleoperation', 'record_robot_demonstration': 'record a robot demonstration as HDF5 keyframes with RGB and depth images during interactive teleoperation', 'process_interactive_marker_feedback': 'process interactive marker feedback events including pose updates, menu selects, and button clicks', 'move_robot_to_marker_pose': 'command the Stretch robot to move its arm to the current interactive marker pose using inverse kinematics'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/scripts/rotate_images.py

Prompts

```
['run the interactive marker ROS node to teleoperate a Stretch robot via 6-DOF marker controls', 'create a 6-DOF interactive marker with rotate and move axis controls for robot teleoperation', 'record a robot demonstration as HDF5 keyframes with RGB and depth images during interactive teleoperation', 'process interactive marker feedback events including pose updates, menu selects, and button clicks', 'command the Stretch robot to move its arm to the current interactive marker pose using inverse kinematics', 'run the ROS node that subscribes to camera color and depth topics and publishes rotated images', 'run the color image callback that rotates incoming color images 270 degrees and publishes them', 'run the depth image callback that rotates incoming depth images 270 degrees and publishes them', 'review the callback_color function that converts ROS Image messages to numpy arrays, rotates them, and republishes', 'review the callback_depth function that converts ROS Image messages to numpy arrays, rotates them, and republishes']
```

Usage

```
{'run_rotate_images_node': 'run the ROS node that subscribes to camera color and depth topics and publishes rotated images', 'run_callback_color': 'run the color image callback that rotates incoming color images 270 degrees and publishes them', 'run_callback_depth': 'run the depth image callback that rotates incoming depth images 270 degrees and publishes them', 'review_callback_color': 'review the callback_color function that converts ROS Image messages to numpy arrays, rotates them, and republishes', 'review_callback_depth': 'review the callback_depth function that converts ROS Image messages to numpy arrays, rotates them, and republishes'}
```

