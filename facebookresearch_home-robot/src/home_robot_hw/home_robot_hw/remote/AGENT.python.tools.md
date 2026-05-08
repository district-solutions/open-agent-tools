# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/remote/api.py

Prompts

```
['create a StretchClient instance to interface with the real Stretch robot via ROS', 'switch the Stretch robot to navigation mode with continuous velocity feedback control', 'switch the Stretch robot to manipulation mode with position control and locked base rotation', 'get an observation from the robot including RGB, depth, XYZ, GPS, compass, and joint state', 'navigate the robot to a target XYT pose in global or relative coordinates', 'create a StretchRosInterface instance to initialize ROS topics, cameras, and lidar for the Stretch robot', 'send a dictionary of joint name to target value goals to the Stretch robot trajectory action server', 'move the robot to a full configuration q by calling goto with a numpy array of joint positions', 'trigger FUNMAP-based grasping at a 3D point x, y, z in the map frame using trigger_grasp', 'trigger FUNMAP-based placement at a 3D point x, y, z in the map frame using trigger_placement', 'get the current robot joint positions, velocities, and forces as numpy arrays via get_joint_state', 'move the robot wrist to absolute roll, pitch, and yaw angles using goto_wrist', 'move the robot lift joint by a delta position using goto_lift_position', 'open or close the gripper by a delta position using goto_gripper_position', 'look up the transform matrix for a named TF frame relative to the base link using get_frame_pose']
```

Usage

```
{'create_stretch_client': 'create a StretchClient instance to interface with the real Stretch robot via ROS', 'switch_to_navigation_mode': 'switch the Stretch robot to navigation mode with continuous velocity feedback control', 'switch_to_manipulation_mode': 'switch the Stretch robot to manipulation mode with position control and locked base rotation', 'get_observation': 'get an observation from the robot including RGB, depth, XYZ, GPS, compass, and joint state', 'navigate_to': 'navigate the robot to a target XYT pose in global or relative coordinates'}
```

## File: facebookresearch_home-robot/src/home_robot_hw/home_robot_hw/remote/ros.py

Prompts

```
['create a StretchClient instance to interface with the real Stretch robot via ROS', 'switch the Stretch robot to navigation mode with continuous velocity feedback control', 'switch the Stretch robot to manipulation mode with position control and locked base rotation', 'get an observation from the robot including RGB, depth, XYZ, GPS, compass, and joint state', 'navigate the robot to a target XYT pose in global or relative coordinates', 'create a StretchRosInterface instance to initialize ROS topics, cameras, and lidar for the Stretch robot', 'send a dictionary of joint name to target value goals to the Stretch robot trajectory action server', 'move the robot to a full configuration q by calling goto with a numpy array of joint positions', 'trigger FUNMAP-based grasping at a 3D point x, y, z in the map frame using trigger_grasp', 'trigger FUNMAP-based placement at a 3D point x, y, z in the map frame using trigger_placement', 'get the current robot joint positions, velocities, and forces as numpy arrays via get_joint_state', 'move the robot wrist to absolute roll, pitch, and yaw angles using goto_wrist', 'move the robot lift joint by a delta position using goto_lift_position', 'open or close the gripper by a delta position using goto_gripper_position', 'look up the transform matrix for a named TF frame relative to the base link using get_frame_pose']
```

Usage

```
{'create_stretch_ros_interface': 'create a StretchRosInterface instance to initialize ROS topics, cameras, and lidar for the Stretch robot', 'send_trajectory_goals': 'send a dictionary of joint name to target value goals to the Stretch robot trajectory action server', 'goto_joint_position': 'move the robot to a full configuration q by calling goto with a numpy array of joint positions', 'trigger_grasp': 'trigger FUNMAP-based grasping at a 3D point x, y, z in the map frame using trigger_grasp', 'trigger_placement': 'trigger FUNMAP-based placement at a 3D point x, y, z in the map frame using trigger_placement', 'get_joint_state': 'get the current robot joint positions, velocities, and forces as numpy arrays via get_joint_state', 'goto_wrist': 'move the robot wrist to absolute roll, pitch, and yaw angles using goto_wrist', 'goto_lift_position': 'move the robot lift joint by a delta position using goto_lift_position', 'goto_gripper_position': 'open or close the gripper by a delta position using goto_gripper_position', 'get_frame_pose': 'look up the transform matrix for a named TF frame relative to the base link using get_frame_pose'}
```

