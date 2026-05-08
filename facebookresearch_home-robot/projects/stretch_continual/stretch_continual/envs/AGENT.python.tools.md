# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/stretch_continual/stretch_continual/envs/stretch_collect_demo_env.py

Prompts

```
['create a StretchCollectDemoEnv instance to collect robot demos with Xbox controller callbacks and recording', 'run the step loop on a StretchCollectDemoEnv to collect observations and actions during an episode', 'reset the StretchCollectDemoEnv to initialize the current timestep and get the first observation', 'review the _start_button_callback method that toggles episode recording start and stop states', 'refactor the _publish_to_ros method to publish key frame poses as ROS TransformStamped messages', 'load all h5 trajectory files from a directory into an aggregated h5 file with ExternalLink support', 'randomly select a trajectory from h5 files in a directory with retry logic and caching', 'compute the end-effector position and rotation from the robot model and current joint pose', 'compute inverse kinematics for the gripper with wrist roll normalization to prevent full rotations', 'construct a combined observation dict with image, depth, pose, and camera info for the Stretch robot environment', 'create a StretchLiveEnv instance with a demo directory and optional camera info in state', 'run the reset method on StretchLiveEnv to load a random trajectory and position the robot', 'run a step action on StretchLiveEnv to execute predicted robot actions with IK and interpolation', 'review the _interpolate_robot_to_in_joint_space method for naive joint space interpolation logic', 'refactor the StretchLiveEnv exec_tol array to adjust execution tolerance thresholds per joint dimension', 'create a StretchOfflineDemoEnv instance with a demo directory and camera info settings', 'reset the offline demo environment to randomly select a new trajectory from the demo directory', 'step through the current demo trajectory and return the next observation and done flag', 'get the observation for a specific timestep including RGB, depth, and joint state data', 'construct color and depth camera info plus camera pose from a demo trajectory at a timestep']
```

Usage

```
{'create_StretchCollectDemoEnv': 'create a StretchCollectDemoEnv instance to collect robot demos with Xbox controller callbacks and recording', 'run_step_loop': 'run the step loop on a StretchCollectDemoEnv to collect observations and actions during an episode', 'reset_environment': 'reset the StretchCollectDemoEnv to initialize the current timestep and get the first observation', 'review_start_button_callback': 'review the _start_button_callback method that toggles episode recording start and stop states', 'refactor_publish_to_ros': 'refactor the _publish_to_ros method to publish key frame poses as ROS TransformStamped messages'}
```

## File: facebookresearch_home-robot/projects/stretch_continual/stretch_continual/envs/stretch_demo_base_env.py

Prompts

```
['create a StretchCollectDemoEnv instance to collect robot demos with Xbox controller callbacks and recording', 'run the step loop on a StretchCollectDemoEnv to collect observations and actions during an episode', 'reset the StretchCollectDemoEnv to initialize the current timestep and get the first observation', 'review the _start_button_callback method that toggles episode recording start and stop states', 'refactor the _publish_to_ros method to publish key frame poses as ROS TransformStamped messages', 'load all h5 trajectory files from a directory into an aggregated h5 file with ExternalLink support', 'randomly select a trajectory from h5 files in a directory with retry logic and caching', 'compute the end-effector position and rotation from the robot model and current joint pose', 'compute inverse kinematics for the gripper with wrist roll normalization to prevent full rotations', 'construct a combined observation dict with image, depth, pose, and camera info for the Stretch robot environment', 'create a StretchLiveEnv instance with a demo directory and optional camera info in state', 'run the reset method on StretchLiveEnv to load a random trajectory and position the robot', 'run a step action on StretchLiveEnv to execute predicted robot actions with IK and interpolation', 'review the _interpolate_robot_to_in_joint_space method for naive joint space interpolation logic', 'refactor the StretchLiveEnv exec_tol array to adjust execution tolerance thresholds per joint dimension', 'create a StretchOfflineDemoEnv instance with a demo directory and camera info settings', 'reset the offline demo environment to randomly select a new trajectory from the demo directory', 'step through the current demo trajectory and return the next observation and done flag', 'get the observation for a specific timestep including RGB, depth, and joint state data', 'construct color and depth camera info plus camera pose from a demo trajectory at a timestep']
```

Usage

```
{'load_h5_trajectories': 'load all h5 trajectory files from a directory into an aggregated h5 file with ExternalLink support', 'select_random_trajectory': 'randomly select a trajectory from h5 files in a directory with retry logic and caching', 'compute_gripper_forward_kinematics': 'compute the end-effector position and rotation from the robot model and current joint pose', 'compute_gripper_inverse_kinematics': 'compute inverse kinematics for the gripper with wrist roll normalization to prevent full rotations', 'construct_observation': 'construct a combined observation dict with image, depth, pose, and camera info for the Stretch robot environment'}
```

## File: facebookresearch_home-robot/projects/stretch_continual/stretch_continual/envs/stretch_live_env.py

Prompts

```
['create a StretchCollectDemoEnv instance to collect robot demos with Xbox controller callbacks and recording', 'run the step loop on a StretchCollectDemoEnv to collect observations and actions during an episode', 'reset the StretchCollectDemoEnv to initialize the current timestep and get the first observation', 'review the _start_button_callback method that toggles episode recording start and stop states', 'refactor the _publish_to_ros method to publish key frame poses as ROS TransformStamped messages', 'load all h5 trajectory files from a directory into an aggregated h5 file with ExternalLink support', 'randomly select a trajectory from h5 files in a directory with retry logic and caching', 'compute the end-effector position and rotation from the robot model and current joint pose', 'compute inverse kinematics for the gripper with wrist roll normalization to prevent full rotations', 'construct a combined observation dict with image, depth, pose, and camera info for the Stretch robot environment', 'create a StretchLiveEnv instance with a demo directory and optional camera info in state', 'run the reset method on StretchLiveEnv to load a random trajectory and position the robot', 'run a step action on StretchLiveEnv to execute predicted robot actions with IK and interpolation', 'review the _interpolate_robot_to_in_joint_space method for naive joint space interpolation logic', 'refactor the StretchLiveEnv exec_tol array to adjust execution tolerance thresholds per joint dimension', 'create a StretchOfflineDemoEnv instance with a demo directory and camera info settings', 'reset the offline demo environment to randomly select a new trajectory from the demo directory', 'step through the current demo trajectory and return the next observation and done flag', 'get the observation for a specific timestep including RGB, depth, and joint state data', 'construct color and depth camera info plus camera pose from a demo trajectory at a timestep']
```

Usage

```
{'create_StretchLiveEnv': 'create a StretchLiveEnv instance with a demo directory and optional camera info in state', 'run_StretchLiveEnv_reset': 'run the reset method on StretchLiveEnv to load a random trajectory and position the robot', 'run_StretchLiveEnv_step': 'run a step action on StretchLiveEnv to execute predicted robot actions with IK and interpolation', 'review_StretchLiveEnv_interpolate': 'review the _interpolate_robot_to_in_joint_space method for naive joint space interpolation logic', 'refactor_StretchLiveEnv_exec_tol': 'refactor the StretchLiveEnv exec_tol array to adjust execution tolerance thresholds per joint dimension'}
```

## File: facebookresearch_home-robot/projects/stretch_continual/stretch_continual/envs/stretch_offline_demo_env.py

Prompts

```
['create a StretchCollectDemoEnv instance to collect robot demos with Xbox controller callbacks and recording', 'run the step loop on a StretchCollectDemoEnv to collect observations and actions during an episode', 'reset the StretchCollectDemoEnv to initialize the current timestep and get the first observation', 'review the _start_button_callback method that toggles episode recording start and stop states', 'refactor the _publish_to_ros method to publish key frame poses as ROS TransformStamped messages', 'load all h5 trajectory files from a directory into an aggregated h5 file with ExternalLink support', 'randomly select a trajectory from h5 files in a directory with retry logic and caching', 'compute the end-effector position and rotation from the robot model and current joint pose', 'compute inverse kinematics for the gripper with wrist roll normalization to prevent full rotations', 'construct a combined observation dict with image, depth, pose, and camera info for the Stretch robot environment', 'create a StretchLiveEnv instance with a demo directory and optional camera info in state', 'run the reset method on StretchLiveEnv to load a random trajectory and position the robot', 'run a step action on StretchLiveEnv to execute predicted robot actions with IK and interpolation', 'review the _interpolate_robot_to_in_joint_space method for naive joint space interpolation logic', 'refactor the StretchLiveEnv exec_tol array to adjust execution tolerance thresholds per joint dimension', 'create a StretchOfflineDemoEnv instance with a demo directory and camera info settings', 'reset the offline demo environment to randomly select a new trajectory from the demo directory', 'step through the current demo trajectory and return the next observation and done flag', 'get the observation for a specific timestep including RGB, depth, and joint state data', 'construct color and depth camera info plus camera pose from a demo trajectory at a timestep']
```

Usage

```
{'create_offline_demo_env': 'create a StretchOfflineDemoEnv instance with a demo directory and camera info settings', 'reset_environment_trajectory': 'reset the offline demo environment to randomly select a new trajectory from the demo directory', 'step_through_trajectory': 'step through the current demo trajectory and return the next observation and done flag', 'get_observation_for_timestep': 'get the observation for a specific timestep including RGB, depth, and joint state data', 'construct_camera_data_from_demo': 'construct color and depth camera info plus camera pose from a demo trajectory at a timestep'}
```

