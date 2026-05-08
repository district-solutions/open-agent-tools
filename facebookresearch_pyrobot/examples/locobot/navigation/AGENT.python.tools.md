# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/examples/locobot/navigation/base_position_control.py

Prompts

```
['run the locobot base position control script to navigate the robot to a relative position', 'run the robot navigation demo with a configurable base controller and planner', 'test the robot base go_to_relative method with a specified position and close loop setting', 'review the main function that creates a Robot and navigates it to a relative position', 'refactor the get_time_str function to use a different timestamp format', 'run the locobot navigation script to move the robot to a relative position using map-based path planning', 'run the robot navigation demo with a custom base controller like ilqr and movebase planner', 'run the robot base navigation with closed-loop control and smooth trajectory enabled', 'review the main function that initializes a Robot with base config and executes go_to_relative navigation', 'review the get_time_str function that returns a formatted YYYY-MM-DD-HH-MM-SS timestamp string', 'run a locobot in circle trajectory tracking mode using the ilqr base controller', 'run a locobot in twocircles trajectory tracking mode with close loop control', 'run trajectory tracking on a custom robot name like locobot_lite with proportional controller', 'get the circle trajectory states for a robot using its odom and base config', 'get the twocircles trajectory states by concatenating a circle and negcircle path', 'run the locobot 3D map visualization using open3d and VSLAM point cloud data', 'create a locobot robot instance using the pyrobot Robot class for navigation tasks', 'get 3D map points and colors from the robot VSLAM system using get_3d_map', 'visualize a point cloud with colors in an open3d Visualizer window with coordinate frame', 'handle SIGINT signal to gracefully exit the 3D map visualization loop']
```

Usage

```
{'run_base_position_control': 'run the locobot base position control script to navigate the robot to a relative position', 'run_robot_navigation': 'run the robot navigation demo with a configurable base controller and planner', 'test_go_to_relative': 'test the robot base go_to_relative method with a specified position and close loop setting', 'review_main': 'review the main function that creates a Robot and navigates it to a relative position', 'refactor_get_time_str': 'refactor the get_time_str function to use a different timestamp format'}
```

## File: facebookresearch_pyrobot/examples/locobot/navigation/base_position_control_with_map.py

Prompts

```
['run the locobot base position control script to navigate the robot to a relative position', 'run the robot navigation demo with a configurable base controller and planner', 'test the robot base go_to_relative method with a specified position and close loop setting', 'review the main function that creates a Robot and navigates it to a relative position', 'refactor the get_time_str function to use a different timestamp format', 'run the locobot navigation script to move the robot to a relative position using map-based path planning', 'run the robot navigation demo with a custom base controller like ilqr and movebase planner', 'run the robot base navigation with closed-loop control and smooth trajectory enabled', 'review the main function that initializes a Robot with base config and executes go_to_relative navigation', 'review the get_time_str function that returns a formatted YYYY-MM-DD-HH-MM-SS timestamp string', 'run a locobot in circle trajectory tracking mode using the ilqr base controller', 'run a locobot in twocircles trajectory tracking mode with close loop control', 'run trajectory tracking on a custom robot name like locobot_lite with proportional controller', 'get the circle trajectory states for a robot using its odom and base config', 'get the twocircles trajectory states by concatenating a circle and negcircle path', 'run the locobot 3D map visualization using open3d and VSLAM point cloud data', 'create a locobot robot instance using the pyrobot Robot class for navigation tasks', 'get 3D map points and colors from the robot VSLAM system using get_3d_map', 'visualize a point cloud with colors in an open3d Visualizer window with coordinate frame', 'handle SIGINT signal to gracefully exit the 3D map visualization loop']
```

Usage

```
{'run_robot_navigation_to_relative_position': 'run the locobot navigation script to move the robot to a relative position using map-based path planning', 'run_robot_with_custom_controller_and_planner': 'run the robot navigation demo with a custom base controller like ilqr and movebase planner', 'run_robot_navigation_with_closed_loop': 'run the robot base navigation with closed-loop control and smooth trajectory enabled', 'review_main_robot_initialization_and_navigation': 'review the main function that initializes a Robot with base config and executes go_to_relative navigation', 'review_get_time_str_timestamp_formatting': 'review the get_time_str function that returns a formatted YYYY-MM-DD-HH-MM-SS timestamp string'}
```

## File: facebookresearch_pyrobot/examples/locobot/navigation/base_trajectory_tracking.py

Prompts

```
['run the locobot base position control script to navigate the robot to a relative position', 'run the robot navigation demo with a configurable base controller and planner', 'test the robot base go_to_relative method with a specified position and close loop setting', 'review the main function that creates a Robot and navigates it to a relative position', 'refactor the get_time_str function to use a different timestamp format', 'run the locobot navigation script to move the robot to a relative position using map-based path planning', 'run the robot navigation demo with a custom base controller like ilqr and movebase planner', 'run the robot base navigation with closed-loop control and smooth trajectory enabled', 'review the main function that initializes a Robot with base config and executes go_to_relative navigation', 'review the get_time_str function that returns a formatted YYYY-MM-DD-HH-MM-SS timestamp string', 'run a locobot in circle trajectory tracking mode using the ilqr base controller', 'run a locobot in twocircles trajectory tracking mode with close loop control', 'run trajectory tracking on a custom robot name like locobot_lite with proportional controller', 'get the circle trajectory states for a robot using its odom and base config', 'get the twocircles trajectory states by concatenating a circle and negcircle path', 'run the locobot 3D map visualization using open3d and VSLAM point cloud data', 'create a locobot robot instance using the pyrobot Robot class for navigation tasks', 'get 3D map points and colors from the robot VSLAM system using get_3d_map', 'visualize a point cloud with colors in an open3d Visualizer window with coordinate frame', 'handle SIGINT signal to gracefully exit the 3D map visualization loop']
```

Usage

```
{'run_trajectory_circle': 'run a locobot in circle trajectory tracking mode using the ilqr base controller', 'run_trajectory_twocircles': 'run a locobot in twocircles trajectory tracking mode with close loop control', 'run_trajectory_custom_bot': 'run trajectory tracking on a custom robot name like locobot_lite with proportional controller', 'get_trajectory_circle': 'get the circle trajectory states for a robot using its odom and base config', 'get_trajectory_twocircles': 'get the twocircles trajectory states by concatenating a circle and negcircle path'}
```

## File: facebookresearch_pyrobot/examples/locobot/navigation/vis_3d_map.py

Prompts

```
['run the locobot base position control script to navigate the robot to a relative position', 'run the robot navigation demo with a configurable base controller and planner', 'test the robot base go_to_relative method with a specified position and close loop setting', 'review the main function that creates a Robot and navigates it to a relative position', 'refactor the get_time_str function to use a different timestamp format', 'run the locobot navigation script to move the robot to a relative position using map-based path planning', 'run the robot navigation demo with a custom base controller like ilqr and movebase planner', 'run the robot base navigation with closed-loop control and smooth trajectory enabled', 'review the main function that initializes a Robot with base config and executes go_to_relative navigation', 'review the get_time_str function that returns a formatted YYYY-MM-DD-HH-MM-SS timestamp string', 'run a locobot in circle trajectory tracking mode using the ilqr base controller', 'run a locobot in twocircles trajectory tracking mode with close loop control', 'run trajectory tracking on a custom robot name like locobot_lite with proportional controller', 'get the circle trajectory states for a robot using its odom and base config', 'get the twocircles trajectory states by concatenating a circle and negcircle path', 'run the locobot 3D map visualization using open3d and VSLAM point cloud data', 'create a locobot robot instance using the pyrobot Robot class for navigation tasks', 'get 3D map points and colors from the robot VSLAM system using get_3d_map', 'visualize a point cloud with colors in an open3d Visualizer window with coordinate frame', 'handle SIGINT signal to gracefully exit the 3D map visualization loop']
```

Usage

```
{'run_3d_map_visualization': 'run the locobot 3D map visualization using open3d and VSLAM point cloud data', 'create_locobot_robot': 'create a locobot robot instance using the pyrobot Robot class for navigation tasks', 'get_3d_map_points': 'get 3D map points and colors from the robot VSLAM system using get_3d_map', 'visualize_point_cloud': 'visualize a point cloud with colors in an open3d Visualizer window with coordinate frame', 'handle_sigint_signal': 'handle SIGINT signal to gracefully exit the 3D map visualization loop'}
```

