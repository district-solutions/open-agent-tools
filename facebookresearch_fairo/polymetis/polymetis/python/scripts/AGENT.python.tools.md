# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/scripts/benchmark_control_latency.py

Prompts

```
['run the polymetis control latency benchmark script to measure joint PD and cartesian PD loop latency', 'run output_episode_stats to print latency mean, std, max, min, and success rate for robot states', 'test RobotInterface move_to_joint_positions by moving the robot to its current joint positions', 'test RobotInterface move_to_ee_pose by moving the robot end-effector to its current pose', 'review the output_episode_stats function that computes and prints control loop latency statistics from robot states', 'run the launch_robot script to start a Polymetis robot server on a configured IP and port', 'run the launch_robot script with real-time scheduling enabled using sudo privileges', 'run the launch_robot script to start a server and instantiate a configured robot client', 'review the main function that starts a robot server process and optionally a robot client', 'review the cleanup function that kills the server subprocess and its process group on exit', 'run the RobotStateVisualizer to stream robot state data from a gRPC server and visualize it', 'read protobuf messages from a binary log file and yield parsed RobotState objects', 'write a protobuf message to a file with varint-encoded length prefix', 'process the state queue and return DataFrames for joint positions, velocities, and torques', 'initialize Plotly subplot graphs from processed robot state DataFrames for visualization']
```

Usage

```
{'run_benchmark_control_latency': 'run the polymetis control latency benchmark script to measure joint PD and cartesian PD loop latency', 'run_output_episode_stats': 'run output_episode_stats to print latency mean, std, max, min, and success rate for robot states', 'test_robot_interface_move_to_joint_positions': 'test RobotInterface move_to_joint_positions by moving the robot to its current joint positions', 'test_robot_interface_move_to_ee_pose': 'test RobotInterface move_to_ee_pose by moving the robot end-effector to its current pose', 'review_output_episode_stats': 'review the output_episode_stats function that computes and prints control loop latency statistics from robot states'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/scripts/launch_robot.py

Prompts

```
['run the polymetis control latency benchmark script to measure joint PD and cartesian PD loop latency', 'run output_episode_stats to print latency mean, std, max, min, and success rate for robot states', 'test RobotInterface move_to_joint_positions by moving the robot to its current joint positions', 'test RobotInterface move_to_ee_pose by moving the robot end-effector to its current pose', 'review the output_episode_stats function that computes and prints control loop latency statistics from robot states', 'run the launch_robot script to start a Polymetis robot server on a configured IP and port', 'run the launch_robot script with real-time scheduling enabled using sudo privileges', 'run the launch_robot script to start a server and instantiate a configured robot client', 'review the main function that starts a robot server process and optionally a robot client', 'review the cleanup function that kills the server subprocess and its process group on exit', 'run the RobotStateVisualizer to stream robot state data from a gRPC server and visualize it', 'read protobuf messages from a binary log file and yield parsed RobotState objects', 'write a protobuf message to a file with varint-encoded length prefix', 'process the state queue and return DataFrames for joint positions, velocities, and torques', 'initialize Plotly subplot graphs from processed robot state DataFrames for visualization']
```

Usage

```
{'run_launch_robot': 'run the launch_robot script to start a Polymetis robot server on a configured IP and port', 'run_launch_robot_with_realtime': 'run the launch_robot script with real-time scheduling enabled using sudo privileges', 'run_launch_robot_with_client': 'run the launch_robot script to start a server and instantiate a configured robot client', 'review_main_function': 'review the main function that starts a robot server process and optionally a robot client', 'review_cleanup_function': 'review the cleanup function that kills the server subprocess and its process group on exit'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/scripts/viz.py

Prompts

```
['run the polymetis control latency benchmark script to measure joint PD and cartesian PD loop latency', 'run output_episode_stats to print latency mean, std, max, min, and success rate for robot states', 'test RobotInterface move_to_joint_positions by moving the robot to its current joint positions', 'test RobotInterface move_to_ee_pose by moving the robot end-effector to its current pose', 'review the output_episode_stats function that computes and prints control loop latency statistics from robot states', 'run the launch_robot script to start a Polymetis robot server on a configured IP and port', 'run the launch_robot script with real-time scheduling enabled using sudo privileges', 'run the launch_robot script to start a server and instantiate a configured robot client', 'review the main function that starts a robot server process and optionally a robot client', 'review the cleanup function that kills the server subprocess and its process group on exit', 'run the RobotStateVisualizer to stream robot state data from a gRPC server and visualize it', 'read protobuf messages from a binary log file and yield parsed RobotState objects', 'write a protobuf message to a file with varint-encoded length prefix', 'process the state queue and return DataFrames for joint positions, velocities, and torques', 'initialize Plotly subplot graphs from processed robot state DataFrames for visualization']
```

Usage

```
{'run_robot_state_visualizer': 'run the RobotStateVisualizer to stream robot state data from a gRPC server and visualize it', 'read_protobuf_messages': 'read protobuf messages from a binary log file and yield parsed RobotState objects', 'write_protobuf_message': 'write a protobuf message to a file with varint-encoded length prefix', 'process_robot_state_queue': 'process the state queue and return DataFrames for joint positions, velocities, and torques', 'initialize_plotly_graphs': 'initialize Plotly subplot graphs from processed robot state DataFrames for visualization'}
```

